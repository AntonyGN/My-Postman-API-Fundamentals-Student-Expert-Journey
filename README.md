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

## First API request 
Using the request ``URL`` to ``GET`` ```https://library-api.postmanlabs.com/books```

Task: Search books by genre
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

   

