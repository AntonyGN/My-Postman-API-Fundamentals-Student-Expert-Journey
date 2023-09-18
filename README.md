# Postman-API-Fundamentals-Student-Expert

Testing the curl request using terminal
curl ``https://api.github.com/users/postmanlabs``

JSON (JavaScript Object Notation) response
```(base) Antony-MacBook-Pro:~ antony$ curl https://api.github.com/users/postmanlabs
{
  "login": "postmanlabs",
  "id": 10251060,
  "node_id": "MDEyOk9yZ2FuaXphdGlvbjEwMjUxMDYw",
  "avatar_url": "https://avatars.githubusercontent.com/u/10251060?v=4",
  "gravatar_id": "",
  "url": "https://api.github.com/users/postmanlabs",
  "html_url": "https://github.com/postmanlabs",
  "followers_url": "https://api.github.com/users/postmanlabs/followers",
  "following_url": "https://api.github.com/users/postmanlabs/following{/other_user}",
  "gists_url": "https://api.github.com/users/postmanlabs/gists{/gist_id}",
  "starred_url": "https://api.github.com/users/postmanlabs/starred{/owner}{/repo}",
  "subscriptions_url": "https://api.github.com/users/postmanlabs/subscriptions",
  "organizations_url": "https://api.github.com/users/postmanlabs/orgs",
  "repos_url": "https://api.github.com/users/postmanlabs/repos",
  "events_url": "https://api.github.com/users/postmanlabs/events{/privacy}",
  "received_events_url": "https://api.github.com/users/postmanlabs/received_events",
  "type": "Organization",
  "site_admin": false,
  "name": "Postman Inc.",
  "company": null,
  "blog": "https://www.postman.com/",
  "location": "United States of America",
  "email": "help@postman.com",
  "hireable": null,
  "bio": "An API platform for building and using APIs",
  "twitter_username": "getpostman",
  "public_repos": 170,
  "public_gists": 0,
  "followers": 1687,
  "following": 0,
  "created_at": "2014-12-20T08:13:58Z",
  "updated_at": "2022-11-28T22:51:35Z"
}
```

# First API request 
Using the request ``URL`` to ``GET`` ```https://library-api.postmanlabs.com/books```

## Task: Search books by genre
The API allows us to add query parameters to a ``GET /books`` request to filter the results

## Get all fiction books

Let's filter the library catalog to get all the fiction books. We can recycle the first request since we are hitting the same ``GET /books`` endpoint.

1. In Postman inside the ``Postman Library API v2 Collection`` you made, hover over the ``get books`` request, click the three dots icon that appears, then select Duplicate to create a copy of the request.

2. Rename this second request from the default ``get books Copy`` to ``get fiction books``. You can hover on the collection name in the right pane and click the edit icon that appears.

3. Using the ``Params tab``, add a query parameter with key ``genre`` and value ``fiction`` to the ``get fiction books`` request. Notice how Postman syncs the request URL in real time, adding the question mark ? automatically to mark the start of query parameters!

4. Save your request

5. Send your request

6. You should get a ``200 OK`` response with an array of books objects - but only books with the ``fiction genre!``

  Request ``URL``to Get all fiction books ```https://library-api.postmanlabs.com/books?genre=fiction```

# Task: Multiple query parameters

As a librarian you'll need to help visitors find books that are available (not checked out).

Let's add a second query parameter to ``GET /books`` to only return books where the ``checkedOut`` property is false. 

## Add another query parameter
1. In the same ``get fiction books`` request, in the ``Params`` tab add a second query parameter with ```key checkedOut``` and value ``false``

2. Save your request 

3. Send your request

You should get a ``200 OK`` response with an array of only fiction books that are not checked out, or an empty array [] if there are no fiction books available.

  Request ``URL``to multiple query parameters ```https://library-api.postmanlabs.com/books?genre=fiction&checkedOut=false```

  JSON response 
  ```
{
        "id": "d284914a-4b60-4d9d-b76b-c3ffbe5f6a05",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-18T06:50:46.080Z"
    },
```

# Path Parameters

Another way of passing request data to an API is via path parameters. A path parameter (or "path variable") is a dynamic section of a path, and is often used for IDs and entity names such as usernames. 

## Path parameter syntax

Path parameters come immediately after a slash in the path. For example, the GitHub API allows you to search for GitHub users by providing a username in the path in place of ``{username}`` below:

```GET https://api.github.com/users/{username}```

Making this API call with a value for ``{username}`` will fetch data about that user:

```GET https://api.github.com/users/postmanlabs```

You can have multiple path parameters in a single request, such as this endpoint for getting a user's GitHub code repository:

```GET https://api.github.com/repos/{owner}/{repoName}```

For example, to get information about the newman code repository from postmanlabs:

```GET https://api.github.com/repos/postmanlabs/newman```

# Task: Get a book by id

Someone keeps coming into the library every day asking whether ``Ficciones`` by Jorge Luis Borges is available. 

When you fetched all the books in the library, you may have noticed that each book as a unique ``id`` value. This ``id`` can always be used to identify the book, even if its other properties are changed.

Since this person keeps asking about ``Ficciones``, you've jotted down that the unique ``id`` for this book is ``29cd820f-82f9-4b45-a7f4-0924111b5b89``

(Don't believe me? You can always search for ``Ficciones`` with the search query parameter: ``GET /books?search=ficciones``)

## Get a book by id

According to the API documentation, we can get a specific book by hitting the path ``GET /books/:id``, where we replace ``:id`` with the book's ``id``.

1. Hover on your Postman Library API v2 Collection, click the three dots icon and select ``Add request``. Name your new request ``get book by id``

2. Make sure the request method is set to ``GET``, and paste in this endpoint as the request URL: ```https://library-api.postmanlabs.com/books/:id```

   Postman automatically adds a ``Path Variables`` editor in the ``Params`` tab of the request for any path parameters in the request URL prefixed with a colon :

3. In the ``Params`` tab of the request, paste the ``id`` for ``Ficciones`` (``29cd820f-82f9-4b45-a7f4-0924111b5b89``) as the ``value`` for the parameter named ``id``. *Make sure not to add any whitespace around the id value*.

4. Save your request

5. Send your request

You should get a ``200 OK`` response with a single JSON object that represents the ``Ficciones`` book. At the time of this example, the book is not checked out:

``JSON` response

```
{
    "id": "29cd820f-82f9-4b45-a7f4-0924111b5b89",
    "title": "Ficciones",
    "author": "Jorge Luis Borges",
    "genre": "fiction",
    "yearPublished": 1944,
    "checkedOut": false,
    "isPermanentCollection": true,
    "createdAt": "2022-03-30T00:54:52.606Z"
}
```













   

   

