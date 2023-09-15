# Postman-API-Fundamentals-Student-Expert-Journey
Testing the curl request
```curl https://api.github.com/users/postmanlabs```

### Repsonse
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

JSON (JavaScript Object Notation) response
```[
    {
        "id": "0ad045b4-7804-4fe1-8cf7-b1e98945464c",
        "title": "Bulbul2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:15:50.273Z"
    },
    {
        "id": "dc487836-0b9b-44f5-9284-de635d64d65e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:12:22.140Z"
    },
    {
        "id": "7c55dc7b-1dac-494d-9bd4-021b11c717dd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:06:34.694Z"
    },
    {
        "id": "f65beb69-21f5-4944-97f6-0f651ea798bb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:04:24.864Z"
    },
    {
        "id": "9a9275b4-88f8-4042-8b34-0b38bb922cbf",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:01:25.419Z"
    },
    {
        "id": "794b0d64-4ea1-40a4-b8c5-1c918856a485",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T08:00:36.566Z"
    },
    {
        "id": "4de3ea36-5e7e-42d3-807f-36bd73e0153d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:59:55.441Z"
    },
    {
        "id": "ffb3d63e-2fe9-4241-9f51-4eb19ebd2dc1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:58:25.053Z"
    },
    {
        "id": "70495266-10ba-43b9-a960-1e7117d91b15",
        "title": "Lord of the Flies",
        "author": "William Golding",
        "genre": "fiction",
        "yearPublished": 1954,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:47:36.961Z"
    },
    {
        "id": "0f949b13-b91f-4f7d-9ff7-0a2dcbbe7393",
        "title": "Lord of the Flies",
        "author": "William Golding",
        "genre": "fiction",
        "yearPublished": 1954,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:47:14.078Z"
    },
    {
        "id": "4f728b80-5f0e-4ec8-af38-7300097b67a2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:45:07.894Z"
    },
    {
        "id": "86542f9c-df94-40db-8f77-b72202fdda1c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:44:04.470Z"
    },
    {
        "id": "41fb4161-5c54-4e1f-9e45-5c397bd4908e",
        "title": "Lord of the Flies",
        "author": "William Golding",
        "genre": "fiction",
        "yearPublished": 1954,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:43:23.103Z"
    },
    {
        "id": "64e43535-d7bf-44f7-a0c2-543f4653f5c9",
        "title": "Dicta quasi qui.",
        "author": "Cody Flatley",
        "genre": "tech",
        "yearPublished": 375,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:39:11.987Z"
    },
    {
        "id": "9b54de21-341d-4299-a714-7ea6535c75fa",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:38:32.135Z"
    },
    {
        "id": "b126a95d-cb2b-40df-8422-17df0b8c0a1c",
        "title": "Bulbul2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:36:23.988Z"
    },
    {
        "id": "ca641191-4ecf-421d-be67-f81cbf4af52d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:35:17.630Z"
    },
    {
        "id": "1cbd82c1-a25e-42fd-9143-45bdcdc50785",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:33:02.880Z"
    },
    {
        "id": "671d4a22-2a6e-4ee4-91ba-656036719938",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:33:02.486Z"
    },
    {
        "id": "6e63a399-2b73-42eb-837f-aebb1878ce12",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:30:51.853Z"
    },
    {
        "id": "d59f0d00-f7f2-4902-8395-abdbe07e8ce0",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:30:26.928Z"
    },
    {
        "id": "8a8223d0-0083-4a92-97ad-36106bd8f7f6",
        "title": "To Love Is Good",
        "author": "Veronica Banks",
        "genre": "Thriller",
        "yearPublished": 1967,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:49.001Z"
    },
    {
        "id": "3625e21c-a73d-4eef-85f9-2af1823558dc",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:37.487Z"
    },
    {
        "id": "4cc0ada0-eafa-4e51-895e-32f780130b1e",
        "title": "Dicta quasi qui.",
        "author": "Cody Flatley",
        "genre": "tech",
        "yearPublished": 375,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:37.333Z"
    },
    {
        "id": "cb8c4ef4-bb1f-48b9-bf74-c09e72ee126e",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:22.752Z"
    },
    {
        "id": "9a355405-5a23-4751-a1b5-540a3fbce676",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:12.438Z"
    },
    {
        "id": "413cd992-130f-4752-8f99-e19e4c104891",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:29:10.823Z"
    },
    {
        "id": "d7ea513d-f084-462e-ba5f-ec702d1cca9e",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:28:56.283Z"
    },
    {
        "id": "cb333afd-d43a-4a87-a843-d2879f2fe312",
        "title": "To Love Is Good",
        "author": "Veronica Banks",
        "genre": "Thriller",
        "yearPublished": 1967,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:28:33.161Z"
    },
    {
        "id": "32534f4f-68c0-4c82-97a4-20fcecbcc2c9",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:28:07.791Z"
    },
    {
        "id": "cf987b91-f054-4bc2-8e0b-8ccab635bfb6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:28:00.735Z"
    },
    {
        "id": "1c29427a-94d8-419c-846b-f2bdcd2ea324",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:56.222Z"
    },
    {
        "id": "69936f80-69d7-44bb-b77d-bb9b15184c30",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:55.860Z"
    },
    {
        "id": "07afa070-45a7-47be-ac83-a43a8fa5c1ed",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:55.452Z"
    },
    {
        "id": "3746c24c-c8d3-4a77-ad58-9b994c0f42bc",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:55.144Z"
    },
    {
        "id": "e7148c0a-3d3a-4e54-9f60-e7d327c07086",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:54.267Z"
    },
    {
        "id": "4830d783-62d6-4396-bc29-d1e413d81701",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:33.533Z"
    },
    {
        "id": "e92df931-327b-4a0e-a4ad-eb88e03fc022",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:18.520Z"
    },
    {
        "id": "54890b95-afd6-4c31-b54f-f9066eb442d4",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:18.196Z"
    },
    {
        "id": "a00ea848-8e99-4595-b4e1-6402ce339647",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:17.837Z"
    },
    {
        "id": "6ffc85f9-628f-43c3-ab9d-3915c98d04c8",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:17.511Z"
    },
    {
        "id": "abd1b101-781a-4047-a0dd-8f3772b26060",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:16.546Z"
    },
    {
        "id": "2c46c7df-deaa-4911-ac1f-6a72e2c9b1c2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:09.514Z"
    },
    {
        "id": "a2e7ac5e-fdf2-4c95-bfad-c7d0b9e22c0c",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:04.977Z"
    },
    {
        "id": "75ecb2c1-c5fd-4f60-bd2a-ac3f26d1b7e3",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:04.599Z"
    },
    {
        "id": "6ad956c0-2ed4-4d61-b9a2-905cc7f25468",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:04.267Z"
    },
    {
        "id": "2a49b795-9b6f-4351-8202-8bbb501c3860",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:03.946Z"
    },
    {
        "id": "df4e8c0f-ffe7-4277-b6f7-3c519ed92f24",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:26:02.050Z"
    },
    {
        "id": "bc6a8792-dcce-4c20-b3aa-c816896be146",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:15.536Z"
    },
    {
        "id": "9ce9d67a-3267-4ac1-8bfe-1de71e78234b",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:15.195Z"
    },
    {
        "id": "5c1d52af-14bc-4f84-8e99-affa9bb21bfc",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:14.833Z"
    },
    {
        "id": "5eddaab6-6f33-4a72-b0a0-cb2068d28330",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:14.499Z"
    },
    {
        "id": "f0040c0d-1740-4f6a-89f1-5587086dd913",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:13.490Z"
    },
    {
        "id": "64e5341a-698b-4dfc-b7ed-1b43c1688ad9",
        "title": "Ronaldo",
        "author": "Messi",
        "genre": "fiction",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:25:10.883Z"
    },
    {
        "id": "3a2874b9-9e16-462e-9e80-81614db04855",
        "title": "The Alchemists",
        "author": "Pablo Coelo",
        "genre": "fiction",
        "yearPublished": 2002,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:24:46.694Z"
    },
    {
        "id": "22325cd5-2ee0-472a-b4e0-df0e61a8102b",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:23:48.023Z"
    },
    {
        "id": "6dfd31ac-d9fe-473e-a82b-efcbc192253e",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:23:47.709Z"
    },
    {
        "id": "96993103-b0d2-48c5-885d-2741e33c1019",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:23:47.377Z"
    },
    {
        "id": "0e6bff0c-4638-4458-9a2f-5839c2fbe226",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:23:46.194Z"
    },
    {
        "id": "1b16b090-1994-4c20-8ff8-ebb333fbe7a1",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:23:45.225Z"
    },
    {
        "id": "9b6a7dea-8daa-4033-8ef8-7b31136fe733",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:22:32.263Z"
    },
    {
        "id": "1a6dc759-8d57-476c-bdd0-6648bbcff094",
        "title": "To Love is to hate",
        "author": "Veronica Banks",
        "genre": "Thriller",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:22:32.118Z"
    },
    {
        "id": "2d416567-e683-41a6-981d-d93e48f871fb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:20:51.289Z"
    },
    {
        "id": "78b9c191-b450-4dc1-a12b-38930431c0a7",
        "title": "To Love is to hate",
        "author": "Veronica Banks",
        "genre": "Thriller",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:20:39.911Z"
    },
    {
        "id": "845baba9-387d-400f-bb3e-1ceef4d2b799",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:20:15.902Z"
    },
    {
        "id": "1507678e-0731-4c7c-bb21-d3faf62df910",
        "title": "Grandma's Bag of Stories",
        "author": "Sudha Murty",
        "genre": "fiction",
        "yearPublished": 2012,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:19:14.356Z"
    },
    {
        "id": "c6b8ee26-b9d3-45b2-a0c3-381e953e9557",
        "title": "Dicta quasi qui.",
        "author": "Cody Flatley",
        "genre": "tech",
        "yearPublished": 375,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:16:15.208Z"
    },
    {
        "id": "665b80a9-ac96-4399-8fb6-ebf74e6d79ca",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:13:09.176Z"
    },
    {
        "id": "cd6bbd11-2c28-407f-90a2-441969f5ec25",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:12:55.901Z"
    },
    {
        "id": "51ee153e-1d6e-47b3-9c4d-d08e285ec563",
        "title": "Wings of Fire",
        "author": "A. P. J. Abdul Kalam and Arun Tiwari",
        "genre": "Autobiography",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:12:54.614Z"
    },
    {
        "id": "fa5f50dd-d0db-4aec-ae63-597c0673496a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:12:30.319Z"
    },
    {
        "id": "1d41814b-a436-483f-b90f-6882bd6b569e",
        "title": "Little Women",
        "author": "Louisa May Alcott",
        "genre": "fiction",
        "yearPublished": 1868,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:12:07.384Z"
    },
    {
        "id": "657f6825-58a9-46ee-b364-7be0b38b77eb",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:09:25.753Z"
    },
    {
        "id": "c5e78bbf-61bd-41aa-a6c1-1ec5c92c946f",
        "title": "a monke has lived his life99 times",
        "author": "mr. monke99",
        "genre": "climate",
        "yearPublished": 1309,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:15.530Z"
    },
    {
        "id": "11eb256a-5116-49ee-b341-e376fc65b6a2",
        "title": "a monke has lived his life98 times",
        "author": "mr. monke98",
        "genre": "climate",
        "yearPublished": 1308,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:15.167Z"
    },
    {
        "id": "62da12d6-6adc-42f1-8ec8-999c4841206c",
        "title": "a monke has lived his life97 times",
        "author": "mr. monke97",
        "genre": "climate",
        "yearPublished": 1307,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:14.810Z"
    },
    {
        "id": "802c23e1-6471-45fa-b6eb-fb91ded6d5f2",
        "title": "a monke has lived his life96 times",
        "author": "mr. monke96",
        "genre": "climate",
        "yearPublished": 1306,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:14.473Z"
    },
    {
        "id": "5515ac78-1088-4fa9-aea8-55a295fc9f4e",
        "title": "a monke has lived his life95 times",
        "author": "mr. monke95",
        "genre": "climate",
        "yearPublished": 1305,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:14.141Z"
    },
    {
        "id": "28dd4054-5331-4bbe-b6e3-03388af6c7c0",
        "title": "a monke has lived his life94 times",
        "author": "mr. monke94",
        "genre": "climate",
        "yearPublished": 1304,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:13.750Z"
    },
    {
        "id": "5986b24a-12fc-4020-b481-35c04ff698f7",
        "title": "a monke has lived his life93 times",
        "author": "mr. monke93",
        "genre": "climate",
        "yearPublished": 1303,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:13.392Z"
    },
    {
        "id": "a4471106-226a-4f54-b172-414453d31e64",
        "title": "a monke has lived his life92 times",
        "author": "mr. monke92",
        "genre": "climate",
        "yearPublished": 1302,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:13.039Z"
    },
    {
        "id": "bfcdcb0a-3212-427b-9e89-45f4da1e20dd",
        "title": "a monke has lived his life91 times",
        "author": "mr. monke91",
        "genre": "climate",
        "yearPublished": 1301,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:12.695Z"
    },
    {
        "id": "736905f6-8fc1-4894-952a-f2e15cbc1813",
        "title": "a monke has lived his life90 times",
        "author": "mr. monke90",
        "genre": "climate",
        "yearPublished": 1300,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:12.332Z"
    },
    {
        "id": "0995e189-d14b-4d0f-a5a1-f9d6d49aa5c5",
        "title": "a monke has lived his life89 times",
        "author": "mr. monke89",
        "genre": "climate",
        "yearPublished": 1299,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:11.983Z"
    },
    {
        "id": "4cfac1fb-4fa7-46d8-bbea-f6aa6f879b1c",
        "title": "a monke has lived his life88 times",
        "author": "mr. monke88",
        "genre": "climate",
        "yearPublished": 1298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:11.626Z"
    },
    {
        "id": "cb20daa4-3a08-481d-8275-ea99e40527e8",
        "title": "a monke has lived his life87 times",
        "author": "mr. monke87",
        "genre": "climate",
        "yearPublished": 1297,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:11.270Z"
    },
    {
        "id": "5ba0333b-2295-4e54-8ae3-0d543912b015",
        "title": "a monke has lived his life86 times",
        "author": "mr. monke86",
        "genre": "climate",
        "yearPublished": 1296,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:10.914Z"
    },
    {
        "id": "382299c4-d0cd-4395-a6d8-b5763c5e4b81",
        "title": "a monke has lived his life85 times",
        "author": "mr. monke85",
        "genre": "climate",
        "yearPublished": 1295,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:10.563Z"
    },
    {
        "id": "34d57864-b418-4b07-b9db-6015eacd0bba",
        "title": "a monke has lived his life84 times",
        "author": "mr. monke84",
        "genre": "climate",
        "yearPublished": 1294,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:10.230Z"
    },
    {
        "id": "79e70a63-c60c-47cf-b85c-f40fd7f985e4",
        "title": "a monke has lived his life83 times",
        "author": "mr. monke83",
        "genre": "climate",
        "yearPublished": 1293,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:09.891Z"
    },
    {
        "id": "e19ed8bd-7958-4b6c-acd5-5117f780d23c",
        "title": "a monke has lived his life82 times",
        "author": "mr. monke82",
        "genre": "climate",
        "yearPublished": 1292,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:09.555Z"
    },
    {
        "id": "7e3ceb0e-61b6-4faf-bfbd-e64e36a39bdf",
        "title": "a monke has lived his life81 times",
        "author": "mr. monke81",
        "genre": "climate",
        "yearPublished": 1291,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:09.228Z"
    },
    {
        "id": "05a376e6-d273-454c-a85b-2e3cbdac801b",
        "title": "a monke has lived his life80 times",
        "author": "mr. monke80",
        "genre": "climate",
        "yearPublished": 1290,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:08.906Z"
    },
    {
        "id": "48e5e751-fcde-4976-b76d-bf33d5d32ccf",
        "title": "a monke has lived his life79 times",
        "author": "mr. monke79",
        "genre": "climate",
        "yearPublished": 1289,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:08.571Z"
    },
    {
        "id": "025b6206-236e-4a87-a69a-0349aeb54235",
        "title": "a monke has lived his life78 times",
        "author": "mr. monke78",
        "genre": "climate",
        "yearPublished": 1288,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:08.229Z"
    },
    {
        "id": "8e1ba741-5ccc-45d2-802c-f76e6784fcf0",
        "title": "a monke has lived his life77 times",
        "author": "mr. monke77",
        "genre": "climate",
        "yearPublished": 1287,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:07.899Z"
    },
    {
        "id": "7b78e788-07a6-40ae-ae36-7e0c25f7bc44",
        "title": "a monke has lived his life76 times",
        "author": "mr. monke76",
        "genre": "climate",
        "yearPublished": 1286,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:07.567Z"
    },
    {
        "id": "03f47d92-fceb-41d0-8896-c69c0976b77f",
        "title": "a monke has lived his life75 times",
        "author": "mr. monke75",
        "genre": "climate",
        "yearPublished": 1285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:07.255Z"
    },
    {
        "id": "28a3913f-ad84-4cd7-b36b-9c4cb5b29564",
        "title": "a monke has lived his life74 times",
        "author": "mr. monke74",
        "genre": "climate",
        "yearPublished": 1284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:06.916Z"
    },
    {
        "id": "8d75e7b3-67be-401a-8ac8-ea13bd611b8c",
        "title": "a monke has lived his life73 times",
        "author": "mr. monke73",
        "genre": "climate",
        "yearPublished": 1283,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:06.584Z"
    },
    {
        "id": "65e37a65-2c14-4ac9-810c-c7099c9230ea",
        "title": "a monke has lived his life72 times",
        "author": "mr. monke72",
        "genre": "climate",
        "yearPublished": 1282,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:06.250Z"
    },
    {
        "id": "0ab4a617-c06c-470c-8cc9-4e9effc5f6b0",
        "title": "a monke has lived his life71 times",
        "author": "mr. monke71",
        "genre": "climate",
        "yearPublished": 1281,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:05.907Z"
    },
    {
        "id": "06bff230-699f-409b-b041-18a2700fd305",
        "title": "a monke has lived his life70 times",
        "author": "mr. monke70",
        "genre": "climate",
        "yearPublished": 1280,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:05.600Z"
    },
    {
        "id": "e8f339cf-2b53-4264-ab67-1415d15174ec",
        "title": "a monke has lived his life69 times",
        "author": "mr. monke69",
        "genre": "climate",
        "yearPublished": 1279,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:05.241Z"
    },
    {
        "id": "423b883d-9846-43f2-a782-def30cd9a0ae",
        "title": "a monke has lived his life68 times",
        "author": "mr. monke68",
        "genre": "climate",
        "yearPublished": 1278,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:04.890Z"
    },
    {
        "id": "023cf142-7866-4768-b109-d5d2044ca9c0",
        "title": "a monke has lived his life67 times",
        "author": "mr. monke67",
        "genre": "climate",
        "yearPublished": 1277,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:04.536Z"
    },
    {
        "id": "09c38c8a-1d20-409d-8456-f280910038d8",
        "title": "a monke has lived his life66 times",
        "author": "mr. monke66",
        "genre": "climate",
        "yearPublished": 1276,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:04.181Z"
    },
    {
        "id": "56115555-9cfa-4009-95fd-4029312f412d",
        "title": "a monke has lived his life65 times",
        "author": "mr. monke65",
        "genre": "climate",
        "yearPublished": 1275,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:03.826Z"
    },
    {
        "id": "08686e3b-27a0-4513-85ea-a74c1e7c359c",
        "title": "a monke has lived his life64 times",
        "author": "mr. monke64",
        "genre": "climate",
        "yearPublished": 1274,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:03.480Z"
    },
    {
        "id": "9293f347-679f-438b-adf8-63719797f481",
        "title": "a monke has lived his life63 times",
        "author": "mr. monke63",
        "genre": "climate",
        "yearPublished": 1273,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:03.124Z"
    },
    {
        "id": "9cefc480-8cec-4176-8129-76a460f36fff",
        "title": "a monke has lived his life62 times",
        "author": "mr. monke62",
        "genre": "climate",
        "yearPublished": 1272,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:02.768Z"
    },
    {
        "id": "339f8ce4-a13d-4818-a378-06fcc8b1f9c7",
        "title": "a monke has lived his life61 times",
        "author": "mr. monke61",
        "genre": "climate",
        "yearPublished": 1271,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:02.426Z"
    },
    {
        "id": "b9769a5c-9e7f-49c4-97c7-4a41f57cc5d3",
        "title": "a monke has lived his life60 times",
        "author": "mr. monke60",
        "genre": "climate",
        "yearPublished": 1270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:02.084Z"
    },
    {
        "id": "fe486e4a-4aac-482e-9d77-3e5cee8d44a7",
        "title": "a monke has lived his life59 times",
        "author": "mr. monke59",
        "genre": "climate",
        "yearPublished": 1269,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:01.703Z"
    },
    {
        "id": "6dd00094-41bd-4305-90d6-9ee48a1a10e8",
        "title": "a monke has lived his life58 times",
        "author": "mr. monke58",
        "genre": "climate",
        "yearPublished": 1268,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:01.346Z"
    },
    {
        "id": "a2caf7d3-5efb-474a-b1ac-89fca90a451e",
        "title": "a monke has lived his life57 times",
        "author": "mr. monke57",
        "genre": "climate",
        "yearPublished": 1267,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:00.992Z"
    },
    {
        "id": "c44775d3-481f-46fc-a833-5a2d29d47b3d",
        "title": "a monke has lived his life56 times",
        "author": "mr. monke56",
        "genre": "climate",
        "yearPublished": 1266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:00.634Z"
    },
    {
        "id": "39a92daf-0142-43dd-ab65-c9e1e6b0da13",
        "title": "a monke has lived his life55 times",
        "author": "mr. monke55",
        "genre": "climate",
        "yearPublished": 1265,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:08:00.283Z"
    },
    {
        "id": "3d76f87c-b4a5-4e8f-a2f4-909604b811ea",
        "title": "a monke has lived his life54 times",
        "author": "mr. monke54",
        "genre": "climate",
        "yearPublished": 1264,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:59.929Z"
    },
    {
        "id": "3b4b3508-96f1-46ae-a8ff-ff327bf6a6c2",
        "title": "a monke has lived his life53 times",
        "author": "mr. monke53",
        "genre": "climate",
        "yearPublished": 1263,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:59.571Z"
    },
    {
        "id": "2c0a284d-1885-4bbb-a75a-18afbed4d60f",
        "title": "a monke has lived his life52 times",
        "author": "mr. monke52",
        "genre": "climate",
        "yearPublished": 1262,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:59.221Z"
    },
    {
        "id": "2c2f1e68-e434-4c4f-8307-c90a675a8648",
        "title": "a monke has lived his life51 times",
        "author": "mr. monke51",
        "genre": "climate",
        "yearPublished": 1261,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:58.272Z"
    },
    {
        "id": "8ed91c28-b0a4-4447-b02a-dee8dd85ab9e",
        "title": "a monke has lived his life50 times",
        "author": "mr. monke50",
        "genre": "climate",
        "yearPublished": 1260,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:57.927Z"
    },
    {
        "id": "9e47db91-6bac-4733-8abc-2520abc4e9b1",
        "title": "a monke has lived his life49 times",
        "author": "mr. monke49",
        "genre": "climate",
        "yearPublished": 1259,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:57.591Z"
    },
    {
        "id": "642a181e-a851-4811-a1b8-fb8d4ebd9836",
        "title": "a monke has lived his life48 times",
        "author": "mr. monke48",
        "genre": "climate",
        "yearPublished": 1258,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:57.209Z"
    },
    {
        "id": "0084b89f-4cf7-45ef-802b-72f13ee0f56a",
        "title": "a monke has lived his life47 times",
        "author": "mr. monke47",
        "genre": "climate",
        "yearPublished": 1257,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:56.862Z"
    },
    {
        "id": "9db00db5-43f7-40c3-a480-cf84f503d51e",
        "title": "a monke has lived his life46 times",
        "author": "mr. monke46",
        "genre": "climate",
        "yearPublished": 1256,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:55.916Z"
    },
    {
        "id": "9b57ab28-8183-41e6-9264-4dab23cb5821",
        "title": "a monke has lived his life45 times",
        "author": "mr. monke45",
        "genre": "climate",
        "yearPublished": 1255,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:55.008Z"
    },
    {
        "id": "81808295-bee0-48c4-a09c-0018d4c11d98",
        "title": "a monke has lived his life44 times",
        "author": "mr. monke44",
        "genre": "climate",
        "yearPublished": 1254,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:54.658Z"
    },
    {
        "id": "a4c56b0c-e540-4f24-a07d-109fd88d6235",
        "title": "a monke has lived his life43 times",
        "author": "mr. monke43",
        "genre": "climate",
        "yearPublished": 1253,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:54.259Z"
    },
    {
        "id": "cf8ba714-e6c9-466f-b7eb-ad89c99831df",
        "title": "a monke has lived his life42 times",
        "author": "mr. monke42",
        "genre": "climate",
        "yearPublished": 1252,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:53.911Z"
    },
    {
        "id": "34fe3431-df73-49ee-a760-d25283015411",
        "title": "a monke has lived his life41 times",
        "author": "mr. monke41",
        "genre": "climate",
        "yearPublished": 1251,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:53.574Z"
    },
    {
        "id": "ae7c6a01-3ba4-47cf-8bf9-bc79dfd49d6b",
        "title": "a monke has lived his life40 times",
        "author": "mr. monke40",
        "genre": "climate",
        "yearPublished": 1250,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:53.230Z"
    },
    {
        "id": "dcb1b01b-2073-4cdc-9118-07dd8043a2c9",
        "title": "a monke has lived his life39 times",
        "author": "mr. monke39",
        "genre": "climate",
        "yearPublished": 1249,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:52.877Z"
    },
    {
        "id": "d8e295fb-78fb-4063-b7d1-fd2edd7d353f",
        "title": "a monke has lived his life38 times",
        "author": "mr. monke38",
        "genre": "climate",
        "yearPublished": 1248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:52.537Z"
    },
    {
        "id": "e1628176-0707-4b4b-9fa5-2834850cd9c7",
        "title": "a monke has lived his life37 times",
        "author": "mr. monke37",
        "genre": "climate",
        "yearPublished": 1247,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:51.610Z"
    },
    {
        "id": "8664a6d1-0ea3-4fa6-8cac-478e620de8e0",
        "title": "a monke has lived his life36 times",
        "author": "mr. monke36",
        "genre": "climate",
        "yearPublished": 1246,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:51.214Z"
    },
    {
        "id": "9ac0f4da-1c8d-4ec4-996c-e3024cd58bb6",
        "title": "a monke has lived his life35 times",
        "author": "mr. monke35",
        "genre": "climate",
        "yearPublished": 1245,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:50.892Z"
    },
    {
        "id": "c67e8f7a-423d-4aab-b9b8-f3aa5563e0b1",
        "title": "a monke has lived his life34 times",
        "author": "mr. monke34",
        "genre": "climate",
        "yearPublished": 1244,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:50.493Z"
    },
    {
        "id": "29ec6bab-f846-4625-8f9b-f951a124289c",
        "title": "a monke has lived his life33 times",
        "author": "mr. monke33",
        "genre": "climate",
        "yearPublished": 1243,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:50.156Z"
    },
    {
        "id": "ff2a2e3a-4d6f-4e7d-8dda-b01b4755b6f0",
        "title": "a monke has lived his life32 times",
        "author": "mr. monke32",
        "genre": "climate",
        "yearPublished": 1242,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:49.766Z"
    },
    {
        "id": "a92af2d9-86a0-4760-aae4-a36b941b2bf1",
        "title": "a monke has lived his life31 times",
        "author": "mr. monke31",
        "genre": "climate",
        "yearPublished": 1241,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:49.416Z"
    },
    {
        "id": "753422f2-f787-4e2f-ba8c-c7d571fc3b78",
        "title": "a monke has lived his life30 times",
        "author": "mr. monke30",
        "genre": "climate",
        "yearPublished": 1240,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:49.059Z"
    },
    {
        "id": "05275b13-b8f9-4e6a-abc3-09a324110d6a",
        "title": "a monke has lived his life29 times",
        "author": "mr. monke29",
        "genre": "climate",
        "yearPublished": 1239,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:48.709Z"
    },
    {
        "id": "20c1abc3-a306-4243-a219-d0a59fef33c3",
        "title": "a monke has lived his life28 times",
        "author": "mr. monke28",
        "genre": "climate",
        "yearPublished": 1238,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:48.359Z"
    },
    {
        "id": "3e563786-3cfc-4f44-8934-7b993dd5bb20",
        "title": "a monke has lived his life27 times",
        "author": "mr. monke27",
        "genre": "climate",
        "yearPublished": 1237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:48.002Z"
    },
    {
        "id": "53a20f4b-74a8-4ddc-a16b-80d925038d35",
        "title": "a monke has lived his life26 times",
        "author": "mr. monke26",
        "genre": "climate",
        "yearPublished": 1236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:47.655Z"
    },
    {
        "id": "d996bc8d-847c-4d19-a78b-0e4a86b8bcdf",
        "title": "a monke has lived his life25 times",
        "author": "mr. monke25",
        "genre": "climate",
        "yearPublished": 1235,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:47.291Z"
    },
    {
        "id": "45f365a8-9224-455c-a197-20c0a54925b7",
        "title": "a monke has lived his life24 times",
        "author": "mr. monke24",
        "genre": "climate",
        "yearPublished": 1234,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:46.947Z"
    },
    {
        "id": "6b67f607-654c-453b-91b9-e52a58f1b6fd",
        "title": "a monke has lived his life23 times",
        "author": "mr. monke23",
        "genre": "climate",
        "yearPublished": 1233,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:46.588Z"
    },
    {
        "id": "fac9dbe4-8b4e-43a8-af51-b86e48ab0204",
        "title": "a monke has lived his life22 times",
        "author": "mr. monke22",
        "genre": "climate",
        "yearPublished": 1232,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:46.228Z"
    },
    {
        "id": "a52bd5bd-a70b-47e2-8c08-19b25b5ca4fd",
        "title": "a monke has lived his life21 times",
        "author": "mr. monke21",
        "genre": "climate",
        "yearPublished": 1231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:45.876Z"
    },
    {
        "id": "5c8d39b4-7eda-4a44-aeb1-ccd1993a7a96",
        "title": "a monke has lived his life20 times",
        "author": "mr. monke20",
        "genre": "climate",
        "yearPublished": 1230,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:45.534Z"
    },
    {
        "id": "b8daa186-c673-46ba-8efa-bbcfa2474207",
        "title": "a monke has lived his life19 times",
        "author": "mr. monke19",
        "genre": "climate",
        "yearPublished": 1229,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:45.186Z"
    },
    {
        "id": "bcd9358b-a2b8-4c28-a24f-05dd14d522c6",
        "title": "a monke has lived his life18 times",
        "author": "mr. monke18",
        "genre": "climate",
        "yearPublished": 1228,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:44.849Z"
    },
    {
        "id": "3faf2397-8ba6-4789-a08d-11b105e3c649",
        "title": "a monke has lived his life17 times",
        "author": "mr. monke17",
        "genre": "climate",
        "yearPublished": 1227,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:44.504Z"
    },
    {
        "id": "1bdb3001-0670-4d9b-8295-b92813355f82",
        "title": "a monke has lived his life16 times",
        "author": "mr. monke16",
        "genre": "climate",
        "yearPublished": 1226,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:44.152Z"
    },
    {
        "id": "3284380c-d00a-44aa-9267-1061c6a83455",
        "title": "a monke has lived his life15 times",
        "author": "mr. monke15",
        "genre": "climate",
        "yearPublished": 1225,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:43.744Z"
    },
    {
        "id": "f7d6e47d-cb54-42c2-81bf-e9ffeaf4a04f",
        "title": "a monke has lived his life14 times",
        "author": "mr. monke14",
        "genre": "climate",
        "yearPublished": 1224,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:43.394Z"
    },
    {
        "id": "c9723349-4856-4464-93a3-45dee0d0ff84",
        "title": "a monke has lived his life13 times",
        "author": "mr. monke13",
        "genre": "climate",
        "yearPublished": 1223,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:43.036Z"
    },
    {
        "id": "a06457e4-ccc4-4780-8a66-ed6a89ba8218",
        "title": "a monke has lived his life12 times",
        "author": "mr. monke12",
        "genre": "climate",
        "yearPublished": 1222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:42.689Z"
    },
    {
        "id": "533e1186-9159-4f0f-9b4e-ce93a6d355bb",
        "title": "a monke has lived his life11 times",
        "author": "mr. monke11",
        "genre": "climate",
        "yearPublished": 1221,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:41.539Z"
    },
    {
        "id": "b9d53079-4ee5-413c-a5af-feff0989f990",
        "title": "a monke has lived his life10 times",
        "author": "mr. monke10",
        "genre": "climate",
        "yearPublished": 1220,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:40.495Z"
    },
    {
        "id": "e3890eea-10c1-4521-9758-f65cd20fd11c",
        "title": "a monke has lived his life9 times",
        "author": "mr. monke9",
        "genre": "climate",
        "yearPublished": 1219,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:40.156Z"
    },
    {
        "id": "0ea6b28e-36dc-47c4-957d-8c2d78cdd27f",
        "title": "a monke has lived his life8 times",
        "author": "mr. monke8",
        "genre": "climate",
        "yearPublished": 1218,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:39.148Z"
    },
    {
        "id": "be87855a-3339-47df-ab06-bf062c1bdb16",
        "title": "a monke has lived his life7 times",
        "author": "mr. monke7",
        "genre": "climate",
        "yearPublished": 1217,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:38.797Z"
    },
    {
        "id": "3419d748-b418-4db4-94ae-769ccaaceb07",
        "title": "a monke has lived his life6 times",
        "author": "mr. monke6",
        "genre": "climate",
        "yearPublished": 1216,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:38.431Z"
    },
    {
        "id": "a4049f82-c12d-4fe5-85ef-0ff50cb1c007",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:38.079Z"
    },
    {
        "id": "5761c318-2c56-4db1-900c-663dc4d011f8",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:37.761Z"
    },
    {
        "id": "a2fb0381-30a1-471a-8e0f-c63cce68561f",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:37.426Z"
    },
    {
        "id": "4429b31b-899e-44db-abe5-eb08416016b7",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:37.082Z"
    },
    {
        "id": "b7375da3-793d-4831-9a74-44db76888ae9",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:35.830Z"
    },
    {
        "id": "9d9ea2b9-f027-421f-aa6d-dc5a9477ca33",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:34.771Z"
    },
    {
        "id": "6991285c-3f4a-434b-999c-a147e212cbfa",
        "title": "Wings of Fire",
        "author": "A. P. J. Abdul Kalam and Arun Tiwari",
        "genre": "Autobiography",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:07:18.455Z"
    },
    {
        "id": "3e042eca-ec31-4227-9b38-90f8f236bd6d",
        "title": "a monke has lived his life99 times",
        "author": "mr. monke99",
        "genre": "climate",
        "yearPublished": 1309,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:49.892Z"
    },
    {
        "id": "b587d111-4854-4e96-beda-b530eb7f3873",
        "title": "a monke has lived his life98 times",
        "author": "mr. monke98",
        "genre": "climate",
        "yearPublished": 1308,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:49.559Z"
    },
    {
        "id": "a21c7d29-8f06-4140-991b-25dfa18a9e7f",
        "title": "a monke has lived his life97 times",
        "author": "mr. monke97",
        "genre": "climate",
        "yearPublished": 1307,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:49.181Z"
    },
    {
        "id": "dd480fca-3b85-4510-bbac-c72c9705846c",
        "title": "a monke has lived his life96 times",
        "author": "mr. monke96",
        "genre": "climate",
        "yearPublished": 1306,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:48.841Z"
    },
    {
        "id": "85151043-b876-4fb8-8eeb-a2de698d7873",
        "title": "a monke has lived his life95 times",
        "author": "mr. monke95",
        "genre": "climate",
        "yearPublished": 1305,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:48.462Z"
    },
    {
        "id": "8c75c3aa-cce5-4437-9a5c-ae173257ed1e",
        "title": "a monke has lived his life94 times",
        "author": "mr. monke94",
        "genre": "climate",
        "yearPublished": 1304,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:48.138Z"
    },
    {
        "id": "29e0f59d-aec3-4695-b1e6-333c3aeaa236",
        "title": "a monke has lived his life93 times",
        "author": "mr. monke93",
        "genre": "climate",
        "yearPublished": 1303,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:47.762Z"
    },
    {
        "id": "f7758133-04ef-4411-8695-0b6b229fb33e",
        "title": "a monke has lived his life92 times",
        "author": "mr. monke92",
        "genre": "climate",
        "yearPublished": 1302,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:47.404Z"
    },
    {
        "id": "1a9148d3-e9b9-4dee-b74b-6e93c0be2430",
        "title": "a monke has lived his life91 times",
        "author": "mr. monke91",
        "genre": "climate",
        "yearPublished": 1301,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:47.048Z"
    },
    {
        "id": "1c954736-70a6-49e6-9f99-8d4432345889",
        "title": "a monke has lived his life90 times",
        "author": "mr. monke90",
        "genre": "climate",
        "yearPublished": 1300,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:46.703Z"
    },
    {
        "id": "3d74f042-c575-48a8-bcb9-86e17b43ac6a",
        "title": "a monke has lived his life89 times",
        "author": "mr. monke89",
        "genre": "climate",
        "yearPublished": 1299,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:46.347Z"
    },
    {
        "id": "183d3829-1785-435c-a6f5-0a0972308a59",
        "title": "a monke has lived his life88 times",
        "author": "mr. monke88",
        "genre": "climate",
        "yearPublished": 1298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:45.987Z"
    },
    {
        "id": "b3af2350-488e-444e-810e-77bf7e935dd8",
        "title": "a monke has lived his life87 times",
        "author": "mr. monke87",
        "genre": "climate",
        "yearPublished": 1297,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:45.627Z"
    },
    {
        "id": "40e37099-1f8f-437a-93e4-1368807f073b",
        "title": "a monke has lived his life86 times",
        "author": "mr. monke86",
        "genre": "climate",
        "yearPublished": 1296,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:45.279Z"
    },
    {
        "id": "8028df1c-ec0d-476f-b214-5fd132777e24",
        "title": "a monke has lived his life85 times",
        "author": "mr. monke85",
        "genre": "climate",
        "yearPublished": 1295,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:43.855Z"
    },
    {
        "id": "82c66a36-1dcb-4403-bbca-8128339a6000",
        "title": "a monke has lived his life84 times",
        "author": "mr. monke84",
        "genre": "climate",
        "yearPublished": 1294,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:43.516Z"
    },
    {
        "id": "6e1fb4ad-f09b-4826-a769-1116063558d7",
        "title": "a monke has lived his life83 times",
        "author": "mr. monke83",
        "genre": "climate",
        "yearPublished": 1293,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:43.192Z"
    },
    {
        "id": "68488df3-45bf-4fc1-90f7-37d37da38dff",
        "title": "a monke has lived his life82 times",
        "author": "mr. monke82",
        "genre": "climate",
        "yearPublished": 1292,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:42.875Z"
    },
    {
        "id": "97b178eb-e0f3-40f3-9bd3-5cd7369a83b5",
        "title": "a monke has lived his life81 times",
        "author": "mr. monke81",
        "genre": "climate",
        "yearPublished": 1291,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:42.554Z"
    },
    {
        "id": "518b2e2c-6dde-49f0-9a6c-104ec335bb5c",
        "title": "a monke has lived his life80 times",
        "author": "mr. monke80",
        "genre": "climate",
        "yearPublished": 1290,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:42.210Z"
    },
    {
        "id": "58bde4d4-306e-4764-870c-3f34f00464f7",
        "title": "a monke has lived his life79 times",
        "author": "mr. monke79",
        "genre": "climate",
        "yearPublished": 1289,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:41.875Z"
    },
    {
        "id": "1767f6da-d553-47bb-ba41-6b2cd36ecdb2",
        "title": "a monke has lived his life78 times",
        "author": "mr. monke78",
        "genre": "climate",
        "yearPublished": 1288,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:41.552Z"
    },
    {
        "id": "ea654334-6aaa-473d-ae73-72eea4a14e9a",
        "title": "a monke has lived his life77 times",
        "author": "mr. monke77",
        "genre": "climate",
        "yearPublished": 1287,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:41.225Z"
    },
    {
        "id": "fd6a4278-f5f4-43de-932a-613bb07775b8",
        "title": "a monke has lived his life76 times",
        "author": "mr. monke76",
        "genre": "climate",
        "yearPublished": 1286,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:40.914Z"
    },
    {
        "id": "222e7e24-a443-40ee-bfb9-d58aba430a0d",
        "title": "a monke has lived his life75 times",
        "author": "mr. monke75",
        "genre": "climate",
        "yearPublished": 1285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:40.587Z"
    },
    {
        "id": "aec81128-673a-46f5-875a-46048d3ad480",
        "title": "a monke has lived his life74 times",
        "author": "mr. monke74",
        "genre": "climate",
        "yearPublished": 1284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:40.253Z"
    },
    {
        "id": "d2fbe7f7-6b17-409a-a125-2cd4e7c3e2d0",
        "title": "a monke has lived his life73 times",
        "author": "mr. monke73",
        "genre": "climate",
        "yearPublished": 1283,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:39.927Z"
    },
    {
        "id": "a4cbe934-aa2e-4801-a606-8e060d10caad",
        "title": "a monke has lived his life72 times",
        "author": "mr. monke72",
        "genre": "climate",
        "yearPublished": 1282,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:39.611Z"
    },
    {
        "id": "e8aa9cf3-97fe-476f-900e-ec44efc95d25",
        "title": "a monke has lived his life71 times",
        "author": "mr. monke71",
        "genre": "climate",
        "yearPublished": 1281,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:38.739Z"
    },
    {
        "id": "2667456d-d281-4b05-a45b-d5d610aedf6d",
        "title": "a monke has lived his life70 times",
        "author": "mr. monke70",
        "genre": "climate",
        "yearPublished": 1280,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:38.443Z"
    },
    {
        "id": "ce1eab83-6e4c-47da-9bc4-9edd5a72cd06",
        "title": "a monke has lived his life69 times",
        "author": "mr. monke69",
        "genre": "climate",
        "yearPublished": 1279,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:38.142Z"
    },
    {
        "id": "7286f3e2-411a-42a3-9527-e153429af485",
        "title": "a monke has lived his life68 times",
        "author": "mr. monke68",
        "genre": "climate",
        "yearPublished": 1278,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:37.850Z"
    },
    {
        "id": "73b1326a-1f5b-4c33-a9d1-84e78a79e386",
        "title": "a monke has lived his life67 times",
        "author": "mr. monke67",
        "genre": "climate",
        "yearPublished": 1277,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:37.543Z"
    },
    {
        "id": "ef047967-32c1-4ac4-aa31-1f980e4c1bea",
        "title": "a monke has lived his life66 times",
        "author": "mr. monke66",
        "genre": "climate",
        "yearPublished": 1276,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:37.245Z"
    },
    {
        "id": "22361d02-a658-43d9-a384-e429b009a34a",
        "title": "a monke has lived his life65 times",
        "author": "mr. monke65",
        "genre": "climate",
        "yearPublished": 1275,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:36.948Z"
    },
    {
        "id": "fbdf2252-38b3-4302-b282-42d4b444cee3",
        "title": "a monke has lived his life64 times",
        "author": "mr. monke64",
        "genre": "climate",
        "yearPublished": 1274,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:36.654Z"
    },
    {
        "id": "45a19753-3688-4982-9ead-945924d2a147",
        "title": "a monke has lived his life63 times",
        "author": "mr. monke63",
        "genre": "climate",
        "yearPublished": 1273,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:36.331Z"
    },
    {
        "id": "388afda6-83d9-41c4-be04-5abad1b534a2",
        "title": "a monke has lived his life62 times",
        "author": "mr. monke62",
        "genre": "climate",
        "yearPublished": 1272,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:36.024Z"
    },
    {
        "id": "cd7431d5-3af5-49f3-b8a3-53d67dea4d0c",
        "title": "a monke has lived his life61 times",
        "author": "mr. monke61",
        "genre": "climate",
        "yearPublished": 1271,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:35.196Z"
    },
    {
        "id": "cad5faf1-eeff-4d34-9b00-ff08ded23f08",
        "title": "a monke has lived his life60 times",
        "author": "mr. monke60",
        "genre": "climate",
        "yearPublished": 1270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:34.917Z"
    },
    {
        "id": "635a5f98-38ea-4c90-b9a6-d75b7d3b5ef8",
        "title": "a monke has lived his life59 times",
        "author": "mr. monke59",
        "genre": "climate",
        "yearPublished": 1269,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:34.584Z"
    },
    {
        "id": "79506470-a1c6-489f-ac73-4ad21f365a97",
        "title": "a monke has lived his life58 times",
        "author": "mr. monke58",
        "genre": "climate",
        "yearPublished": 1268,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:33.733Z"
    },
    {
        "id": "c1b77e3e-6914-4eae-8899-b5bd4e2d4a3d",
        "title": "a monke has lived his life57 times",
        "author": "mr. monke57",
        "genre": "climate",
        "yearPublished": 1267,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:33.422Z"
    },
    {
        "id": "02b47b09-adac-430a-9909-61439ce7f057",
        "title": "a monke has lived his life56 times",
        "author": "mr. monke56",
        "genre": "climate",
        "yearPublished": 1266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:33.122Z"
    },
    {
        "id": "07336f1f-f6fe-4254-88e6-db37fe3c71a3",
        "title": "a monke has lived his life55 times",
        "author": "mr. monke55",
        "genre": "climate",
        "yearPublished": 1265,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:32.824Z"
    },
    {
        "id": "3259c0de-3492-46c1-978e-60b7c8bc8ce3",
        "title": "a monke has lived his life54 times",
        "author": "mr. monke54",
        "genre": "climate",
        "yearPublished": 1264,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:32.523Z"
    },
    {
        "id": "b0f054cb-c9d8-4dcc-be95-51c1c97bdfe9",
        "title": "a monke has lived his life53 times",
        "author": "mr. monke53",
        "genre": "climate",
        "yearPublished": 1263,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:32.197Z"
    },
    {
        "id": "3ce80d85-4671-4965-8687-674830e429c7",
        "title": "a monke has lived his life52 times",
        "author": "mr. monke52",
        "genre": "climate",
        "yearPublished": 1262,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:31.341Z"
    },
    {
        "id": "0011f313-6d10-4f84-92a0-6a527e2312fc",
        "title": "a monke has lived his life51 times",
        "author": "mr. monke51",
        "genre": "climate",
        "yearPublished": 1261,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:31.038Z"
    },
    {
        "id": "599f392e-e27e-4eef-8b84-e9fc43274c06",
        "title": "a monke has lived his life50 times",
        "author": "mr. monke50",
        "genre": "climate",
        "yearPublished": 1260,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:30.753Z"
    },
    {
        "id": "a65e9e02-53a5-4156-8c35-a87c528ca249",
        "title": "a monke has lived his life49 times",
        "author": "mr. monke49",
        "genre": "climate",
        "yearPublished": 1259,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:30.444Z"
    },
    {
        "id": "0c3ad98d-a4a8-401f-ae16-1a848ae6e9fe",
        "title": "a monke has lived his life48 times",
        "author": "mr. monke48",
        "genre": "climate",
        "yearPublished": 1258,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:30.158Z"
    },
    {
        "id": "42e3e8e4-5654-4c25-bb69-1795c061f654",
        "title": "a monke has lived his life47 times",
        "author": "mr. monke47",
        "genre": "climate",
        "yearPublished": 1257,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:29.851Z"
    },
    {
        "id": "ff2b60c4-6576-408f-a344-09b35b5710e6",
        "title": "a monke has lived his life46 times",
        "author": "mr. monke46",
        "genre": "climate",
        "yearPublished": 1256,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:29.570Z"
    },
    {
        "id": "8b3737fe-bccc-44f2-945c-561b9a40ca92",
        "title": "a monke has lived his life45 times",
        "author": "mr. monke45",
        "genre": "climate",
        "yearPublished": 1255,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:29.253Z"
    },
    {
        "id": "09ca0f46-6305-43d8-a973-ff24035b397f",
        "title": "a monke has lived his life44 times",
        "author": "mr. monke44",
        "genre": "climate",
        "yearPublished": 1254,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:28.946Z"
    },
    {
        "id": "b574c6b0-d704-4e95-acd8-d200caeffc77",
        "title": "a monke has lived his life43 times",
        "author": "mr. monke43",
        "genre": "climate",
        "yearPublished": 1253,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:28.090Z"
    },
    {
        "id": "190ed95c-ce5e-4c3f-bda9-be254c3ba17d",
        "title": "a monke has lived his life42 times",
        "author": "mr. monke42",
        "genre": "climate",
        "yearPublished": 1252,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:27.802Z"
    },
    {
        "id": "4c47d824-018d-4178-9028-35c6233d3fee",
        "title": "a monke has lived his life41 times",
        "author": "mr. monke41",
        "genre": "climate",
        "yearPublished": 1251,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:27.507Z"
    },
    {
        "id": "ef875733-5015-4822-ab1b-bb3b5ecbe57e",
        "title": "a monke has lived his life40 times",
        "author": "mr. monke40",
        "genre": "climate",
        "yearPublished": 1250,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:27.224Z"
    },
    {
        "id": "81ff96d4-377d-4a27-8c74-36a1eb7f5bc8",
        "title": "a monke has lived his life39 times",
        "author": "mr. monke39",
        "genre": "climate",
        "yearPublished": 1249,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:26.923Z"
    },
    {
        "id": "38efae4a-7318-4e67-8d49-3ff1ef2eef32",
        "title": "a monke has lived his life38 times",
        "author": "mr. monke38",
        "genre": "climate",
        "yearPublished": 1248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:26.640Z"
    },
    {
        "id": "e66295e7-eebc-4c6d-a9ee-63b45cc95772",
        "title": "a monke has lived his life37 times",
        "author": "mr. monke37",
        "genre": "climate",
        "yearPublished": 1247,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:26.344Z"
    },
    {
        "id": "2b11ff77-a3ca-4cee-b835-741c285e3958",
        "title": "a monke has lived his life36 times",
        "author": "mr. monke36",
        "genre": "climate",
        "yearPublished": 1246,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:26.037Z"
    },
    {
        "id": "bdeb3256-ba17-469d-b9db-42f896abd02a",
        "title": "a monke has lived his life35 times",
        "author": "mr. monke35",
        "genre": "climate",
        "yearPublished": 1245,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:25.738Z"
    },
    {
        "id": "b8de5a0e-6e83-4267-8798-70b34d09224f",
        "title": "a monke has lived his life34 times",
        "author": "mr. monke34",
        "genre": "climate",
        "yearPublished": 1244,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:25.436Z"
    },
    {
        "id": "82c20378-1a05-4128-b12d-ff42f3d59494",
        "title": "a monke has lived his life33 times",
        "author": "mr. monke33",
        "genre": "climate",
        "yearPublished": 1243,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:25.138Z"
    },
    {
        "id": "3cb498b1-bbad-415e-b4ef-6f07c765c44a",
        "title": "a monke has lived his life32 times",
        "author": "mr. monke32",
        "genre": "climate",
        "yearPublished": 1242,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:24.852Z"
    },
    {
        "id": "4586db01-48df-4dbe-b356-0ecf4f0abf78",
        "title": "a monke has lived his life31 times",
        "author": "mr. monke31",
        "genre": "climate",
        "yearPublished": 1241,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:24.546Z"
    },
    {
        "id": "a3ce1be8-16e1-40ff-a4e8-3ff2384f13a1",
        "title": "a monke has lived his life30 times",
        "author": "mr. monke30",
        "genre": "climate",
        "yearPublished": 1240,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:24.251Z"
    },
    {
        "id": "b32ce0cf-67ae-41c4-b219-595a53154e4d",
        "title": "a monke has lived his life29 times",
        "author": "mr. monke29",
        "genre": "climate",
        "yearPublished": 1239,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:23.950Z"
    },
    {
        "id": "7f94e73c-2ce1-4845-b5e5-ae5e9fd0e9b4",
        "title": "a monke has lived his life28 times",
        "author": "mr. monke28",
        "genre": "climate",
        "yearPublished": 1238,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:23.665Z"
    },
    {
        "id": "826fc9df-c1bc-4864-a6fe-6b8f461da6a8",
        "title": "a monke has lived his life27 times",
        "author": "mr. monke27",
        "genre": "climate",
        "yearPublished": 1237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:23.362Z"
    },
    {
        "id": "5d941fd0-e0ec-4a13-b490-4bd53ff0a40c",
        "title": "a monke has lived his life26 times",
        "author": "mr. monke26",
        "genre": "climate",
        "yearPublished": 1236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:23.076Z"
    },
    {
        "id": "59134d67-26a4-434e-baa9-42b0bc955e23",
        "title": "a monke has lived his life25 times",
        "author": "mr. monke25",
        "genre": "climate",
        "yearPublished": 1235,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:22.763Z"
    },
    {
        "id": "57b8b24e-f1b9-49f3-a1b9-10de1a24100c",
        "title": "a monke has lived his life24 times",
        "author": "mr. monke24",
        "genre": "climate",
        "yearPublished": 1234,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:22.478Z"
    },
    {
        "id": "62e97358-076e-4c2c-98d7-0e5b2799b3da",
        "title": "a monke has lived his life23 times",
        "author": "mr. monke23",
        "genre": "climate",
        "yearPublished": 1233,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:22.182Z"
    },
    {
        "id": "37c00796-87c5-4b9a-bf5b-fe0a01b616be",
        "title": "a monke has lived his life22 times",
        "author": "mr. monke22",
        "genre": "climate",
        "yearPublished": 1232,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:21.898Z"
    },
    {
        "id": "c78fca48-1e83-4e41-a271-064f4134966d",
        "title": "a monke has lived his life21 times",
        "author": "mr. monke21",
        "genre": "climate",
        "yearPublished": 1231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:21.569Z"
    },
    {
        "id": "4e25c33b-d9eb-4361-8466-81c28c86da83",
        "title": "a monke has lived his life20 times",
        "author": "mr. monke20",
        "genre": "climate",
        "yearPublished": 1230,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:21.245Z"
    },
    {
        "id": "16b8c458-17f9-4bb8-a1d8-c15d5bf0d4e6",
        "title": "a monke has lived his life19 times",
        "author": "mr. monke19",
        "genre": "climate",
        "yearPublished": 1229,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:20.948Z"
    },
    {
        "id": "367a576c-4608-49e4-9bf9-9a9cbf63a66e",
        "title": "a monke has lived his life18 times",
        "author": "mr. monke18",
        "genre": "climate",
        "yearPublished": 1228,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:20.658Z"
    },
    {
        "id": "211f2b94-aac6-4f55-82bd-3a3046c50a58",
        "title": "a monke has lived his life17 times",
        "author": "mr. monke17",
        "genre": "climate",
        "yearPublished": 1227,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:20.363Z"
    },
    {
        "id": "54c67011-d147-4057-b93c-36418a06f622",
        "title": "a monke has lived his life16 times",
        "author": "mr. monke16",
        "genre": "climate",
        "yearPublished": 1226,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:20.077Z"
    },
    {
        "id": "a0e77dd3-03d8-4a54-98c9-a916b7454eae",
        "title": "a monke has lived his life15 times",
        "author": "mr. monke15",
        "genre": "climate",
        "yearPublished": 1225,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:19.781Z"
    },
    {
        "id": "dd98dbcc-5a2c-4e5b-8c14-305948862217",
        "title": "a monke has lived his life14 times",
        "author": "mr. monke14",
        "genre": "climate",
        "yearPublished": 1224,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:19.490Z"
    },
    {
        "id": "dd471ede-5270-4aa5-91ff-f80dd56819ef",
        "title": "a monke has lived his life13 times",
        "author": "mr. monke13",
        "genre": "climate",
        "yearPublished": 1223,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:19.190Z"
    },
    {
        "id": "331114d2-9689-45bc-b8b6-f8a57aa4372c",
        "title": "a monke has lived his life12 times",
        "author": "mr. monke12",
        "genre": "climate",
        "yearPublished": 1222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:18.900Z"
    },
    {
        "id": "b93abbef-f35e-4b8b-bd0d-f2162119f3f9",
        "title": "a monke has lived his life11 times",
        "author": "mr. monke11",
        "genre": "climate",
        "yearPublished": 1221,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:18.577Z"
    },
    {
        "id": "c607c4b0-9be9-44b9-9f6e-58f6fbaf125c",
        "title": "a monke has lived his life10 times",
        "author": "mr. monke10",
        "genre": "climate",
        "yearPublished": 1220,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:18.270Z"
    },
    {
        "id": "62a51b84-4b19-4f76-93a2-c689b8636e83",
        "title": "a monke has lived his life9 times",
        "author": "mr. monke9",
        "genre": "climate",
        "yearPublished": 1219,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:17.954Z"
    },
    {
        "id": "614a4858-3993-4790-b865-c5b6a419433e",
        "title": "a monke has lived his life8 times",
        "author": "mr. monke8",
        "genre": "climate",
        "yearPublished": 1218,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:17.666Z"
    },
    {
        "id": "d2d89f6a-3c34-4350-aecd-7100a270e61c",
        "title": "a monke has lived his life7 times",
        "author": "mr. monke7",
        "genre": "climate",
        "yearPublished": 1217,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:17.361Z"
    },
    {
        "id": "fe6b6499-05e2-47ce-b231-050f11ea04d0",
        "title": "a monke has lived his life6 times",
        "author": "mr. monke6",
        "genre": "climate",
        "yearPublished": 1216,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:17.071Z"
    },
    {
        "id": "bb0361eb-49d6-4fe7-b7f7-5e52fd64f879",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:16.773Z"
    },
    {
        "id": "e08128c2-d6b8-4987-ac9b-a2b454fc7a0e",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:16.487Z"
    },
    {
        "id": "e49e0a35-a625-498f-a7a7-06a843108b29",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:16.154Z"
    },
    {
        "id": "0cd5803c-909a-42a6-a9d9-05e437aac49b",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:15.871Z"
    },
    {
        "id": "794ea727-9db7-41df-87d7-b86e66d0377a",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:15.570Z"
    },
    {
        "id": "1716cafc-0263-44cf-ab38-39babf816f8e",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:14.739Z"
    },
    {
        "id": "848d2e13-e192-4b34-9b51-6c352950149b",
        "title": "Fue un privilegio estar aqui",
        "author": "Melva Frias Vda. Carrillo",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:12.390Z"
    },
    {
        "id": "fc4844bb-d50f-4ead-8819-55177eb9cc26",
        "title": "Las sagas de Potter",
        "author": "Josepi LucasMoi",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:06:11.308Z"
    },
    {
        "id": "f1c620cb-b945-4c9c-a79f-74d437461628",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:04:46.432Z"
    },
    {
        "id": "5d8a7a9c-311a-4d47-ab0f-a8dfb0be51b7",
        "title": "Robust asymmetric system engine",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:04:03.339Z"
    },
    {
        "id": "f2c087d4-4e23-4cef-a42e-641fc3e395e7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:54.901Z"
    },
    {
        "id": "cf884e98-66ce-4bb6-9bbb-eb8fe218025a",
        "title": "a monke has lived his life99 times",
        "author": "mr. monke99",
        "genre": "climate",
        "yearPublished": 1309,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:09.115Z"
    },
    {
        "id": "0a39274d-672e-4119-a0af-c2448b0c65db",
        "title": "a monke has lived his life98 times",
        "author": "mr. monke98",
        "genre": "climate",
        "yearPublished": 1308,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:08.821Z"
    },
    {
        "id": "11953d13-0c2a-49d9-93e5-89ea06cb5fb3",
        "title": "a monke has lived his life97 times",
        "author": "mr. monke97",
        "genre": "climate",
        "yearPublished": 1307,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:07.971Z"
    },
    {
        "id": "172199b8-6343-4ad2-8f85-e3ede5ad982e",
        "title": "a monke has lived his life96 times",
        "author": "mr. monke96",
        "genre": "climate",
        "yearPublished": 1306,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:07.669Z"
    },
    {
        "id": "a6e2cbd9-179e-4576-8470-f56a0eee9195",
        "title": "a monke has lived his life95 times",
        "author": "mr. monke95",
        "genre": "climate",
        "yearPublished": 1305,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:07.363Z"
    },
    {
        "id": "a0216484-8016-4860-ac38-510baef2bfd0",
        "title": "a monke has lived his life94 times",
        "author": "mr. monke94",
        "genre": "climate",
        "yearPublished": 1304,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:07.072Z"
    },
    {
        "id": "2244df2b-45a2-42f4-a065-0eb4acfa055f",
        "title": "a monke has lived his life93 times",
        "author": "mr. monke93",
        "genre": "climate",
        "yearPublished": 1303,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:06.770Z"
    },
    {
        "id": "b41cf1ad-d2f5-4901-ac62-6f6d6989b618",
        "title": "a monke has lived his life92 times",
        "author": "mr. monke92",
        "genre": "climate",
        "yearPublished": 1302,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:06.379Z"
    },
    {
        "id": "a8aabcfd-1afd-4cc0-978a-8b8d65c64d04",
        "title": "a monke has lived his life91 times",
        "author": "mr. monke91",
        "genre": "climate",
        "yearPublished": 1301,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:06.077Z"
    },
    {
        "id": "d77a1551-7fd8-480c-a4d5-d8469a9ff34a",
        "title": "a monke has lived his life90 times",
        "author": "mr. monke90",
        "genre": "climate",
        "yearPublished": 1300,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:05.780Z"
    },
    {
        "id": "c0f9997d-aa69-4e1b-9cb5-53eb084b9bba",
        "title": "a monke has lived his life89 times",
        "author": "mr. monke89",
        "genre": "climate",
        "yearPublished": 1299,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:05.462Z"
    },
    {
        "id": "d18e9ed2-871e-483f-8e1f-b34ff7e04e7e",
        "title": "a monke has lived his life88 times",
        "author": "mr. monke88",
        "genre": "climate",
        "yearPublished": 1298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:05.166Z"
    },
    {
        "id": "a79bccdb-189e-4ec5-90e1-966e2656ad87",
        "title": "a monke has lived his life87 times",
        "author": "mr. monke87",
        "genre": "climate",
        "yearPublished": 1297,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:04.861Z"
    },
    {
        "id": "536f8df5-f635-402c-b9c5-952b0bd0fc2a",
        "title": "a monke has lived his life86 times",
        "author": "mr. monke86",
        "genre": "climate",
        "yearPublished": 1296,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:04.544Z"
    },
    {
        "id": "d07a72cc-782c-4626-b2c7-41bda0a71f90",
        "title": "a monke has lived his life85 times",
        "author": "mr. monke85",
        "genre": "climate",
        "yearPublished": 1295,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:04.224Z"
    },
    {
        "id": "b888035e-1fb8-4917-9d3e-6edc348e27f2",
        "title": "a monke has lived his life84 times",
        "author": "mr. monke84",
        "genre": "climate",
        "yearPublished": 1294,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:03.368Z"
    },
    {
        "id": "370c7d25-d916-4766-bf4c-97f50566053a",
        "title": "a monke has lived his life83 times",
        "author": "mr. monke83",
        "genre": "climate",
        "yearPublished": 1293,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:03.021Z"
    },
    {
        "id": "99f34e70-870e-4e6b-94fe-909ddbe8ffd1",
        "title": "a monke has lived his life82 times",
        "author": "mr. monke82",
        "genre": "climate",
        "yearPublished": 1292,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:02.717Z"
    },
    {
        "id": "b7a1a2d2-b1ee-48a8-a005-cec178b38c26",
        "title": "a monke has lived his life81 times",
        "author": "mr. monke81",
        "genre": "climate",
        "yearPublished": 1291,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:02.400Z"
    },
    {
        "id": "02a7277f-8d6c-4284-bb1f-dc2d7b0907be",
        "title": "a monke has lived his life80 times",
        "author": "mr. monke80",
        "genre": "climate",
        "yearPublished": 1290,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:02.094Z"
    },
    {
        "id": "2d1dcd7f-42a3-4c5b-99f8-88403c9f92e9",
        "title": "a monke has lived his life79 times",
        "author": "mr. monke79",
        "genre": "climate",
        "yearPublished": 1289,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:01.789Z"
    },
    {
        "id": "a40a7abd-89b0-4f49-bd61-b345ddf8f072",
        "title": "a monke has lived his life78 times",
        "author": "mr. monke78",
        "genre": "climate",
        "yearPublished": 1288,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:01.470Z"
    },
    {
        "id": "8afabd1a-e05a-4253-893f-eca152d85e68",
        "title": "a monke has lived his life77 times",
        "author": "mr. monke77",
        "genre": "climate",
        "yearPublished": 1287,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:01.165Z"
    },
    {
        "id": "9fd5d605-4354-4567-a3ae-3d5b9d409770",
        "title": "a monke has lived his life76 times",
        "author": "mr. monke76",
        "genre": "climate",
        "yearPublished": 1286,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:03:00.854Z"
    },
    {
        "id": "31339ea3-1735-45ae-8524-a056605bca87",
        "title": "a monke has lived his life75 times",
        "author": "mr. monke75",
        "genre": "climate",
        "yearPublished": 1285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:59.983Z"
    },
    {
        "id": "57f70db1-24bb-4cfa-881d-92522272c69e",
        "title": "a monke has lived his life74 times",
        "author": "mr. monke74",
        "genre": "climate",
        "yearPublished": 1284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:59.681Z"
    },
    {
        "id": "1d05c5e9-602b-4aec-be86-2379080ead76",
        "title": "a monke has lived his life73 times",
        "author": "mr. monke73",
        "genre": "climate",
        "yearPublished": 1283,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:59.375Z"
    },
    {
        "id": "d3daeaa5-f3be-4e87-a2d0-428f4fb96f03",
        "title": "a monke has lived his life72 times",
        "author": "mr. monke72",
        "genre": "climate",
        "yearPublished": 1282,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:58.520Z"
    },
    {
        "id": "67c3203e-8e77-4dee-ad0e-d6d051f5ec58",
        "title": "a monke has lived his life71 times",
        "author": "mr. monke71",
        "genre": "climate",
        "yearPublished": 1281,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:58.212Z"
    },
    {
        "id": "49f35911-e5f5-40da-bba1-6f03acbe48e8",
        "title": "a monke has lived his life70 times",
        "author": "mr. monke70",
        "genre": "climate",
        "yearPublished": 1280,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:57.354Z"
    },
    {
        "id": "5fe4a607-4708-42f5-ad0e-dd49f8cc1b1d",
        "title": "a monke has lived his life69 times",
        "author": "mr. monke69",
        "genre": "climate",
        "yearPublished": 1279,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:56.987Z"
    },
    {
        "id": "3ca5e106-6c55-45cc-a98e-f81fc27e45a2",
        "title": "a monke has lived his life68 times",
        "author": "mr. monke68",
        "genre": "climate",
        "yearPublished": 1278,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:56.690Z"
    },
    {
        "id": "8904e2cc-819e-4c7c-8014-759de30ca7d0",
        "title": "a monke has lived his life67 times",
        "author": "mr. monke67",
        "genre": "climate",
        "yearPublished": 1277,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:56.388Z"
    },
    {
        "id": "c360a336-6268-46f1-b547-c7c6895191cd",
        "title": "a monke has lived his life66 times",
        "author": "mr. monke66",
        "genre": "climate",
        "yearPublished": 1276,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:56.090Z"
    },
    {
        "id": "05d516b3-4188-4b04-9a50-05d3f62bdcaf",
        "title": "a monke has lived his life65 times",
        "author": "mr. monke65",
        "genre": "climate",
        "yearPublished": 1275,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:55.789Z"
    },
    {
        "id": "6add9ed3-7737-4df8-bce7-b41885409f0b",
        "title": "a monke has lived his life64 times",
        "author": "mr. monke64",
        "genre": "climate",
        "yearPublished": 1274,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:55.491Z"
    },
    {
        "id": "bad0b692-6d06-48a1-ab3d-63c30c0179c6",
        "title": "a monke has lived his life63 times",
        "author": "mr. monke63",
        "genre": "climate",
        "yearPublished": 1273,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:55.180Z"
    },
    {
        "id": "c252e594-f9fe-4d91-912f-58f85846e1f6",
        "title": "a monke has lived his life62 times",
        "author": "mr. monke62",
        "genre": "climate",
        "yearPublished": 1272,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:54.890Z"
    },
    {
        "id": "145810c7-7122-4ed8-b4e7-c4c04eb1a33f",
        "title": "a monke has lived his life61 times",
        "author": "mr. monke61",
        "genre": "climate",
        "yearPublished": 1271,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:54.587Z"
    },
    {
        "id": "e0f62d4f-f7fe-4055-945f-5d636e587f6e",
        "title": "a monke has lived his life60 times",
        "author": "mr. monke60",
        "genre": "climate",
        "yearPublished": 1270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:53.669Z"
    },
    {
        "id": "a9c5e061-1fc6-40b1-9a33-d57fd57981df",
        "title": "a monke has lived his life59 times",
        "author": "mr. monke59",
        "genre": "climate",
        "yearPublished": 1269,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:53.364Z"
    },
    {
        "id": "8ead0fb3-3f62-46f9-a633-1eb4fe6be53f",
        "title": "a monke has lived his life58 times",
        "author": "mr. monke58",
        "genre": "climate",
        "yearPublished": 1268,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:53.067Z"
    },
    {
        "id": "e693fdf9-ab28-47d1-8b48-74c6acc08dac",
        "title": "a monke has lived his life57 times",
        "author": "mr. monke57",
        "genre": "climate",
        "yearPublished": 1267,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:52.765Z"
    },
    {
        "id": "1f3d5d2c-6157-41a0-adbd-a14486e9d235",
        "title": "a monke has lived his life56 times",
        "author": "mr. monke56",
        "genre": "climate",
        "yearPublished": 1266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:52.472Z"
    },
    {
        "id": "daaf9e7b-4f36-4de6-bb29-3015e5207bbb",
        "title": "a monke has lived his life55 times",
        "author": "mr. monke55",
        "genre": "climate",
        "yearPublished": 1265,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:52.017Z"
    },
    {
        "id": "f79579b9-992d-44df-8fb6-6c965efc49c9",
        "title": "a monke has lived his life54 times",
        "author": "mr. monke54",
        "genre": "climate",
        "yearPublished": 1264,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:51.717Z"
    },
    {
        "id": "cad2af72-2dab-442c-8cff-1348a335151d",
        "title": "a monke has lived his life53 times",
        "author": "mr. monke53",
        "genre": "climate",
        "yearPublished": 1263,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:51.395Z"
    },
    {
        "id": "583cb9dc-15a8-4909-ab9a-122bfcca5c4a",
        "title": "a monke has lived his life52 times",
        "author": "mr. monke52",
        "genre": "climate",
        "yearPublished": 1262,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:51.076Z"
    },
    {
        "id": "2f33ee88-be3b-4ef2-b54c-f6eb67185f40",
        "title": "a monke has lived his life51 times",
        "author": "mr. monke51",
        "genre": "climate",
        "yearPublished": 1261,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:50.769Z"
    },
    {
        "id": "f8ee5243-126f-4807-be4a-fddac12767f1",
        "title": "a monke has lived his life50 times",
        "author": "mr. monke50",
        "genre": "climate",
        "yearPublished": 1260,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:50.477Z"
    },
    {
        "id": "9ff3a65e-74cf-44af-86f7-4cc5022a05c0",
        "title": "a monke has lived his life49 times",
        "author": "mr. monke49",
        "genre": "climate",
        "yearPublished": 1259,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:50.166Z"
    },
    {
        "id": "9d9b39c4-9fb2-4307-9573-a1501b321754",
        "title": "a monke has lived his life48 times",
        "author": "mr. monke48",
        "genre": "climate",
        "yearPublished": 1258,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:49.873Z"
    },
    {
        "id": "4477cbd6-ab18-4e38-8b5c-a06f5f436bc5",
        "title": "a monke has lived his life47 times",
        "author": "mr. monke47",
        "genre": "climate",
        "yearPublished": 1257,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:49.558Z"
    },
    {
        "id": "575d70f4-5249-4d9a-8dcc-930dbfeb3c19",
        "title": "a monke has lived his life46 times",
        "author": "mr. monke46",
        "genre": "climate",
        "yearPublished": 1256,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:49.188Z"
    },
    {
        "id": "a8f9a22d-288f-43bd-938c-31f958f00bea",
        "title": "a monke has lived his life45 times",
        "author": "mr. monke45",
        "genre": "climate",
        "yearPublished": 1255,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:48.879Z"
    },
    {
        "id": "ffdf6ddf-d35d-4751-97f0-202d8400803d",
        "title": "a monke has lived his life44 times",
        "author": "mr. monke44",
        "genre": "climate",
        "yearPublished": 1254,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:48.583Z"
    },
    {
        "id": "2a711ebd-d996-4f0b-97b9-7502df27f902",
        "title": "a monke has lived his life43 times",
        "author": "mr. monke43",
        "genre": "climate",
        "yearPublished": 1253,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:48.233Z"
    },
    {
        "id": "ba265cbe-c477-4a10-a635-4ff17751ddea",
        "title": "a monke has lived his life42 times",
        "author": "mr. monke42",
        "genre": "climate",
        "yearPublished": 1252,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:47.931Z"
    },
    {
        "id": "ef81534d-63f1-45b4-a85f-6fff46530e79",
        "title": "a monke has lived his life41 times",
        "author": "mr. monke41",
        "genre": "climate",
        "yearPublished": 1251,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:47.627Z"
    },
    {
        "id": "c7aa5986-4dd7-4ac8-9cee-d651dba33d45",
        "title": "a monke has lived his life40 times",
        "author": "mr. monke40",
        "genre": "climate",
        "yearPublished": 1250,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:47.336Z"
    },
    {
        "id": "a7609e6c-f51d-4a4b-97da-d33ee1eb3d7c",
        "title": "a monke has lived his life39 times",
        "author": "mr. monke39",
        "genre": "climate",
        "yearPublished": 1249,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:47.034Z"
    },
    {
        "id": "1fae7b32-39e9-467a-867b-8e7852009f3a",
        "title": "a monke has lived his life38 times",
        "author": "mr. monke38",
        "genre": "climate",
        "yearPublished": 1248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:46.742Z"
    },
    {
        "id": "ad61df6b-6257-415b-91a0-57bcfe2e4ae6",
        "title": "a monke has lived his life37 times",
        "author": "mr. monke37",
        "genre": "climate",
        "yearPublished": 1247,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:46.436Z"
    },
    {
        "id": "f01bba71-e90f-427a-b585-31458111d997",
        "title": "a monke has lived his life36 times",
        "author": "mr. monke36",
        "genre": "climate",
        "yearPublished": 1246,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:46.119Z"
    },
    {
        "id": "27bd30cf-ab33-4a86-9e60-a85ae0c3ea47",
        "title": "a monke has lived his life35 times",
        "author": "mr. monke35",
        "genre": "climate",
        "yearPublished": 1245,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:45.758Z"
    },
    {
        "id": "b50e3a9e-c0ec-4dc3-8c46-086e3e0270be",
        "title": "a monke has lived his life34 times",
        "author": "mr. monke34",
        "genre": "climate",
        "yearPublished": 1244,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:45.469Z"
    },
    {
        "id": "9c96dde9-a59a-4899-bf7c-11efb238f5ea",
        "title": "a monke has lived his life33 times",
        "author": "mr. monke33",
        "genre": "climate",
        "yearPublished": 1243,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:45.158Z"
    },
    {
        "id": "3355370d-8592-4552-bc8a-1f7701714697",
        "title": "a monke has lived his life32 times",
        "author": "mr. monke32",
        "genre": "climate",
        "yearPublished": 1242,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:44.869Z"
    },
    {
        "id": "962e9e69-026b-45fb-b3c5-1cb8b04a37ec",
        "title": "a monke has lived his life31 times",
        "author": "mr. monke31",
        "genre": "climate",
        "yearPublished": 1241,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:44.567Z"
    },
    {
        "id": "bd763127-9f7e-4b2f-b557-7191dbb76c12",
        "title": "a monke has lived his life30 times",
        "author": "mr. monke30",
        "genre": "climate",
        "yearPublished": 1240,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:44.275Z"
    },
    {
        "id": "05ac5cfb-03c3-4193-9776-b63e36a60de5",
        "title": "a monke has lived his life29 times",
        "author": "mr. monke29",
        "genre": "climate",
        "yearPublished": 1239,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:43.969Z"
    },
    {
        "id": "ec09471d-bf12-4a83-b171-6b94d34e93eb",
        "title": "a monke has lived his life28 times",
        "author": "mr. monke28",
        "genre": "climate",
        "yearPublished": 1238,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:43.668Z"
    },
    {
        "id": "137a6bf2-0992-47c0-af69-bc642dcd1a90",
        "title": "a monke has lived his life27 times",
        "author": "mr. monke27",
        "genre": "climate",
        "yearPublished": 1237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:43.363Z"
    },
    {
        "id": "df2864fb-7508-4569-bdd3-f43d57c73195",
        "title": "a monke has lived his life26 times",
        "author": "mr. monke26",
        "genre": "climate",
        "yearPublished": 1236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:43.060Z"
    },
    {
        "id": "f3a5057c-81b5-400e-9acf-8a9f66c28e9e",
        "title": "a monke has lived his life25 times",
        "author": "mr. monke25",
        "genre": "climate",
        "yearPublished": 1235,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:42.191Z"
    },
    {
        "id": "9ea56124-cd24-44cc-818f-6ec2da9d4a27",
        "title": "a monke has lived his life24 times",
        "author": "mr. monke24",
        "genre": "climate",
        "yearPublished": 1234,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:41.899Z"
    },
    {
        "id": "caff718e-fd94-49b1-99d6-cc1873eb99ad",
        "title": "a monke has lived his life23 times",
        "author": "mr. monke23",
        "genre": "climate",
        "yearPublished": 1233,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:41.029Z"
    },
    {
        "id": "46e1c9d4-0734-4646-bdc7-0a1cb22a8d68",
        "title": "a monke has lived his life22 times",
        "author": "mr. monke22",
        "genre": "climate",
        "yearPublished": 1232,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:40.739Z"
    },
    {
        "id": "09130668-30a7-4af3-b788-b3c64fc8aa5a",
        "title": "a monke has lived his life21 times",
        "author": "mr. monke21",
        "genre": "climate",
        "yearPublished": 1231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:40.438Z"
    },
    {
        "id": "630a0690-5395-454e-9c34-41c7f94ad0ee",
        "title": "a monke has lived his life20 times",
        "author": "mr. monke20",
        "genre": "climate",
        "yearPublished": 1230,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:40.140Z"
    },
    {
        "id": "a20e1154-8688-4e1b-af5e-d3e949e18516",
        "title": "a monke has lived his life19 times",
        "author": "mr. monke19",
        "genre": "climate",
        "yearPublished": 1229,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:39.837Z"
    },
    {
        "id": "b72bc9e2-adba-4bf4-a18b-e9423128e748",
        "title": "a monke has lived his life18 times",
        "author": "mr. monke18",
        "genre": "climate",
        "yearPublished": 1228,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:39.540Z"
    },
    {
        "id": "400c09d3-b4e2-4d51-b170-b2a6db0de219",
        "title": "a monke has lived his life17 times",
        "author": "mr. monke17",
        "genre": "climate",
        "yearPublished": 1227,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:39.228Z"
    },
    {
        "id": "bd2146b9-3334-4222-92b3-b732598f2aca",
        "title": "a monke has lived his life16 times",
        "author": "mr. monke16",
        "genre": "climate",
        "yearPublished": 1226,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:38.910Z"
    },
    {
        "id": "5504c449-17f3-49c5-806c-ab20470d09a4",
        "title": "a monke has lived his life15 times",
        "author": "mr. monke15",
        "genre": "climate",
        "yearPublished": 1225,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:38.605Z"
    },
    {
        "id": "b4207bce-f27f-4367-8e03-b426e9523739",
        "title": "a monke has lived his life14 times",
        "author": "mr. monke14",
        "genre": "climate",
        "yearPublished": 1224,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:38.311Z"
    },
    {
        "id": "3cadf3c5-6b0d-46b1-8a64-939ee92cb6e8",
        "title": "a monke has lived his life13 times",
        "author": "mr. monke13",
        "genre": "climate",
        "yearPublished": 1223,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:38.005Z"
    },
    {
        "id": "73801bea-499c-405b-a681-23482b16cae4",
        "title": "a monke has lived his life12 times",
        "author": "mr. monke12",
        "genre": "climate",
        "yearPublished": 1222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:37.710Z"
    },
    {
        "id": "d2e2330d-5ed1-448c-aa89-975ade6d6a8e",
        "title": "a monke has lived his life11 times",
        "author": "mr. monke11",
        "genre": "climate",
        "yearPublished": 1221,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:36.642Z"
    },
    {
        "id": "bdb69c02-5085-4cef-bb8c-4da00e2de386",
        "title": "a monke has lived his life10 times",
        "author": "mr. monke10",
        "genre": "climate",
        "yearPublished": 1220,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:36.299Z"
    },
    {
        "id": "13ff3c7e-4426-4327-a299-3158ca1732a3",
        "title": "a monke has lived his life9 times",
        "author": "mr. monke9",
        "genre": "climate",
        "yearPublished": 1219,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:35.974Z"
    },
    {
        "id": "215f05a6-2a8b-4e0d-90eb-079f2eb16572",
        "title": "a monke has lived his life8 times",
        "author": "mr. monke8",
        "genre": "climate",
        "yearPublished": 1218,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:35.644Z"
    },
    {
        "id": "0575bf89-dad5-4c09-b36b-c5d0ebdd965a",
        "title": "a monke has lived his life7 times",
        "author": "mr. monke7",
        "genre": "climate",
        "yearPublished": 1217,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:35.339Z"
    },
    {
        "id": "0802fc73-055e-49fc-8cf1-72c2f0067eb9",
        "title": "a monke has lived his life6 times",
        "author": "mr. monke6",
        "genre": "climate",
        "yearPublished": 1216,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:35.018Z"
    },
    {
        "id": "18e1e1df-2ff6-451e-aa74-727259be2c11",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:34.710Z"
    },
    {
        "id": "678721d0-b271-48c9-97af-ee91c1bc71d2",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:34.417Z"
    },
    {
        "id": "ffb7a75f-91d0-4a72-9dd7-e770882fa72b",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:34.100Z"
    },
    {
        "id": "df3ae490-0b94-4a99-b235-1b289ebddc59",
        "title": "The Diary of a Young Girl",
        "author": "Anne Frank",
        "genre": "autobiography",
        "yearPublished": 1947,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:33.829Z"
    },
    {
        "id": "9d9fd560-5b99-41e0-badc-be3eed4760cf",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:33.809Z"
    },
    {
        "id": "08a0a73c-399d-4089-96d1-7080feec69c9",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:32.494Z"
    },
    {
        "id": "ea08ecda-333b-433d-a6e3-fa904d4c8e63",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:30.878Z"
    },
    {
        "id": "ae25b8fe-0254-4730-b608-f419a37ee34e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:27.933Z"
    },
    {
        "id": "5efaa1b1-3f10-47b1-a88c-ea491139ea2e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:08.744Z"
    },
    {
        "id": "3cebec42-e801-4d3d-bc14-45cbe6e64b93",
        "title": "a monke has lived his life99 times",
        "author": "mr. monke99",
        "genre": "climate",
        "yearPublished": 1309,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:02.440Z"
    },
    {
        "id": "b024b443-e78c-4626-a700-a8b55b178548",
        "title": "a monke has lived his life98 times",
        "author": "mr. monke98",
        "genre": "climate",
        "yearPublished": 1308,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:02.095Z"
    },
    {
        "id": "aecf24a4-a4fa-4e55-9598-f393f8ea97f8",
        "title": "a monke has lived his life97 times",
        "author": "mr. monke97",
        "genre": "climate",
        "yearPublished": 1307,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:01.800Z"
    },
    {
        "id": "c76cf8d1-a67d-49cc-bb1c-cca959efa633",
        "title": "a monke has lived his life96 times",
        "author": "mr. monke96",
        "genre": "climate",
        "yearPublished": 1306,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:01.512Z"
    },
    {
        "id": "edff9998-de1c-40b0-9ab8-05274cfe3387",
        "title": "a monke has lived his life95 times",
        "author": "mr. monke95",
        "genre": "climate",
        "yearPublished": 1305,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:01.185Z"
    },
    {
        "id": "73e8fac0-c4ef-43ec-8c89-4208b78c1d6e",
        "title": "a monke has lived his life94 times",
        "author": "mr. monke94",
        "genre": "climate",
        "yearPublished": 1304,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:00.891Z"
    },
    {
        "id": "e82d7901-bba7-42a5-9e74-92e5e7590729",
        "title": "a monke has lived his life93 times",
        "author": "mr. monke93",
        "genre": "climate",
        "yearPublished": 1303,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:00.592Z"
    },
    {
        "id": "72d0d3ab-b978-45c2-9765-e2db0e6457f9",
        "title": "a monke has lived his life92 times",
        "author": "mr. monke92",
        "genre": "climate",
        "yearPublished": 1302,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:00.274Z"
    },
    {
        "id": "608f2bf3-5d02-4fc2-9cf1-164ece76c0ac",
        "title": "messi",
        "author": "Ronaldo",
        "genre": "fiction",
        "yearPublished": 2012,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:02:00.209Z"
    },
    {
        "id": "3185df74-a572-4c86-8b4f-ca588b794c9c",
        "title": "a monke has lived his life91 times",
        "author": "mr. monke91",
        "genre": "climate",
        "yearPublished": 1301,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:59.976Z"
    },
    {
        "id": "7eac6c5b-9eb9-417c-a300-cb30fba0552a",
        "title": "a monke has lived his life90 times",
        "author": "mr. monke90",
        "genre": "climate",
        "yearPublished": 1300,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:59.684Z"
    },
    {
        "id": "6a9c9e26-cd0c-4fe3-831e-a24c058a8696",
        "title": "a monke has lived his life89 times",
        "author": "mr. monke89",
        "genre": "climate",
        "yearPublished": 1299,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:59.335Z"
    },
    {
        "id": "b44e59fa-3505-43e4-ad1c-85f4c9001a96",
        "title": "a monke has lived his life88 times",
        "author": "mr. monke88",
        "genre": "climate",
        "yearPublished": 1298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:59.003Z"
    },
    {
        "id": "abcf03fa-87c3-4bae-8bb6-a06c0cfc61f5",
        "title": "a monke has lived his life87 times",
        "author": "mr. monke87",
        "genre": "climate",
        "yearPublished": 1297,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:58.709Z"
    },
    {
        "id": "566e66de-9d22-430f-895f-fe057d6bafd7",
        "title": "a monke has lived his life86 times",
        "author": "mr. monke86",
        "genre": "climate",
        "yearPublished": 1296,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:58.367Z"
    },
    {
        "id": "0f80aca9-08fa-4365-b86c-d9c31c2a299e",
        "title": "a monke has lived his life85 times",
        "author": "mr. monke85",
        "genre": "climate",
        "yearPublished": 1295,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:58.063Z"
    },
    {
        "id": "9c4cc44f-3262-44f6-86d1-3fab9083b6ed",
        "title": "a monke has lived his life84 times",
        "author": "mr. monke84",
        "genre": "climate",
        "yearPublished": 1294,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:57.772Z"
    },
    {
        "id": "57aa6ab5-f5ea-4863-b3e0-3275552cccd3",
        "title": "a monke has lived his life83 times",
        "author": "mr. monke83",
        "genre": "climate",
        "yearPublished": 1293,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:57.480Z"
    },
    {
        "id": "abe6aca2-7650-4b93-b41f-f28f31e82c11",
        "title": "a monke has lived his life82 times",
        "author": "mr. monke82",
        "genre": "climate",
        "yearPublished": 1292,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:57.188Z"
    },
    {
        "id": "96260bc0-5372-481f-998d-08e3e76df153",
        "title": "a monke has lived his life81 times",
        "author": "mr. monke81",
        "genre": "climate",
        "yearPublished": 1291,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:56.893Z"
    },
    {
        "id": "430df1d4-8338-4738-b679-c28d2a8fa828",
        "title": "a monke has lived his life80 times",
        "author": "mr. monke80",
        "genre": "climate",
        "yearPublished": 1290,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:56.596Z"
    },
    {
        "id": "e1bfdb7c-91c5-4cf8-8dde-7a48d8d25e3d",
        "title": "a monke has lived his life79 times",
        "author": "mr. monke79",
        "genre": "climate",
        "yearPublished": 1289,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:56.301Z"
    },
    {
        "id": "4f4d67e0-c5f8-4607-a0b7-f7ffc7e6fd48",
        "title": "a monke has lived his life78 times",
        "author": "mr. monke78",
        "genre": "climate",
        "yearPublished": 1288,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:56.003Z"
    },
    {
        "id": "c948c25e-ade7-4623-baee-06dfbe8bcf1e",
        "title": "a monke has lived his life77 times",
        "author": "mr. monke77",
        "genre": "climate",
        "yearPublished": 1287,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:55.661Z"
    },
    {
        "id": "7cf52386-e7b3-490b-989e-b4be219017e7",
        "title": "a monke has lived his life76 times",
        "author": "mr. monke76",
        "genre": "climate",
        "yearPublished": 1286,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:55.363Z"
    },
    {
        "id": "f8836c87-8546-4eb0-92e3-756a9d70d7b6",
        "title": "a monke has lived his life75 times",
        "author": "mr. monke75",
        "genre": "climate",
        "yearPublished": 1285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:55.068Z"
    },
    {
        "id": "f2382d2d-4d0d-4f35-b20f-a12730615372",
        "title": "a monke has lived his life74 times",
        "author": "mr. monke74",
        "genre": "climate",
        "yearPublished": 1284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:54.781Z"
    },
    {
        "id": "ee266739-e93e-42fd-a7a8-c1dde9a78645",
        "title": "a monke has lived his life73 times",
        "author": "mr. monke73",
        "genre": "climate",
        "yearPublished": 1283,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:54.485Z"
    },
    {
        "id": "dc449d12-7d54-4d19-8667-2b9b28a590b3",
        "title": "a monke has lived his life72 times",
        "author": "mr. monke72",
        "genre": "climate",
        "yearPublished": 1282,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:54.194Z"
    },
    {
        "id": "d317b6ba-e8ef-4696-8670-1a28dfe5d877",
        "title": "a monke has lived his life71 times",
        "author": "mr. monke71",
        "genre": "climate",
        "yearPublished": 1281,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:53.896Z"
    },
    {
        "id": "fdab349b-66f1-41bf-b95e-5d7865ad24e0",
        "title": "a monke has lived his life70 times",
        "author": "mr. monke70",
        "genre": "climate",
        "yearPublished": 1280,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:53.053Z"
    },
    {
        "id": "5e51d0a4-9ff3-4e65-821a-89038e5754e0",
        "title": "a monke has lived his life69 times",
        "author": "mr. monke69",
        "genre": "climate",
        "yearPublished": 1279,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:52.676Z"
    },
    {
        "id": "a514b250-d71d-425e-b4ee-d19d6d18656d",
        "title": "a monke has lived his life68 times",
        "author": "mr. monke68",
        "genre": "climate",
        "yearPublished": 1278,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:51.832Z"
    },
    {
        "id": "d6b8052a-17ad-49b8-9e50-ccc1d22aa6fa",
        "title": "a monke has lived his life67 times",
        "author": "mr. monke67",
        "genre": "climate",
        "yearPublished": 1277,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:51.539Z"
    },
    {
        "id": "579847f8-5c1d-4925-ba4d-0d1190b0a6fc",
        "title": "a monke has lived his life66 times",
        "author": "mr. monke66",
        "genre": "climate",
        "yearPublished": 1276,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:51.250Z"
    },
    {
        "id": "86f766c7-2f3b-4aae-ac52-686d89db1b28",
        "title": "a monke has lived his life65 times",
        "author": "mr. monke65",
        "genre": "climate",
        "yearPublished": 1275,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:50.939Z"
    },
    {
        "id": "9963b3ea-af9b-4dcf-a75a-e8e6201f9bf8",
        "title": "a monke has lived his life64 times",
        "author": "mr. monke64",
        "genre": "climate",
        "yearPublished": 1274,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:50.646Z"
    },
    {
        "id": "136c35f6-df19-4d8b-aa30-e37b648ffd65",
        "title": "a monke has lived his life63 times",
        "author": "mr. monke63",
        "genre": "climate",
        "yearPublished": 1273,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:50.346Z"
    },
    {
        "id": "c14db848-0a72-4406-a9a4-d4a61aeebbea",
        "title": "a monke has lived his life62 times",
        "author": "mr. monke62",
        "genre": "climate",
        "yearPublished": 1272,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:50.021Z"
    },
    {
        "id": "97c2048d-f6a6-4af1-aacb-866547414655",
        "title": "a monke has lived his life61 times",
        "author": "mr. monke61",
        "genre": "climate",
        "yearPublished": 1271,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:49.725Z"
    },
    {
        "id": "4505f47a-5533-4fdb-96d8-adc6a5299c8a",
        "title": "a monke has lived his life60 times",
        "author": "mr. monke60",
        "genre": "climate",
        "yearPublished": 1270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:49.425Z"
    },
    {
        "id": "b7b5ecaf-073e-4e00-92d7-cf64399116f5",
        "title": "a monke has lived his life59 times",
        "author": "mr. monke59",
        "genre": "climate",
        "yearPublished": 1269,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:49.135Z"
    },
    {
        "id": "7d50385f-7e6e-4b3f-ae67-8b7915348736",
        "title": "a monke has lived his life58 times",
        "author": "mr. monke58",
        "genre": "climate",
        "yearPublished": 1268,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:48.843Z"
    },
    {
        "id": "f8ab2eb1-0c89-46f0-ae99-77847561bfa0",
        "title": "a monke has lived his life57 times",
        "author": "mr. monke57",
        "genre": "climate",
        "yearPublished": 1267,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:48.551Z"
    },
    {
        "id": "4c7e55ef-dce6-4c77-adde-51d8159b24e6",
        "title": "a monke has lived his life56 times",
        "author": "mr. monke56",
        "genre": "climate",
        "yearPublished": 1266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:48.260Z"
    },
    {
        "id": "aac2f1e7-894e-4048-9afd-a75bfd2ec4a3",
        "title": "a monke has lived his life55 times",
        "author": "mr. monke55",
        "genre": "climate",
        "yearPublished": 1265,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:47.967Z"
    },
    {
        "id": "bd90020a-bd0a-49a7-ae3d-1c1dc15ef7f1",
        "title": "a monke has lived his life54 times",
        "author": "mr. monke54",
        "genre": "climate",
        "yearPublished": 1264,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:47.142Z"
    },
    {
        "id": "e6d0831e-a74f-42fb-a9bd-36e898afe12c",
        "title": "a monke has lived his life53 times",
        "author": "mr. monke53",
        "genre": "climate",
        "yearPublished": 1263,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:46.841Z"
    },
    {
        "id": "be7788f1-2f15-415d-bb04-486b8421a8f5",
        "title": "a monke has lived his life52 times",
        "author": "mr. monke52",
        "genre": "climate",
        "yearPublished": 1262,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:46.554Z"
    },
    {
        "id": "fa7479b5-d752-4fff-8cf4-6f9a70e11b7c",
        "title": "a monke has lived his life51 times",
        "author": "mr. monke51",
        "genre": "climate",
        "yearPublished": 1261,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:46.257Z"
    },
    {
        "id": "86f5a71c-8950-4c4f-81d8-04fda188452b",
        "title": "a monke has lived his life50 times",
        "author": "mr. monke50",
        "genre": "climate",
        "yearPublished": 1260,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:45.972Z"
    },
    {
        "id": "d5696d29-76b2-4eef-ae84-e406424295e5",
        "title": "a monke has lived his life49 times",
        "author": "mr. monke49",
        "genre": "climate",
        "yearPublished": 1259,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:45.680Z"
    },
    {
        "id": "b5ba5924-62e9-4b82-bc7e-f1ae5d2e2e5b",
        "title": "a monke has lived his life48 times",
        "author": "mr. monke48",
        "genre": "climate",
        "yearPublished": 1258,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:45.386Z"
    },
    {
        "id": "43f0631c-5223-414f-b7ee-d203ee9868e1",
        "title": "a monke has lived his life47 times",
        "author": "mr. monke47",
        "genre": "climate",
        "yearPublished": 1257,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:45.062Z"
    },
    {
        "id": "d3920e9a-298f-4b2e-b335-1dab0364ae5e",
        "title": "a monke has lived his life46 times",
        "author": "mr. monke46",
        "genre": "climate",
        "yearPublished": 1256,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:44.771Z"
    },
    {
        "id": "14a92653-a13b-48bf-9ccf-5a9058018c46",
        "title": "a monke has lived his life45 times",
        "author": "mr. monke45",
        "genre": "climate",
        "yearPublished": 1255,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:44.342Z"
    },
    {
        "id": "fd153c22-7fcc-45e3-8ac5-65e64d1228c8",
        "title": "a monke has lived his life44 times",
        "author": "mr. monke44",
        "genre": "climate",
        "yearPublished": 1254,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:44.000Z"
    },
    {
        "id": "197edd16-2865-4f74-8ed6-fa9e8beea076",
        "title": "a monke has lived his life43 times",
        "author": "mr. monke43",
        "genre": "climate",
        "yearPublished": 1253,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:43.705Z"
    },
    {
        "id": "b2e66f0a-b234-450b-b1dd-88f69f99fc77",
        "title": "a monke has lived his life42 times",
        "author": "mr. monke42",
        "genre": "climate",
        "yearPublished": 1252,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:43.386Z"
    },
    {
        "id": "8848cf50-928a-42b5-a7ed-5f5e0e9601ef",
        "title": "a monke has lived his life41 times",
        "author": "mr. monke41",
        "genre": "climate",
        "yearPublished": 1251,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:42.995Z"
    },
    {
        "id": "828fdd24-dfd2-4438-8457-b07056f240cc",
        "title": "a monke has lived his life40 times",
        "author": "mr. monke40",
        "genre": "climate",
        "yearPublished": 1250,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:42.075Z"
    },
    {
        "id": "f4242c5f-2c6c-4a7a-a1fd-a76581df61e7",
        "title": "a monke has lived his life39 times",
        "author": "mr. monke39",
        "genre": "climate",
        "yearPublished": 1249,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:41.745Z"
    },
    {
        "id": "d86c23de-be7c-4862-9f66-2b97e68980f6",
        "title": "a monke has lived his life38 times",
        "author": "mr. monke38",
        "genre": "climate",
        "yearPublished": 1248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:41.446Z"
    },
    {
        "id": "a18a10b4-9238-4495-ba3e-dbea2afc18d0",
        "title": "a monke has lived his life37 times",
        "author": "mr. monke37",
        "genre": "climate",
        "yearPublished": 1247,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:41.144Z"
    },
    {
        "id": "16106f93-4ca2-44c6-bcea-e18cc31750fa",
        "title": "a monke has lived his life36 times",
        "author": "mr. monke36",
        "genre": "climate",
        "yearPublished": 1246,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:40.850Z"
    },
    {
        "id": "68b69f83-731b-4e1f-a3a9-67bff92e93f1",
        "title": "a monke has lived his life35 times",
        "author": "mr. monke35",
        "genre": "climate",
        "yearPublished": 1245,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:40.553Z"
    },
    {
        "id": "a4a1fb9f-6ee1-4bd7-a03b-69258ea2a5bd",
        "title": "a monke has lived his life34 times",
        "author": "mr. monke34",
        "genre": "climate",
        "yearPublished": 1244,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:40.268Z"
    },
    {
        "id": "d98bf279-8518-42f1-a1bc-67e0d2bde8a5",
        "title": "a monke has lived his life33 times",
        "author": "mr. monke33",
        "genre": "climate",
        "yearPublished": 1243,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:39.458Z"
    },
    {
        "id": "58a2527e-284b-4753-a417-5a06f830fa75",
        "title": "a monke has lived his life32 times",
        "author": "mr. monke32",
        "genre": "climate",
        "yearPublished": 1242,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:39.146Z"
    },
    {
        "id": "3d4c1cd6-2f4e-4b19-97f1-cdeff11dcca9",
        "title": "a monke has lived his life31 times",
        "author": "mr. monke31",
        "genre": "climate",
        "yearPublished": 1241,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:38.858Z"
    },
    {
        "id": "757f60b7-e6f0-4683-a9d1-abeb369eee2d",
        "title": "a monke has lived his life30 times",
        "author": "mr. monke30",
        "genre": "climate",
        "yearPublished": 1240,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:38.559Z"
    },
    {
        "id": "d23b630f-b8d4-4194-9cb7-f1a8266619f8",
        "title": "a monke has lived his life29 times",
        "author": "mr. monke29",
        "genre": "climate",
        "yearPublished": 1239,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:38.268Z"
    },
    {
        "id": "8a77702b-f7a8-4297-a4c4-8934690a1fba",
        "title": "a monke has lived his life28 times",
        "author": "mr. monke28",
        "genre": "climate",
        "yearPublished": 1238,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:37.978Z"
    },
    {
        "id": "aa31afb1-5cd7-48ee-8d41-ef69f5fd94d5",
        "title": "a monke has lived his life27 times",
        "author": "mr. monke27",
        "genre": "climate",
        "yearPublished": 1237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:37.687Z"
    },
    {
        "id": "2e6cc20e-14f4-4a68-8682-0154d414fcf0",
        "title": "a monke has lived his life26 times",
        "author": "mr. monke26",
        "genre": "climate",
        "yearPublished": 1236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:37.403Z"
    },
    {
        "id": "398642e7-79d7-4ecf-9320-e382c5087c9b",
        "title": "a monke has lived his life25 times",
        "author": "mr. monke25",
        "genre": "climate",
        "yearPublished": 1235,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:37.111Z"
    },
    {
        "id": "6f7e162f-e77f-4d5f-992d-63d2f1e0b912",
        "title": "a monke has lived his life24 times",
        "author": "mr. monke24",
        "genre": "climate",
        "yearPublished": 1234,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:36.813Z"
    },
    {
        "id": "3b8842be-aaf1-496c-b77d-a6d987157fb0",
        "title": "a monke has lived his life23 times",
        "author": "mr. monke23",
        "genre": "climate",
        "yearPublished": 1233,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:36.509Z"
    },
    {
        "id": "f07acbab-bb29-4fbc-b67d-8dee486d002c",
        "title": "a monke has lived his life22 times",
        "author": "mr. monke22",
        "genre": "climate",
        "yearPublished": 1232,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:36.218Z"
    },
    {
        "id": "2f19c3ad-6ced-4031-8892-d441abca0c5d",
        "title": "a monke has lived his life21 times",
        "author": "mr. monke21",
        "genre": "climate",
        "yearPublished": 1231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:35.927Z"
    },
    {
        "id": "44351ab2-716d-4e02-ad5c-fe1fd77cab39",
        "title": "a monke has lived his life20 times",
        "author": "mr. monke20",
        "genre": "climate",
        "yearPublished": 1230,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:35.632Z"
    },
    {
        "id": "9bd06d3f-1777-4d28-8e4b-8cf87ce0424f",
        "title": "a monke has lived his life19 times",
        "author": "mr. monke19",
        "genre": "climate",
        "yearPublished": 1229,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:35.338Z"
    },
    {
        "id": "aceb613f-7ca3-47d0-919c-53f232e9c39e",
        "title": "a monke has lived his life18 times",
        "author": "mr. monke18",
        "genre": "climate",
        "yearPublished": 1228,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:35.027Z"
    },
    {
        "id": "846e13fe-f9be-4b87-b9ff-2b37488e9689",
        "title": "a monke has lived his life17 times",
        "author": "mr. monke17",
        "genre": "climate",
        "yearPublished": 1227,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:34.737Z"
    },
    {
        "id": "b940959f-6324-4a79-8435-26658dbcfdd3",
        "title": "a monke has lived his life16 times",
        "author": "mr. monke16",
        "genre": "climate",
        "yearPublished": 1226,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:34.451Z"
    },
    {
        "id": "9a3f2e91-b262-43bf-bfe2-294a83fd313e",
        "title": "a monke has lived his life15 times",
        "author": "mr. monke15",
        "genre": "climate",
        "yearPublished": 1225,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:34.150Z"
    },
    {
        "id": "5b45e498-b167-4562-8b21-c42605c81d42",
        "title": "a monke has lived his life14 times",
        "author": "mr. monke14",
        "genre": "climate",
        "yearPublished": 1224,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:33.860Z"
    },
    {
        "id": "b7dd604f-95d3-487e-883a-98926c7962c7",
        "title": "a monke has lived his life13 times",
        "author": "mr. monke13",
        "genre": "climate",
        "yearPublished": 1223,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:33.568Z"
    },
    {
        "id": "90f13e8f-65e2-4733-9ccf-b1f05bb6e0e8",
        "title": "a monke has lived his life12 times",
        "author": "mr. monke12",
        "genre": "climate",
        "yearPublished": 1222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:33.279Z"
    },
    {
        "id": "fb6b5570-980b-4db3-8253-61419cbf9f3e",
        "title": "a monke has lived his life11 times",
        "author": "mr. monke11",
        "genre": "climate",
        "yearPublished": 1221,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:32.899Z"
    },
    {
        "id": "9f453842-3014-4114-9a96-086c4d81ca3f",
        "title": "a monke has lived his life10 times",
        "author": "mr. monke10",
        "genre": "climate",
        "yearPublished": 1220,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:32.612Z"
    },
    {
        "id": "9ffc8f5a-16d0-44b4-9033-a5bea53a8919",
        "title": "a monke has lived his life9 times",
        "author": "mr. monke9",
        "genre": "climate",
        "yearPublished": 1219,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:32.320Z"
    },
    {
        "id": "f53b750a-fdd5-4fcd-a5bb-bd4606546bc4",
        "title": "a monke has lived his life8 times",
        "author": "mr. monke8",
        "genre": "climate",
        "yearPublished": 1218,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:32.029Z"
    },
    {
        "id": "8f20ea82-236e-405d-ab1e-7124d7311109",
        "title": "a monke has lived his life7 times",
        "author": "mr. monke7",
        "genre": "climate",
        "yearPublished": 1217,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:31.722Z"
    },
    {
        "id": "9669adb6-1a4f-4a6c-a49a-e07a12ec3561",
        "title": "a monke has lived his life6 times",
        "author": "mr. monke6",
        "genre": "climate",
        "yearPublished": 1216,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:31.436Z"
    },
    {
        "id": "33c702dc-5b0f-46d3-b123-82c758c0e1e8",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:31.137Z"
    },
    {
        "id": "39efef3d-4697-4fc3-8f15-c6f6fe2fab49",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:30.843Z"
    },
    {
        "id": "1657c017-c461-4040-bb60-1c1f19fe6897",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:30.523Z"
    },
    {
        "id": "dd0090e9-ae4a-4e00-9a15-548c0bf7cccf",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:30.231Z"
    },
    {
        "id": "15b5c9bd-a17e-4bdd-b76d-230463bb545e",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:29.928Z"
    },
    {
        "id": "3b676888-16d8-408b-b8db-f25a759784a4",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:01:29.105Z"
    },
    {
        "id": "37a4550c-7294-420d-ae81-5b9e1454c023",
        "title": "a monke has lived his life39 times",
        "author": "mr. monke39",
        "genre": "climate",
        "yearPublished": 1249,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:46.231Z"
    },
    {
        "id": "740b128b-723c-400f-a8df-ec0c83e7bf38",
        "title": "a monke has lived his life94 times",
        "author": "mr. monke94",
        "genre": "climate",
        "yearPublished": 1304,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.259Z"
    },
    {
        "id": "6e6ffd90-bc9d-4567-9558-9774d9a757af",
        "title": "a monke has lived his life13 times",
        "author": "mr. monke13",
        "genre": "climate",
        "yearPublished": 1223,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.242Z"
    },
    {
        "id": "b4faf63c-4856-477c-bae6-f0616932afdf",
        "title": "a monke has lived his life47 times",
        "author": "mr. monke47",
        "genre": "climate",
        "yearPublished": 1257,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.227Z"
    },
    {
        "id": "ac097f8c-06a4-4fd9-916b-ec2fb4e458f1",
        "title": "a monke has lived his life72 times",
        "author": "mr. monke72",
        "genre": "climate",
        "yearPublished": 1282,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.212Z"
    },
    {
        "id": "f4c165e7-0f7b-458c-81ba-097ef312929d",
        "title": "a monke has lived his life53 times",
        "author": "mr. monke53",
        "genre": "climate",
        "yearPublished": 1263,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.194Z"
    },
    {
        "id": "6bc36b64-d754-4e26-9da8-a9bc8796840b",
        "title": "a monke has lived his life61 times",
        "author": "mr. monke61",
        "genre": "climate",
        "yearPublished": 1271,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.107Z"
    },
    {
        "id": "75c32d1a-26bb-4b30-b3de-b853be4099de",
        "title": "a monke has lived his life5 times",
        "author": "mr. monke5",
        "genre": "climate",
        "yearPublished": 1215,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:42.016Z"
    },
    {
        "id": "1116c032-7fe9-4e45-b412-23dbb76b7f57",
        "title": "a monke has lived his life29 times",
        "author": "mr. monke29",
        "genre": "climate",
        "yearPublished": 1239,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:41.807Z"
    },
    {
        "id": "a0a0aefa-11d5-4587-8d73-91e8be5dd050",
        "title": "a monke has lived his life1 times",
        "author": "mr. monke1",
        "genre": "climate",
        "yearPublished": 1211,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:41.761Z"
    },
    {
        "id": "7ef22b34-8ff4-45df-b8e8-34c0d01f4cd9",
        "title": "a monke has lived his life17 times",
        "author": "mr. monke17",
        "genre": "climate",
        "yearPublished": 1227,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:41.574Z"
    },
    {
        "id": "7c02c2f3-731b-48f5-b055-242cb58a52bb",
        "title": "a monke has lived his life54 times",
        "author": "mr. monke54",
        "genre": "climate",
        "yearPublished": 1264,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.995Z"
    },
    {
        "id": "020b8e84-2e07-4a8f-bd2b-eb5e65d30c01",
        "title": "a monke has lived his life35 times",
        "author": "mr. monke35",
        "genre": "climate",
        "yearPublished": 1245,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.627Z"
    },
    {
        "id": "083aa69c-e132-4566-be44-6c4f09dfa70a",
        "title": "a monke has lived his life6 times",
        "author": "mr. monke6",
        "genre": "climate",
        "yearPublished": 1216,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.486Z"
    },
    {
        "id": "a330a2ff-8c9d-43a0-8cfc-34ffe3d1a26b",
        "title": "a monke has lived his life8 times",
        "author": "mr. monke8",
        "genre": "climate",
        "yearPublished": 1218,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.470Z"
    },
    {
        "id": "6d9b44db-d7ba-4d87-9003-4e339b6d1648",
        "title": "a monke has lived his life65 times",
        "author": "mr. monke65",
        "genre": "climate",
        "yearPublished": 1275,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.454Z"
    },
    {
        "id": "bcc9c002-165a-4abb-b2cc-5bae8a080b88",
        "title": "a monke has lived his life66 times",
        "author": "mr. monke66",
        "genre": "climate",
        "yearPublished": 1276,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.438Z"
    },
    {
        "id": "51b34300-79a5-40f6-90d6-23de382a527f",
        "title": "a monke has lived his life36 times",
        "author": "mr. monke36",
        "genre": "climate",
        "yearPublished": 1246,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.424Z"
    },
    {
        "id": "04c73922-a817-4713-9db5-9df32b102cdb",
        "title": "a monke has lived his life60 times",
        "author": "mr. monke60",
        "genre": "climate",
        "yearPublished": 1270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.399Z"
    },
    {
        "id": "596188e7-e1a5-418d-b2d2-e861ba585956",
        "title": "a monke has lived his life87 times",
        "author": "mr. monke87",
        "genre": "climate",
        "yearPublished": 1297,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.383Z"
    },
    {
        "id": "2c39f07e-cca0-489a-88f0-964f8976de6e",
        "title": "a monke has lived his life67 times",
        "author": "mr. monke67",
        "genre": "climate",
        "yearPublished": 1277,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.368Z"
    },
    {
        "id": "01364e05-ac4f-4cf5-b15f-58dfae83b535",
        "title": "a monke has lived his life74 times",
        "author": "mr. monke74",
        "genre": "climate",
        "yearPublished": 1284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.352Z"
    },
    {
        "id": "d53099bd-145c-4127-a06b-7ba0e548784f",
        "title": "a monke has lived his life15 times",
        "author": "mr. monke15",
        "genre": "climate",
        "yearPublished": 1225,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.336Z"
    },
    {
        "id": "50baa4e1-ddd0-4930-9aa1-15c85365e8bf",
        "title": "a monke has lived his life57 times",
        "author": "mr. monke57",
        "genre": "climate",
        "yearPublished": 1267,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.320Z"
    },
    {
        "id": "adec35b3-0463-40f8-a8c0-9d6b1c4c65ac",
        "title": "a monke has lived his life58 times",
        "author": "mr. monke58",
        "genre": "climate",
        "yearPublished": 1268,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.305Z"
    },
    {
        "id": "b3689600-38f4-47f0-b4dc-1d61a3df6850",
        "title": "a monke has lived his life37 times",
        "author": "mr. monke37",
        "genre": "climate",
        "yearPublished": 1247,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.289Z"
    },
    {
        "id": "7676b867-0098-48c1-948b-cdc9015739c8",
        "title": "a monke has lived his life46 times",
        "author": "mr. monke46",
        "genre": "climate",
        "yearPublished": 1256,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.274Z"
    },
    {
        "id": "748af897-fbb8-4044-ab37-ed35594003c6",
        "title": "a monke has lived his life41 times",
        "author": "mr. monke41",
        "genre": "climate",
        "yearPublished": 1251,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.252Z"
    },
    {
        "id": "8abd965a-fb0d-4a98-a4d0-5801aeba2619",
        "title": "a monke has lived his life79 times",
        "author": "mr. monke79",
        "genre": "climate",
        "yearPublished": 1289,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.229Z"
    },
    {
        "id": "2a9f6a63-598c-44ea-b8f2-d87daf1da6bb",
        "title": "a monke has lived his life76 times",
        "author": "mr. monke76",
        "genre": "climate",
        "yearPublished": 1286,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.212Z"
    },
    {
        "id": "ce85b38d-f7ff-4f9b-b2e1-71a00b040bef",
        "title": "a monke has lived his life49 times",
        "author": "mr. monke49",
        "genre": "climate",
        "yearPublished": 1259,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.196Z"
    },
    {
        "id": "dee957a1-b34b-4fe7-8db0-dde22c4de26d",
        "title": "a monke has lived his life7 times",
        "author": "mr. monke7",
        "genre": "climate",
        "yearPublished": 1217,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.103Z"
    },
    {
        "id": "f7b73dd6-0250-4ba7-986b-428843ccaeea",
        "title": "a monke has lived his life63 times",
        "author": "mr. monke63",
        "genre": "climate",
        "yearPublished": 1273,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.084Z"
    },
    {
        "id": "d29df78c-8b73-4d0e-87e9-62bf1bae72e6",
        "title": "a monke has lived his life42 times",
        "author": "mr. monke42",
        "genre": "climate",
        "yearPublished": 1252,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.032Z"
    },
    {
        "id": "f6a0cc20-93d8-4c75-8b1d-4d16c8d19bc6",
        "title": "a monke has lived his life4 times",
        "author": "mr. monke4",
        "genre": "climate",
        "yearPublished": 1214,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.017Z"
    },
    {
        "id": "34711b65-a764-4657-9e4c-d467a51ce057",
        "title": "a monke has lived his life33 times",
        "author": "mr. monke33",
        "genre": "climate",
        "yearPublished": 1243,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:40.000Z"
    },
    {
        "id": "09544e3e-3b4c-4231-912e-9209b0416b6d",
        "title": "a monke has lived his life40 times",
        "author": "mr. monke40",
        "genre": "climate",
        "yearPublished": 1250,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.985Z"
    },
    {
        "id": "3aba626b-d6e0-4d6c-8a08-2abcbed56e98",
        "title": "a monke has lived his life48 times",
        "author": "mr. monke48",
        "genre": "climate",
        "yearPublished": 1258,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.963Z"
    },
    {
        "id": "3d1b815f-c2bf-44ae-bb9c-f31215d3359f",
        "title": "a monke has lived his life38 times",
        "author": "mr. monke38",
        "genre": "climate",
        "yearPublished": 1248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.947Z"
    },
    {
        "id": "b6fcd98e-622c-4685-bc52-98ece47ede0f",
        "title": "a monke has lived his life31 times",
        "author": "mr. monke31",
        "genre": "climate",
        "yearPublished": 1241,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.932Z"
    },
    {
        "id": "058aa017-61ff-4fd8-8742-bc31c6b84a54",
        "title": "a monke has lived his life25 times",
        "author": "mr. monke25",
        "genre": "climate",
        "yearPublished": 1235,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.916Z"
    },
    {
        "id": "dbc3eac2-48b7-409d-9d48-f314384e468a",
        "title": "a monke has lived his life90 times",
        "author": "mr. monke90",
        "genre": "climate",
        "yearPublished": 1300,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.901Z"
    },
    {
        "id": "159b32c6-6bb7-43b0-bc8a-c48c6190fca5",
        "title": "a monke has lived his life96 times",
        "author": "mr. monke96",
        "genre": "climate",
        "yearPublished": 1306,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.885Z"
    },
    {
        "id": "79f01e18-ff0e-4526-97cf-9bc303c85939",
        "title": "a monke has lived his life81 times",
        "author": "mr. monke81",
        "genre": "climate",
        "yearPublished": 1291,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.870Z"
    },
    {
        "id": "a7ed8506-1760-43f3-846d-786e436c1802",
        "title": "a monke has lived his life98 times",
        "author": "mr. monke98",
        "genre": "climate",
        "yearPublished": 1308,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.854Z"
    },
    {
        "id": "de7d91aa-cf63-4441-8184-378661c51e58",
        "title": "a monke has lived his life9 times",
        "author": "mr. monke9",
        "genre": "climate",
        "yearPublished": 1219,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.838Z"
    },
    {
        "id": "66c03a19-6c1b-4563-b2ab-26eba31fb2aa",
        "title": "a monke has lived his life11 times",
        "author": "mr. monke11",
        "genre": "climate",
        "yearPublished": 1221,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.822Z"
    },
    {
        "id": "f4529dbb-babd-4373-8426-e7bc315019f7",
        "title": "a monke has lived his life83 times",
        "author": "mr. monke83",
        "genre": "climate",
        "yearPublished": 1293,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.804Z"
    },
    {
        "id": "516cfbb8-6ecd-4f38-9cd2-c6ea203a86df",
        "title": "a monke has lived his life32 times",
        "author": "mr. monke32",
        "genre": "climate",
        "yearPublished": 1242,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.722Z"
    },
    {
        "id": "c58aa4c9-564a-4f27-a558-9ea231c28169",
        "title": "a monke has lived his life12 times",
        "author": "mr. monke12",
        "genre": "climate",
        "yearPublished": 1222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.557Z"
    },
    {
        "id": "9fec5990-6cc7-4dd5-a5e3-d562827c5aac",
        "title": "a monke has lived his life91 times",
        "author": "mr. monke91",
        "genre": "climate",
        "yearPublished": 1301,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.541Z"
    },
    {
        "id": "50b4c8fd-3b1e-4404-8aac-3ec6dca856fd",
        "title": "a monke has lived his life56 times",
        "author": "mr. monke56",
        "genre": "climate",
        "yearPublished": 1266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.526Z"
    },
    {
        "id": "3ed2411f-bd1c-4571-afda-2d21057fbdde",
        "title": "a monke has lived his life22 times",
        "author": "mr. monke22",
        "genre": "climate",
        "yearPublished": 1232,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.484Z"
    },
    {
        "id": "2f50a856-799e-4a1f-95b6-f63c89cc5d08",
        "title": "a monke has lived his life69 times",
        "author": "mr. monke69",
        "genre": "climate",
        "yearPublished": 1279,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.374Z"
    },
    {
        "id": "dc75283e-10c0-403e-bd6d-cd9f784b1ecb",
        "title": "a monke has lived his life86 times",
        "author": "mr. monke86",
        "genre": "climate",
        "yearPublished": 1296,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.359Z"
    },
    {
        "id": "dee2f6fc-ade1-4cb1-8ee4-08fa069f7e54",
        "title": "a monke has lived his life16 times",
        "author": "mr. monke16",
        "genre": "climate",
        "yearPublished": 1226,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.340Z"
    },
    {
        "id": "4544c318-2d71-4810-922c-57cfccf11fb1",
        "title": "a monke has lived his life80 times",
        "author": "mr. monke80",
        "genre": "climate",
        "yearPublished": 1290,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.324Z"
    },
    {
        "id": "a5cd1e21-d212-4a30-9649-41d614ad65a2",
        "title": "a monke has lived his life97 times",
        "author": "mr. monke97",
        "genre": "climate",
        "yearPublished": 1307,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.303Z"
    },
    {
        "id": "7f3734f8-1d27-4660-8c73-c65a54e1a005",
        "title": "a monke has lived his life59 times",
        "author": "mr. monke59",
        "genre": "climate",
        "yearPublished": 1269,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.288Z"
    },
    {
        "id": "69dbdf1b-547f-40b3-bc9c-5ed8835c8a09",
        "title": "a monke has lived his life50 times",
        "author": "mr. monke50",
        "genre": "climate",
        "yearPublished": 1260,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.272Z"
    },
    {
        "id": "9f5af720-299d-41c2-91cf-079a6a309dff",
        "title": "a monke has lived his life19 times",
        "author": "mr. monke19",
        "genre": "climate",
        "yearPublished": 1229,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.256Z"
    },
    {
        "id": "7f4e2b75-4491-4a8a-9a30-263a31807559",
        "title": "a monke has lived his life64 times",
        "author": "mr. monke64",
        "genre": "climate",
        "yearPublished": 1274,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.241Z"
    },
    {
        "id": "bec173b0-98e3-4fbf-be7b-8dd75530b9a2",
        "title": "a monke has lived his life89 times",
        "author": "mr. monke89",
        "genre": "climate",
        "yearPublished": 1299,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.226Z"
    },
    {
        "id": "90b8b9a6-f7d0-44f2-950c-0cc488a7a58d",
        "title": "a monke has lived his life52 times",
        "author": "mr. monke52",
        "genre": "climate",
        "yearPublished": 1262,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.210Z"
    },
    {
        "id": "3abca85e-ac44-49d9-a152-2fef2b2af2df",
        "title": "a monke has lived his life3 times",
        "author": "mr. monke3",
        "genre": "climate",
        "yearPublished": 1213,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.193Z"
    },
    {
        "id": "e9fbb83c-e2c5-43e1-989a-1405ddee8f82",
        "title": "a monke has lived his life2 times",
        "author": "mr. monke2",
        "genre": "climate",
        "yearPublished": 1212,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.173Z"
    },
    {
        "id": "697760b5-0297-4ab7-9f21-31741e21ac30",
        "title": "a monke has lived his life14 times",
        "author": "mr. monke14",
        "genre": "climate",
        "yearPublished": 1224,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.158Z"
    },
    {
        "id": "956cf770-32a6-4aec-8647-1339d5df53d7",
        "title": "a monke has lived his life26 times",
        "author": "mr. monke26",
        "genre": "climate",
        "yearPublished": 1236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.141Z"
    },
    {
        "id": "9a36528d-ba3e-4076-bf27-709a4db07560",
        "title": "a monke has lived his life24 times",
        "author": "mr. monke24",
        "genre": "climate",
        "yearPublished": 1234,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.126Z"
    },
    {
        "id": "b719a0f0-74ee-4064-893f-74bf26553256",
        "title": "a monke has lived his life99 times",
        "author": "mr. monke99",
        "genre": "climate",
        "yearPublished": 1309,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.110Z"
    },
    {
        "id": "46abe719-3b6f-492f-aa3c-ddbc5640cf86",
        "title": "a monke has lived his life20 times",
        "author": "mr. monke20",
        "genre": "climate",
        "yearPublished": 1230,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.094Z"
    },
    {
        "id": "6ab59f10-1405-4824-bc7b-d271e2fc635f",
        "title": "a monke has lived his life0 times",
        "author": "mr. monke0",
        "genre": "climate",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.078Z"
    },
    {
        "id": "834639ab-ba37-49a0-904e-d97fa34bd07f",
        "title": "a monke has lived his life51 times",
        "author": "mr. monke51",
        "genre": "climate",
        "yearPublished": 1261,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.061Z"
    },
    {
        "id": "ba4a5b31-037e-4f31-825f-ada3c91abc14",
        "title": "a monke has lived his life23 times",
        "author": "mr. monke23",
        "genre": "climate",
        "yearPublished": 1233,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.021Z"
    },
    {
        "id": "97a4be41-072f-4e5f-a513-4a1707ab0cf2",
        "title": "a monke has lived his life82 times",
        "author": "mr. monke82",
        "genre": "climate",
        "yearPublished": 1292,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:39.006Z"
    },
    {
        "id": "1adae2fe-d882-47d5-873a-c574e2f20482",
        "title": "a monke has lived his life70 times",
        "author": "mr. monke70",
        "genre": "climate",
        "yearPublished": 1280,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.973Z"
    },
    {
        "id": "2b2a14e8-637a-4970-b3d0-af7ccabd0a40",
        "title": "a monke has lived his life30 times",
        "author": "mr. monke30",
        "genre": "climate",
        "yearPublished": 1240,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.821Z"
    },
    {
        "id": "e3912135-f4db-4e94-a854-404180d87fc3",
        "title": "a monke has lived his life55 times",
        "author": "mr. monke55",
        "genre": "climate",
        "yearPublished": 1265,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.805Z"
    },
    {
        "id": "150c345b-f251-42ab-bc58-8d90d358884c",
        "title": "a monke has lived his life68 times",
        "author": "mr. monke68",
        "genre": "climate",
        "yearPublished": 1278,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.790Z"
    },
    {
        "id": "c4b96690-b267-48fc-afd1-72faf342af62",
        "title": "a monke has lived his life45 times",
        "author": "mr. monke45",
        "genre": "climate",
        "yearPublished": 1255,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.774Z"
    },
    {
        "id": "f5276d6b-b449-42b9-8da6-a03e4c007b60",
        "title": "a monke has lived his life34 times",
        "author": "mr. monke34",
        "genre": "climate",
        "yearPublished": 1244,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.747Z"
    },
    {
        "id": "6e328d83-c275-4b8a-b155-cf4714614c95",
        "title": "a monke has lived his life93 times",
        "author": "mr. monke93",
        "genre": "climate",
        "yearPublished": 1303,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.732Z"
    },
    {
        "id": "dc583fe8-4601-49cf-8d5f-ed0e6ea1cf04",
        "title": "a monke has lived his life43 times",
        "author": "mr. monke43",
        "genre": "climate",
        "yearPublished": 1253,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.716Z"
    },
    {
        "id": "771f04a3-4f87-4f07-ad60-ce8522b95f37",
        "title": "a monke has lived his life73 times",
        "author": "mr. monke73",
        "genre": "climate",
        "yearPublished": 1283,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.699Z"
    },
    {
        "id": "2aee08d2-c948-48c9-b261-b6297fa39d47",
        "title": "a monke has lived his life84 times",
        "author": "mr. monke84",
        "genre": "climate",
        "yearPublished": 1294,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.683Z"
    },
    {
        "id": "0c218693-65ee-407b-8612-6133ce7a5fe4",
        "title": "a monke has lived his life77 times",
        "author": "mr. monke77",
        "genre": "climate",
        "yearPublished": 1287,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.560Z"
    },
    {
        "id": "1f72ad63-06c4-4f1d-a191-62c8abac1458",
        "title": "a monke has lived his life18 times",
        "author": "mr. monke18",
        "genre": "climate",
        "yearPublished": 1228,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.544Z"
    },
    {
        "id": "73dacdb8-dfe1-4d79-9e05-d18b01402bef",
        "title": "a monke has lived his life88 times",
        "author": "mr. monke88",
        "genre": "climate",
        "yearPublished": 1298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.528Z"
    },
    {
        "id": "f247092d-1238-4cf9-ad19-b2b3092cd236",
        "title": "a monke has lived his life95 times",
        "author": "mr. monke95",
        "genre": "climate",
        "yearPublished": 1305,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.511Z"
    },
    {
        "id": "28d5755c-6955-4d89-81c4-12105d3f2518",
        "title": "a monke has lived his life92 times",
        "author": "mr. monke92",
        "genre": "climate",
        "yearPublished": 1302,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.509Z"
    },
    {
        "id": "54bb1e8a-17db-48ce-9528-87d7b524511c",
        "title": "a monke has lived his life10 times",
        "author": "mr. monke10",
        "genre": "climate",
        "yearPublished": 1220,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.507Z"
    },
    {
        "id": "ef7e3242-d455-48f4-ae9e-c30e5b25d7d8",
        "title": "a monke has lived his life75 times",
        "author": "mr. monke75",
        "genre": "climate",
        "yearPublished": 1285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.506Z"
    },
    {
        "id": "c7f78a90-3652-42dc-8c25-024b06a4a9b9",
        "title": "a monke has lived his life71 times",
        "author": "mr. monke71",
        "genre": "climate",
        "yearPublished": 1281,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.506Z"
    },
    {
        "id": "722c159d-107a-412f-ab47-67e1076e31e7",
        "title": "a monke has lived his life62 times",
        "author": "mr. monke62",
        "genre": "climate",
        "yearPublished": 1272,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.505Z"
    },
    {
        "id": "c4654876-989f-4d10-aa90-7f9c1b85ae29",
        "title": "a monke has lived his life21 times",
        "author": "mr. monke21",
        "genre": "climate",
        "yearPublished": 1231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.504Z"
    },
    {
        "id": "7662e197-407f-4c2d-88d9-82e563814071",
        "title": "a monke has lived his life85 times",
        "author": "mr. monke85",
        "genre": "climate",
        "yearPublished": 1295,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.480Z"
    },
    {
        "id": "2b91c95d-9fad-4b6c-939f-2b841ab2a099",
        "title": "a monke has lived his life27 times",
        "author": "mr. monke27",
        "genre": "climate",
        "yearPublished": 1237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.381Z"
    },
    {
        "id": "dbff5531-8d2f-4b83-af03-ac601e99bc1f",
        "title": "a monke has lived his life78 times",
        "author": "mr. monke78",
        "genre": "climate",
        "yearPublished": 1288,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.380Z"
    },
    {
        "id": "ec43039d-e030-41de-90c5-b9eec5513d62",
        "title": "a monke has lived his life44 times",
        "author": "mr. monke44",
        "genre": "climate",
        "yearPublished": 1254,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.379Z"
    },
    {
        "id": "b240eab6-b4f4-45eb-9437-4638c33f4477",
        "title": "a monke has lived his life28 times",
        "author": "mr. monke28",
        "genre": "climate",
        "yearPublished": 1238,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T07:00:38.328Z"
    },
    {
        "id": "c8b3b732-773a-4431-a9cb-2fb510884f8b",
        "title": "A Passage to India",
        "author": "E.M.Foster",
        "genre": "fiction",
        "yearPublished": 1924,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:59:11.129Z"
    },
    {
        "id": "af70c341-0c30-4c60-8986-8974c850a5ef",
        "title": "a monke living his life",
        "author": "mr. monke",
        "genre": "fantasy",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:58:14.827Z"
    },
    {
        "id": "258eed96-6446-4cc1-b8c2-070ebe8c504b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:58:08.184Z"
    },
    {
        "id": "da2f91d0-fa0c-40fd-a714-20c51a92b679",
        "title": "a monke living his life",
        "author": "mr. monke",
        "genre": "fantasy",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:55:46.169Z"
    },
    {
        "id": "8285a0ab-5567-4ac7-b105-9034318dc213",
        "title": "the twilight saga",
        "author": "stephanie meyer",
        "genre": "romantic fantasy",
        "yearPublished": 2005,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:52:51.427Z"
    },
    {
        "id": "3c9ee5e7-63d6-4381-9b0a-7582689a20d0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:51:59.917Z"
    },
    {
        "id": "36578838-b3e0-4d99-9536-34b486c223ee",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:50:53.738Z"
    },
    {
        "id": "20ce53b6-5009-4210-a7ff-cd8bfcb01fbc",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:47:50.463Z"
    },
    {
        "id": "1bf7ee55-57f1-4b93-9bcb-46fd93c9eb88",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:47:05.604Z"
    },
    {
        "id": "4161a63f-bcdd-4b24-a09e-14858481cb87",
        "title": "Jane Eyre",
        "author": "Charlotte Bronte",
        "genre": "fiction",
        "yearPublished": 1847,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:45:07.236Z"
    },
    {
        "id": "1fe9834f-700e-43f9-91d4-8f95bf21b983",
        "title": "Harry Potter",
        "author": "JK Rowling",
        "genre": "fiction",
        "yearPublished": 2002,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:44:13.006Z"
    },
    {
        "id": "b834ab81-a434-47cf-901b-52d57e29f55c",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:43:53.544Z"
    },
    {
        "id": "ff542399-d32a-4764-9e31-6731a5223a24",
        "title": "the twilight saga",
        "author": "stephanie meyer",
        "genre": "romantic fantasy",
        "yearPublished": 2005,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:43:09.270Z"
    },
    {
        "id": "2ec2f04c-6270-4dbc-8df3-150b08414014",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:42:47.302Z"
    },
    {
        "id": "488cad3a-32a4-47f0-a3dc-849bae255973",
        "title": "API 101 with Ali",
        "author": "Ved Bhoir",
        "genre": "education",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:42:05.439Z"
    },
    {
        "id": "7477cde3-1f28-4629-80de-45364e741571",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:41:33.149Z"
    },
    {
        "id": "2cdb4871-3de3-4437-af86-f1338538ed59",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:40:07.435Z"
    },
    {
        "id": "2feaf86c-d938-4a11-82cc-785eace0f7a9",
        "title": "API 101 with Ali",
        "author": "Ved Bhoir",
        "genre": "education",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:38:35.521Z"
    },
    {
        "id": "d5ca4a6b-ed95-4d51-a6c6-71573c891661",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:37:34.562Z"
    },
    {
        "id": "6da58003-8e68-4782-8747-6472900a2888",
        "title": "a monke living his life",
        "author": "mr. monke",
        "genre": "fantasy",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:37:25.907Z"
    },
    {
        "id": "373c1a22-f41f-47e7-a104-36429d257372",
        "title": "the twilight saga",
        "author": "stephanie meyer",
        "genre": "romantic fantasy",
        "yearPublished": 2005,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:37:08.235Z"
    },
    {
        "id": "c2cd723a-85aa-4e4c-a0b0-6b44e0f79bd4",
        "title": "The Great Gatsby",
        "author": "F.Scott Fitzgerald",
        "genre": "fiction",
        "yearPublished": 1925,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:37:00.128Z"
    },
    {
        "id": "62b4e487-5289-44a0-9031-05bf97990826",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:35:52.837Z"
    },
    {
        "id": "304ee6b3-6397-49c2-a9d5-436edc0c8286",
        "title": "king of wrath",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:34:34.680Z"
    },
    {
        "id": "e4816e1d-6683-49d7-a6d3-45a55c16037f",
        "title": "Hunger Games",
        "author": "Suzanne Collins",
        "genre": "fiction",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:33:45.463Z"
    },
    {
        "id": "e7e96592-30a7-4c96-a3d6-c4abd2187211",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:32:26.575Z"
    },
    {
        "id": "dffaa545-eea6-42bc-a1c8-22d11534a37c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:27:54.677Z"
    },
    {
        "id": "e239d749-57eb-4ab1-a024-66216bb0a9bd",
        "title": "Bulbul2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:22:12.701Z"
    },
    {
        "id": "d5423d4f-8dbe-444b-a4dd-a31c17894763",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:21:53.576Z"
    },
    {
        "id": "f9da6b18-8536-466b-a435-3133a85f9b39",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:20:26.584Z"
    },
    {
        "id": "7a54a5da-df58-4575-869d-11a0e3885343",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:20:13.055Z"
    },
    {
        "id": "dbfcfdb7-cab9-4115-8c6d-3fc45da9861e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:19:46.616Z"
    },
    {
        "id": "36aa9e20-53c9-49fc-b1fd-d278538f6741",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:17:13.985Z"
    },
    {
        "id": "35300205-1c70-4b17-be3d-32abdd3ba3f4",
        "title": "Malgudi Days",
        "author": "Narayan R K",
        "genre": "Short story collections",
        "yearPublished": 1942,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:17:11.448Z"
    },
    {
        "id": "e6fcf2cd-defe-40dc-aae4-31ff7a6e7907",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:16:30.117Z"
    },
    {
        "id": "9c1cc3be-5750-4d0b-ab8e-8bfc99f7a406",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:16:15.263Z"
    },
    {
        "id": "0c70b44d-443d-42d3-9edc-323fd9846e6f",
        "title": "a monke living his life",
        "author": "mr. monke",
        "genre": "fantasy",
        "yearPublished": 1210,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:16:02.412Z"
    },
    {
        "id": "f0170962-ed62-4b70-addb-2da8c21d124d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:15:35.397Z"
    },
    {
        "id": "6550c9aa-6b86-4586-8ddf-d6f53d6c6c01",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:15:02.477Z"
    },
    {
        "id": "41fce7f1-8a8b-4126-b0ad-46a847616e0c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:14:36.701Z"
    },
    {
        "id": "ab526113-549d-41d9-bffc-73a557424e65",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:13:23.232Z"
    },
    {
        "id": "bcb6823e-a292-4ea7-b512-5889576d95f2",
        "title": "Bulbul",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:13:19.394Z"
    },
    {
        "id": "d265220e-0800-4edc-835d-e71171a3d321",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:12:46.170Z"
    },
    {
        "id": "7f058b44-b97f-4067-9bc4-1b2b64a550bc",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:08:48.415Z"
    },
    {
        "id": "da86ff67-2d43-463f-b93a-edab868b59e3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:05:45.454Z"
    },
    {
        "id": "b326c21a-abed-427d-8651-3a44c8b0e149",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:04:58.180Z"
    },
    {
        "id": "710508bd-9036-4d32-8f85-eb36f22cad8b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:02:46.227Z"
    },
    {
        "id": "fbeb208a-3808-436a-a588-3340fa9bcc43",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:01:08.231Z"
    },
    {
        "id": "1a3ae26d-ac40-446b-9158-84b5ccc10962",
        "title": "To Kill12",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1969,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T06:00:35.992Z"
    },
    {
        "id": "a730e774-a75f-404c-b1b9-d4d691a0e2c3",
        "title": "Psychology Of Money",
        "author": "Morgan Housel",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:56:08.481Z"
    },
    {
        "id": "b2fda074-e717-474a-a609-6a2acec6b399",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction1",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:53:15.195Z"
    },
    {
        "id": "3ab46209-df48-48a4-ba7b-1844389ddc9b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:53:12.778Z"
    },
    {
        "id": "091c1404-b287-4545-a2bf-e8c87304ce16",
        "title": "abcd",
        "author": "xyz",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:49:28.003Z"
    },
    {
        "id": "ef67c7e7-d821-4058-8800-83dc00ce92c6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:48:45.313Z"
    },
    {
        "id": "d988bb35-3cb9-44f0-b902-dd5f280259e2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:42:14.337Z"
    },
    {
        "id": "779164ea-1c95-4f5a-83fa-f1a7bff3bce4",
        "title": "twisted series",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:42:11.667Z"
    },
    {
        "id": "8123bf8d-1c4b-46c8-b2bf-3afea8ffb27c",
        "title": "twisted series",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:42:03.422Z"
    },
    {
        "id": "9034f982-f8b8-4fd2-8823-de876d8e64fc",
        "title": "sherlock holmes",
        "author": "Arthur Conan Doyle",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:38:11.651Z"
    },
    {
        "id": "88613120-01f6-4c30-9f4e-6ea5327cc8cc",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:28:04.958Z"
    },
    {
        "id": "3e548e9f-a76a-4f6f-a90d-c6b672cd22d6",
        "title": "becoming",
        "author": "michelle Obama",
        "genre": "biography",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:27:38.958Z"
    },
    {
        "id": "473c1755-0359-4f74-8d7b-67394b7bd24d",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:25:30.878Z"
    },
    {
        "id": "8023f924-1c54-4838-a8aa-fe1c10de9ccd",
        "title": "twisted series",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:22:43.027Z"
    },
    {
        "id": "0ab19e46-d956-46ed-999c-5edd877bde86",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:14:17.418Z"
    },
    {
        "id": "ec0c6db4-f63d-4d89-9152-5efd4cb03513",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:14:13.142Z"
    },
    {
        "id": "21ad81aa-eacc-4477-b4b5-170e1ac29aa2",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:12:04.885Z"
    },
    {
        "id": "e53103d5-fc09-4111-9701-816f42358f75",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:10:00.507Z"
    },
    {
        "id": "510a5dc8-954f-41e9-b3a4-d346fe7ef8de",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:09:52.650Z"
    },
    {
        "id": "a0968596-9413-4096-8077-0dbc0f2ff249",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:09:45.357Z"
    },
    {
        "id": "3c2e5445-6e8c-4cf1-bd7b-eeae32967021",
        "title": "Faith",
        "author": "Jaik",
        "genre": "fiction",
        "yearPublished": 1969,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:09:40.992Z"
    },
    {
        "id": "bbf33231-411c-426c-943f-93e2ffba930c",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:09:08.596Z"
    },
    {
        "id": "e5d5c4df-a1b1-4bc6-9a8f-5f418463fac8",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:08:04.548Z"
    },
    {
        "id": "b9a12eba-0ada-4d1a-a1e1-146781d68745",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:06:29.392Z"
    },
    {
        "id": "5f43d411-a738-40eb-ba91-e80a5d5ccb39",
        "title": "Iron man",
        "author": "Stan Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:06:07.886Z"
    },
    {
        "id": "3c9149c5-d9f6-476f-812b-fda79db1e3fa",
        "title": "Humming",
        "author": "Harris",
        "genre": "fiction",
        "yearPublished": 1950,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:06:05.166Z"
    },
    {
        "id": "99c3e70e-ef07-4489-ab56-75b5f16f8414",
        "title": "RAM-Scion of Ikshvaku",
        "author": "amish",
        "genre": "fiction",
        "yearPublished": 2015,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T05:00:06.225Z"
    },
    {
        "id": "63d1bda2-1827-47a3-a782-9fda7bb3da1e",
        "title": "Spiderman",
        "author": "Stan Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:59:36.879Z"
    },
    {
        "id": "36a226f0-d7ee-4f1d-b7ef-465b629403e3",
        "title": "Ragnarok",
        "author": "Stan Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:56:44.718Z"
    },
    {
        "id": "0bbabad1-1c60-4dc9-89d0-484e64975b23",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:56:22.982Z"
    },
    {
        "id": "ac744e0b-0d8d-458c-bab6-d127136246fa",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:54:08.359Z"
    },
    {
        "id": "769004aa-a10d-4882-9a73-0e20765b4c8e",
        "title": "To Kill123",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1969,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:51:06.133Z"
    },
    {
        "id": "2c9b86be-d62e-4228-8db3-bfa81e4f19ef",
        "title": "To Kill a Mockingbirds1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:50:22.510Z"
    },
    {
        "id": "a1319f8b-0150-4865-943a-2c4fd6c37273",
        "title": "To Kill a Mockingbirds1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:48:11.954Z"
    },
    {
        "id": "8eb7a83f-8adb-4d41-b7ea-72c601747f6f",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:45:11.913Z"
    },
    {
        "id": "7220bfd1-7a17-45ee-9421-607b5c7f7d75",
        "title": "To Kill a Mockingbirds1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:42:40.842Z"
    },
    {
        "id": "7dfa64e6-ba83-474c-832a-92cbb81e4c30",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:42:00.886Z"
    },
    {
        "id": "01f64eb2-df77-4852-b0c5-3d8f014805c4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:40:58.932Z"
    },
    {
        "id": "950b30d6-f1cd-4185-94fe-80fbd1760b80",
        "title": "one thousand and one nights 1",
        "author": "ibn al-Muqaffa 2",
        "genre": "fiction",
        "yearPublished": 1706,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:33:21.650Z"
    },
    {
        "id": "c0ce3635-42c9-4524-be47-341edc263572",
        "title": "one thousand and one nights 1",
        "author": "ibn al-Muqaffa 2",
        "genre": "fiction",
        "yearPublished": 1706,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:25:52.325Z"
    },
    {
        "id": "de40328d-a705-4f8c-8b69-a83ef09a976a",
        "title": "Tom is on the way",
        "author": "Tom Lee",
        "genre": "fantasy",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:22:52.133Z"
    },
    {
        "id": "d3edfee8-804a-4f85-b29f-d90affd3740b",
        "title": "one thousand and one nights",
        "author": "ibn al-Muqaffa",
        "genre": "fiction",
        "yearPublished": 1706,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:20:30.839Z"
    },
    {
        "id": "1f8e0bba-c5ab-4398-a30f-4c3b20196af1",
        "title": "Tom is on the way",
        "author": "Tom Lee",
        "genre": "fantasy",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:13:31.434Z"
    },
    {
        "id": "95079a25-8794-4f1e-b0d6-59e62a0bcedd",
        "title": "Tom is on the way",
        "author": "Tom Lee",
        "genre": "fantasy",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:07:56.078Z"
    },
    {
        "id": "193de636-6a26-419b-8ca0-0f8c5f8b314d",
        "title": "Architecto optio consequatur hic provident et aspernatur facere quisquam.",
        "author": "Mrs. Sandra Witting",
        "genre": "tech",
        "yearPublished": 640,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:05:14.754Z"
    },
    {
        "id": "d536f5a9-1d39-48cd-a3e2-1bc1dd6430a4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T04:00:14.549Z"
    },
    {
        "id": "a14b01ca-3683-4818-8319-eabecf78bbb6",
        "title": "To Kill a Mockingbirds",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:49:40.052Z"
    },
    {
        "id": "cc861e04-af10-4e24-a912-fcc93132f5d3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:47:13.006Z"
    },
    {
        "id": "0c106b72-1712-4556-9c32-8ddadcd5ffb6",
        "title": "To Kill a Mockingbirds",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:43:43.421Z"
    },
    {
        "id": "39d8b93d-bfe5-4ae5-8e85-f0936ebb7c90",
        "title": "To Kill a Mockingbirds",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:43:15.427Z"
    },
    {
        "id": "25889ab5-912f-4d57-93c9-dc77ffd0c5ea",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:42:14.950Z"
    },
    {
        "id": "fe4a7c0b-15e1-4ecd-a7c8-a811fb6e087a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:36:47.508Z"
    },
    {
        "id": "0fb741fb-e947-44e3-8c12-bca9db9afb6e",
        "title": "To Love is to hate",
        "author": "Vanice Banks",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T03:18:55.089Z"
    },
    {
        "id": "f6f3f91e-8522-4703-abcf-a538b36eb70a",
        "title": "Harry Potter",
        "author": "J.K. Rowling",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T02:49:07.829Z"
    },
    {
        "id": "b52de930-92bf-40c7-bb7d-34c70a19a9cb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T02:29:31.028Z"
    },
    {
        "id": "82a5b3f0-dc98-4bbd-a219-7965e9a6c2a3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T02:28:02.050Z"
    },
    {
        "id": "1fd6ec2d-e944-41ac-bc3f-15cb8d157ed2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T02:18:09.386Z"
    },
    {
        "id": "1cd27998-48f8-4f62-a516-46f298559380",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T02:11:21.626Z"
    },
    {
        "id": "986720b6-2ede-4379-8c7f-5038be3f5c9d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T01:37:21.725Z"
    },
    {
        "id": "908121fd-114f-489a-87fc-dd517a7e24a0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T01:35:52.761Z"
    },
    {
        "id": "c43a26cb-389e-4a84-ac04-00b37c43f573",
        "title": "Another book by Juli Vidal",
        "author": "Juli-CVidal",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-15T00:23:01.739Z"
    },
    {
        "id": "a5d22df0-5a80-460b-9a94-b48680fdd747",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T23:11:42.011Z"
    },
    {
        "id": "5df33714-3a5b-4341-9637-66eb5a7fbe88",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T23:09:17.476Z"
    },
    {
        "id": "380dfc8b-657a-47e2-97e4-56ee2711e9c5",
        "title": "To Kill a Stranger",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T23:01:59.239Z"
    },
    {
        "id": "784fc118-8d7c-49d0-8328-3ad0c3196383",
        "title": "The dark walk",
        "author": "Nithin",
        "genre": "horror",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:59:24.957Z"
    },
    {
        "id": "34b049bb-5301-4f7e-b9e8-408fdb052d02",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:35:53.252Z"
    },
    {
        "id": "368da237-8aae-4dc5-bd41-d8bd8bede50d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:23:26.353Z"
    },
    {
        "id": "e3c3fe4a-7b0a-4585-8259-9a0e696d5958",
        "title": "RAM-Scion of Ikshvaku",
        "author": "amish",
        "genre": "fiction",
        "yearPublished": 2015,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:07:07.220Z"
    },
    {
        "id": "03689c47-3955-43c8-ae6d-e9d633118850",
        "title": "The Fault",
        "author": "Ron",
        "genre": "fiction",
        "yearPublished": 2017,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:04:50.320Z"
    },
    {
        "id": "59069ad7-9427-44a1-951b-28e3d21f06af",
        "title": "The Fault",
        "author": "Mercedes Ron",
        "genre": "fiction",
        "yearPublished": 2017,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T22:04:11.284Z"
    },
    {
        "id": "6496c429-fdb1-4ab8-bf2b-d5dafaadee8a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:51:32.222Z"
    },
    {
        "id": "0e4b61a9-57f9-437a-92be-f8f724517091",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:45:47.479Z"
    },
    {
        "id": "6b0404f2-fbb5-4006-9843-42802d7aa311",
        "title": "To Kill a Mockingbird 123",
        "author": "Harper Lee 1",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:45:26.362Z"
    },
    {
        "id": "1a8cf483-2937-4e1b-a654-880c750939d9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:42:33.160Z"
    },
    {
        "id": "b4723854-3c3f-40f3-bc3c-2dfa9200fa4b",
        "title": "surviving maladaptive daydreaming",
        "author": "Farah",
        "genre": "thriller",
        "yearPublished": 2030,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:42:06.906Z"
    },
    {
        "id": "faf53352-b19c-4c7f-bc66-d77ac93efef4",
        "title": "To Kill a Mockingbird 123",
        "author": "Harper Lee 1",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:41:54.758Z"
    },
    {
        "id": "161acf13-985a-4513-9687-71a24381a814",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:41:30.655Z"
    },
    {
        "id": "8e6c6d00-7994-4c3a-a82f-69e696591dc1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:40:18.490Z"
    },
    {
        "id": "c5a41971-4535-4b26-821f-05f39e635624",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:39:28.547Z"
    },
    {
        "id": "b833f4fc-9a51-4826-8aca-c18f1b6f30e2",
        "title": "AI Superpowers",
        "author": "Kai-Fu Lee",
        "genre": "non-fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:35:18.769Z"
    },
    {
        "id": "29ee9c3f-1b09-40dd-b403-7d131d0accd1",
        "title": "Randikaaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:34:52.220Z"
    },
    {
        "id": "5fffe37e-058d-42b6-b4b6-8fdab389ef79",
        "title": "Randikaaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:33:26.373Z"
    },
    {
        "id": "7d695f12-c52b-464f-a061-8019719b8180",
        "title": "Randikaaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:30:35.323Z"
    },
    {
        "id": "c26e702a-cf1c-4199-b69c-28a6c4fe60ed",
        "title": "Randikaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:29:57.471Z"
    },
    {
        "id": "58e3739a-ead8-404b-b10d-facdb88c6077",
        "title": "Randikaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:29:35.204Z"
    },
    {
        "id": "21d32b40-1028-4a57-a2b8-34b5b54447c7",
        "title": "Randikaaa fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:28:06.258Z"
    },
    {
        "id": "a9bef629-4f26-4ef9-898a-364ba7b97cc7",
        "title": "Randika fernando",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:27:58.760Z"
    },
    {
        "id": "c82d5193-6708-4627-88bf-6888b428d3a7",
        "title": "surviving maladaptive daydreaming",
        "author": "Farah",
        "genre": "thriller",
        "yearPublished": 2030,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:19:52.830Z"
    },
    {
        "id": "1aa0566f-c92d-44f3-bac1-ddd966513da7",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:18:08.728Z"
    },
    {
        "id": "bc5a6f49-ef03-4548-adef-2c2adadaf18e",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:17:07.703Z"
    },
    {
        "id": "7475e7a8-39df-42cd-9a8d-7ef5c7d94183",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:15:59.490Z"
    },
    {
        "id": "b9d18258-ac57-42ad-ba9a-ecf48bdff293",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:15:32.291Z"
    },
    {
        "id": "5aaba259-9113-4586-906c-3f0572cfd082",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:15:25.460Z"
    },
    {
        "id": "eaea7d45-2d04-46f7-a4ab-30a57e2080d2",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:13:09.231Z"
    },
    {
        "id": "8e3bab6f-4e56-4a17-b711-d60bdca9645f",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:12:13.095Z"
    },
    {
        "id": "0bc71d9e-0580-4fb2-a883-40833b1fe979",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:11:34.802Z"
    },
    {
        "id": "5b9f56f5-eba0-43e1-852b-3426072dd955",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:10:08.352Z"
    },
    {
        "id": "190f3f20-b344-429d-b965-29c2dd38dde4",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:10:05.915Z"
    },
    {
        "id": "09037b6e-f201-49c5-8137-21a3bad92bc9",
        "title": "surviving maladaptive daydreaming",
        "author": "Farah",
        "genre": "thriller",
        "yearPublished": 2030,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:09:59.257Z"
    },
    {
        "id": "96627eb9-8e15-4e80-873a-a74bf4e77633",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:03:56.951Z"
    },
    {
        "id": "8e222c8e-f269-44bf-88c1-d0df54aa7a34",
        "title": "Queen of dragons",
        "author": "Sree",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T21:00:22.698Z"
    },
    {
        "id": "4b620f7c-e7f4-473e-9c33-938f84366365",
        "title": "kathirina",
        "author": "iraj",
        "genre": "fiction",
        "yearPublished": 2016,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:55:42.123Z"
    },
    {
        "id": "432f4b85-9cd1-44e5-bcec-e04f496fc52a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:50:00.296Z"
    },
    {
        "id": "522b1cc0-01a7-4158-8f33-f5f38f304c4e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:41:50.172Z"
    },
    {
        "id": "06b1e5fb-b7ad-468d-b4c8-cac8a532dab9",
        "title": "becoming",
        "author": "michelle Obama",
        "genre": "biography",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:39:25.013Z"
    },
    {
        "id": "80d52bd2-56cd-4616-bd20-8e69f3a1394b",
        "title": "AI Superpowers",
        "author": "Kai-Fu Lee",
        "genre": "non-fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:34:41.367Z"
    },
    {
        "id": "146d7796-68a9-4338-b1d4-19aac67783de",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:30:54.179Z"
    },
    {
        "id": "0dfceb23-236c-474c-ae31-c1cb4d6e955a",
        "title": "madol duwa",
        "author": "anuga mindinu",
        "genre": "fiction",
        "yearPublished": 1967,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:29:07.058Z"
    },
    {
        "id": "386b2cb6-a69f-4402-b3d4-fcb646fcda60",
        "title": "Ram",
        "author": "Amish Tripathi",
        "genre": "mythological-fiction",
        "yearPublished": 2015,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:27:54.530Z"
    },
    {
        "id": "e902062e-d8ca-48d2-bace-d110bfadc837",
        "title": "I Will Teach You to Be Rich",
        "author": "Ramit Sethi",
        "genre": "nonfiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:22:59.251Z"
    },
    {
        "id": "a68e13ae-b8e2-4cc7-a2d2-955ef168ba94",
        "title": " To Kill a Mockingbird 3da parte ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:17:11.218Z"
    },
    {
        "id": "aeada711-c8ba-487c-9438-8e3b10881a3c",
        "title": "half girlfriend",
        "author": "chetan Bhagat",
        "genre": "romance",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:16:10.920Z"
    },
    {
        "id": "420ca972-ae18-45c1-a6cc-d3885bebc518",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:13:21.441Z"
    },
    {
        "id": "fe5ccb8c-f7dd-47c1-907a-c10c5f563877",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T20:09:34.025Z"
    },
    {
        "id": "fbc294e8-34b6-4426-9fa9-42beaf0358cc",
        "title": "Shoe Dog",
        "author": "Phil Knight",
        "genre": "non-fiction",
        "yearPublished": 2016,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:59:42.976Z"
    },
    {
        "id": "3000826d-7c0d-4d4c-b4d1-4d36ba63f35f",
        "title": "Build: An Unorthodox Guide to Making Things Worth Making",
        "author": "Tony Fadell",
        "genre": "non-fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:57:09.880Z"
    },
    {
        "id": "556c9e3d-898c-428b-b54e-8a42b661e7fe",
        "title": "I Will Teach You to Be Rich",
        "author": "Ramit Sethi",
        "genre": "nonfiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:52:58.125Z"
    },
    {
        "id": "3ed621f5-6e51-4865-8aa3-2884b5e319dd",
        "title": " To Kill a Mockingbird 2da parte ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:49:28.934Z"
    },
    {
        "id": "f7f96d04-0bab-4f58-ad3f-255e2f467337",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:41:47.419Z"
    },
    {
        "id": "dfb09f9f-9353-4f28-84bc-d164ef018e39",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:41:05.403Z"
    },
    {
        "id": "e5cb464b-f987-4e98-b15d-736f6d84644c",
        "title": " To Kill a Mockingbird 2da parte ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:32:09.934Z"
    },
    {
        "id": "ae1f1bf6-754a-4750-9828-9b45735aaf0f",
        "title": " To Kill a Mockingbird 2da parte ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:31:44.344Z"
    },
    {
        "id": "6c3b266d-ed52-4d76-86a2-645517c1e1b0",
        "title": "The dark walk",
        "author": "Nithin",
        "genre": "horror",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:03:50.511Z"
    },
    {
        "id": "465100ac-6e07-4e8c-b06b-65e66c014f54",
        "title": "A Song of Ice and Fire",
        "author": "George R R Martin",
        "genre": "fiction",
        "yearPublished": 2011,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T19:01:33.869Z"
    },
    {
        "id": "46379b35-4477-4840-bfbc-0993a459777e",
        "title": "Diary of a Wimpy Kid:Double Down",
        "author": "Jeff Kinney",
        "genre": "fiction",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:50:18.763Z"
    },
    {
        "id": "09bc2149-0ba2-4db5-9270-7c95a5c2001a",
        "title": "The dark walk",
        "author": "Nithin",
        "genre": "horror",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:50:08.489Z"
    },
    {
        "id": "7074f340-ed3b-4359-a270-5cf740c1692f",
        "title": "Pinocchio",
        "author": "Carlo Collodi",
        "genre": "Novel",
        "yearPublished": 1883,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:49:48.349Z"
    },
    {
        "id": "d290fd41-c7c3-4328-b2fb-eed70f3b5f56",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:48:53.888Z"
    },
    {
        "id": "c5c83945-92c8-4bd0-8960-70d27eacf558",
        "title": "A Song of Ice and Fire",
        "author": "George R R Martin",
        "genre": "fiction",
        "yearPublished": 2011,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:46:38.815Z"
    },
    {
        "id": "a097b882-a3a7-4100-a6bd-1f89e5c362f0",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:44:42.353Z"
    },
    {
        "id": "c0423f12-c10d-49f8-b1bb-310e2cf06265",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:41:38.498Z"
    },
    {
        "id": "9516a004-1199-4d34-837b-e4fe7a4cfdaf",
        "title": "Diary of a Wimpy Kid:Long Haul",
        "author": "Jeff Kinney",
        "genre": "fiction",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:39:17.059Z"
    },
    {
        "id": "1995a05f-eadd-44e4-bbc5-dc122adf8c8d",
        "title": "Dance Of Dragons",
        "author": "George R R Martin",
        "genre": "fiction",
        "yearPublished": 2011,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:38:34.858Z"
    },
    {
        "id": "8a07f59c-1913-4e48-a426-c82212fb817e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:36:34.458Z"
    },
    {
        "id": "4ebef89a-6b3e-4dbe-885d-6e08166b3ef6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:36:30.598Z"
    },
    {
        "id": "b5d021bc-bd23-4533-b9bf-99595745a4b3",
        "title": "The dark walk",
        "author": "Nithin",
        "genre": "horror",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:36:19.451Z"
    },
    {
        "id": "74cc6097-a43c-44b2-8b6c-c9c0c55c021f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:35:35.250Z"
    },
    {
        "id": "1c83d0a1-895d-4f97-ab65-12887e6c46c6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:35:04.380Z"
    },
    {
        "id": "e9d2f6c8-5f0c-4aa7-9327-d26cdc7b0b6f",
        "title": "Harry potter",
        "author": "J K Rowling",
        "genre": "Fantasy",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:33:26.263Z"
    },
    {
        "id": "e46e11b6-5f6f-4d7c-8f5a-b740359d7cf3",
        "title": "Diary of a Wimpy Kid:Rodrick Rules",
        "author": "Jeff Kinney",
        "genre": "fiction",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:33:06.408Z"
    },
    {
        "id": "1e3149bb-9ec4-4b54-ac2c-4d16d12034c3",
        "title": "The fault in our stars",
        "author": "John Green",
        "genre": "fiction",
        "yearPublished": 2012,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:30:01.208Z"
    },
    {
        "id": "0f1ab3d6-64be-4e46-ba1c-c379b41531ec",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:29:39.524Z"
    },
    {
        "id": "eed961e9-ecf7-424a-aa1e-fa139b7098bb",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:29:00.277Z"
    },
    {
        "id": "51f1e159-10f4-4fbf-a4a2-33b179c46143",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:28:59.917Z"
    },
    {
        "id": "2f8c8291-655b-497c-bcf0-d66716929386",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:28:13.143Z"
    },
    {
        "id": "7f16958a-100a-465e-96f5-be4c7e376d74",
        "title": "The dark walk",
        "author": "Nithin",
        "genre": "horror",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:27:53.024Z"
    },
    {
        "id": "4ef2cfd1-8dd0-433b-9c78-d6c232e6eef6",
        "title": "Wings of Fire",
        "author": "A.P.J.Abdul Kalam",
        "genre": "Autobiography",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:25:40.016Z"
    },
    {
        "id": "5ecaee81-789a-44d7-b335-338500a0a67a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:25:30.289Z"
    },
    {
        "id": "557c35e3-d089-43e0-aa61-91b1fa08850f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:24:46.563Z"
    },
    {
        "id": "33b171fb-0920-4326-9803-40fd22eeff2c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:24:21.534Z"
    },
    {
        "id": "ed8dedfe-1313-42a0-9f95-c1bf5b7d7b7e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:24:20.597Z"
    },
    {
        "id": "f2014da9-948f-430d-b06c-7952a80daf42",
        "title": "Wings of Fire",
        "author": "A.P.J.Abdul Kalam",
        "genre": "Autobiography",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:21:15.390Z"
    },
    {
        "id": "344a2f74-e1d4-4609-b2a7-82f5dd909e1d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:21:04.603Z"
    },
    {
        "id": "30b412f8-6b48-45dd-ab92-5236e9e32d87",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:19:23.990Z"
    },
    {
        "id": "6291d4ed-4fcf-41be-89ec-0d3465080a02",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:19:15.985Z"
    },
    {
        "id": "5f099585-abbb-46f6-8f53-34ea8a5c52cd",
        "title": "Reminders of Him",
        "author": "Colleen Hoover",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:18:25.757Z"
    },
    {
        "id": "b0cc0f60-28ba-41e9-8d4d-b6edac355b9f",
        "title": "little things",
        "author": "sree",
        "genre": "drama",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:16:44.378Z"
    },
    {
        "id": "5ed9274e-b45d-4249-aaee-1bb18efcb0c4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:12:09.837Z"
    },
    {
        "id": "4f985b51-c490-4c6d-9c35-5dcf250535b7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:11:54.084Z"
    },
    {
        "id": "b12151fb-88ea-4db5-ad49-f16322d26f06",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T18:01:01.589Z"
    },
    {
        "id": "018d8a95-9e66-4c8b-bcdc-8cfac435f692",
        "title": " To Kill a Mockingbird 2da parte ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:55:07.335Z"
    },
    {
        "id": "072e4d12-4753-467c-afd0-e435881f9ce7",
        "title": "the secret",
        "author": "loki",
        "genre": "action",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:54:11.885Z"
    },
    {
        "id": "5dd6ef1b-1aa4-4da2-b5a0-34ecc05a5760",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:51:44.922Z"
    },
    {
        "id": "8e766390-d203-408d-940f-ac03ae7daf62",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:50:19.635Z"
    },
    {
        "id": "e72a48bf-c574-4f59-a261-00c7b4eb73ba",
        "title": "Goosbumps",
        "author": "R L Stine",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:48:17.441Z"
    },
    {
        "id": "8cd4de08-d516-49cd-9113-940e2b85ecb8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:48:02.581Z"
    },
    {
        "id": "75f9d6e1-55c3-4b7c-b8c1-191eed2c32ad",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:44:43.091Z"
    },
    {
        "id": "9de5cb3a-e20b-4fb7-aa98-70decd083b44",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:44:00.160Z"
    },
    {
        "id": "637c4423-38b2-4929-ae68-410937205b31",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:43:57.105Z"
    },
    {
        "id": "ea792535-288f-4bd2-85ae-d759f8f30a73",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:40:45.649Z"
    },
    {
        "id": "2a6c4cc6-0047-400d-a880-fb5a4b14f6cf",
        "title": "Harry Potter",
        "author": "J K Rowling",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:40:38.821Z"
    },
    {
        "id": "76e30d29-41d9-4ce8-bf96-e12baa6f7efd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:38:52.767Z"
    },
    {
        "id": "52d03e19-d8f2-41a3-a1d0-12f05f75b1d7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:38:44.940Z"
    },
    {
        "id": "96af1597-4470-40ab-9718-bb769b40da82",
        "title": "To Kill a banana",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1980,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:35:49.879Z"
    },
    {
        "id": "b905fe33-80b5-429a-a409-69e59b2c010d",
        "title": " Mockingbird",
        "author": "Harpe",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:18:19.543Z"
    },
    {
        "id": "b48fdc45-602c-48bd-aae0-c9d79623b949",
        "title": "Immortals of Meluha",
        "author": "Amish",
        "genre": "Fiction",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:17:18.857Z"
    },
    {
        "id": "a4a17108-539b-4937-b224-96722dfd3724",
        "title": "ATOMIC HABITS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:16:59.820Z"
    },
    {
        "id": "ceaccc96-038f-40c0-8e77-5f72af10c8a9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:11:58.224Z"
    },
    {
        "id": "0501e84b-1691-4397-9395-d4ea2b068146",
        "title": "ATOMIC HABITS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:11:12.779Z"
    },
    {
        "id": "c47e1886-713e-4a21-a1dc-e8c82d8a8415",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:10:23.700Z"
    },
    {
        "id": "23401602-da03-4b61-bdd4-68b93a43a607",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:09:23.091Z"
    },
    {
        "id": "ba5f614b-613f-4a39-ba90-6b2925a5ef44",
        "title": "ATOMIC HABITS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:06:16.446Z"
    },
    {
        "id": "7986ef8b-b965-4d4e-80f1-2a5acd7ef70e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:05:39.537Z"
    },
    {
        "id": "31a341f6-8156-4793-82cf-0f215772b558",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:04:46.658Z"
    },
    {
        "id": "be003e12-9013-4705-bcc9-ffac7677eaaa",
        "title": "Aadujeevitham",
        "author": "Beenyamin",
        "genre": "Fiction",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:04:22.314Z"
    },
    {
        "id": "325c9045-40ef-4ade-826f-0b280cb1aafa",
        "title": "nadim",
        "author": "Nadim Naisam",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:04:10.921Z"
    },
    {
        "id": "1975a8a4-634a-4ab6-bfc0-07c006d5031f",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:03:52.094Z"
    },
    {
        "id": "b10075a6-651c-416a-b9a3-1f4349489cfc",
        "title": "War and Peace ",
        "author": "Leo Tolstoy",
        "genre": "Historical Fiction",
        "yearPublished": 1865,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:02:52.899Z"
    },
    {
        "id": "fa339db6-c79f-41b4-aa52-0adb956c641b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:01:55.041Z"
    },
    {
        "id": "d978ad99-9bf0-4edd-8c0b-ef48d6a564bf",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:01:35.593Z"
    },
    {
        "id": "1ebfad05-1791-43a1-8319-b1996283e6d8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T17:00:14.363Z"
    },
    {
        "id": "abb173d5-8388-45c3-a2af-5ea2bbecbae4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:59:56.108Z"
    },
    {
        "id": "6eb5c90e-f863-4baf-8b06-4348aca4a1e3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:57:40.347Z"
    },
    {
        "id": "cfc729e7-e970-439f-bab6-e034d074d131",
        "title": "Wings of Fire",
        "author": "APJ",
        "genre": "Auto Biography",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:57:38.294Z"
    },
    {
        "id": "66e92007-c07e-48a0-88cf-1a8c93b5bf11",
        "title": "sarathi",
        "author": "sarathi",
        "genre": "bio",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:55:14.140Z"
    },
    {
        "id": "1e933832-4c29-499d-b531-2bd2cc4f1094",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:54:47.194Z"
    },
    {
        "id": "a0382001-dfc4-4a47-9bc3-46c62212672d",
        "title": "nadim",
        "author": "Nadim Naisam",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:51:09.371Z"
    },
    {
        "id": "b8c25065-fbc1-48ee-82e1-f2c42d36d009",
        "title": "Harry Potter",
        "author": "J.K. Rowling",
        "genre": "fantasy",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:46:59.198Z"
    },
    {
        "id": "88e3355f-19a0-40a5-9dc0-2d614024b93b",
        "title": "A study in scarlet",
        "author": "Arthur Conan Doyle",
        "genre": "fiction",
        "yearPublished": 1887,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:44:32.527Z"
    },
    {
        "id": "1b54b0b6-b283-4a8b-b02d-c9bb583189e6",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:43:06.789Z"
    },
    {
        "id": "4baeac5d-208e-40d6-abf8-e81492a9269b",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:36:45.108Z"
    },
    {
        "id": "c30d6aab-3dce-4cdb-a8eb-dd940c624370",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:35:32.999Z"
    },
    {
        "id": "0be423a9-c8fd-4a5e-8533-23b74c36e32d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:34:52.024Z"
    },
    {
        "id": "8f660193-f87a-4957-88ef-71a2bd04a070",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:33:59.476Z"
    },
    {
        "id": "9756ba69-41e0-436d-b555-1ef3878af19c",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:30:54.924Z"
    },
    {
        "id": "1d48cc91-996d-4002-a5f7-61ff50056bca",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:28:54.900Z"
    },
    {
        "id": "4da2bd22-3903-4fe2-be20-9271a58acdbb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:24:27.736Z"
    },
    {
        "id": "689e540a-3ec4-4839-a378-4443cd665a27",
        "title": "DS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:24:09.812Z"
    },
    {
        "id": "f09c433e-7b07-4f6d-9288-092c46b841c7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:20:58.251Z"
    },
    {
        "id": "40e04f4c-ba38-472b-b31a-90e3cb8b331f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:20:46.983Z"
    },
    {
        "id": "e49762d7-66af-4512-984c-5aa2c31b0ff0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:12:52.604Z"
    },
    {
        "id": "dca387a6-ddf1-4baf-bfe8-bae0af3777f7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:12:43.357Z"
    },
    {
        "id": "29a3acbc-ced5-44ba-9458-24c6d8380f98",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:11:21.664Z"
    },
    {
        "id": "51b171ff-b16c-427f-a81d-f0170881d6e7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:11:11.076Z"
    },
    {
        "id": "be2f46f7-0c32-43be-b3c3-fcc1caedac02",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:08:12.899Z"
    },
    {
        "id": "c3d5527e-3527-4479-836d-b6b2416c6b73",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:08:10.175Z"
    },
    {
        "id": "03e3722e-bbde-41c2-9603-4ac009b3814d",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T16:06:36.949Z"
    },
    {
        "id": "34135af6-9dac-4cae-81a8-1aff9edb3f19",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:57:42.782Z"
    },
    {
        "id": "ac3f7334-142d-4eeb-9b48-52494ddc0f8d",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:56:37.550Z"
    },
    {
        "id": "5ebd609a-0815-407e-b0c9-76433fd7a7ce",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:53:28.430Z"
    },
    {
        "id": "72d2ce05-9b48-49c5-aeec-106f225f4c79",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:50:02.896Z"
    },
    {
        "id": "6bda95e9-4588-463f-b655-7bdc7569b2c0",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:48:53.690Z"
    },
    {
        "id": "14dc83b1-51d0-4590-894a-6107e9019226",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:45:53.655Z"
    },
    {
        "id": "03c96028-6322-4c87-9a70-ad96726c0a63",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:44:40.817Z"
    },
    {
        "id": "1d7f63f5-8004-4c5b-a825-63fc649d01bc",
        "title": "How over the Rainbow",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:36:32.236Z"
    },
    {
        "id": "4860e6af-5648-4bec-8f96-8fa192e0ef06",
        "title": "To be A Girl",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:34:39.442Z"
    },
    {
        "id": "02061ce6-362d-4fa4-8685-8ddf415ea731",
        "title": "To Kill a Mockingbird",
        "author": "Harper ",
        "genre": "fiction",
        "yearPublished": 1961,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:32:47.898Z"
    },
    {
        "id": "fd1b648b-8d4b-4889-9592-14012d112c38",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:31:19.123Z"
    },
    {
        "id": "c4dfdc32-c04f-4ad9-97af-551df7c33074",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:31:16.191Z"
    },
    {
        "id": "97efdef4-3233-4a51-b2e4-3a6ef68fae39",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:31:12.936Z"
    },
    {
        "id": "efef03a9-8778-43dc-82e0-f0e566600b1e",
        "title": "kick",
        "author": "me",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:31:09.501Z"
    },
    {
        "id": "3dce81dc-581d-4b61-8806-d22a862f6d1a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:30:54.552Z"
    },
    {
        "id": "385e2626-a88c-47d1-b044-a0ec361a883e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:30:50.699Z"
    },
    {
        "id": "acbd0095-c23a-40da-851f-fdae8ceffcb1",
        "title": "To Kill a Mockingbird New",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:28:09.606Z"
    },
    {
        "id": "124c05e0-1d04-4b53-a32f-20f36b6753a2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:27:56.802Z"
    },
    {
        "id": "ed0c3f4e-b128-4292-b0a9-480024ee7c90",
        "title": "To Kill a Mockingbird New",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:27:29.024Z"
    },
    {
        "id": "e99b1d43-e981-4a51-9671-e2fa8180f5a2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:24:31.817Z"
    },
    {
        "id": "4a6f918e-ce0a-4298-b165-ffba89102024",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:10:50.221Z"
    },
    {
        "id": "9c47e704-d78f-47c2-830a-54c2080b9d88",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:06:48.342Z"
    },
    {
        "id": "12824b39-3a4e-46f5-8ef2-d9cd6f0f7992",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:05:43.610Z"
    },
    {
        "id": "baab6309-45f7-4fe1-bdad-6167f9c3fe0c",
        "title": "it ends with us",
        "author": "colleen hoover",
        "genre": "romance",
        "yearPublished": 2016,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:01:39.872Z"
    },
    {
        "id": "80d6b6ea-087c-4726-9e37-3aea14326b63",
        "title": "Pride and Prejudice",
        "author": "Jane Austen",
        "genre": "fiction",
        "yearPublished": 1813,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:01:37.808Z"
    },
    {
        "id": "11193804-bc0a-4395-97de-3561c3bfba36",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T15:01:33.380Z"
    },
    {
        "id": "c97bf255-4216-40bb-947d-183e5e2bb6cd",
        "title": "sarathi",
        "author": "sarathi",
        "genre": "bio",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:59:19.995Z"
    },
    {
        "id": "29fb8ad5-b007-49d1-ac0f-68f2d8f06711",
        "title": "Jana",
        "author": "Jana",
        "genre": "bio",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:53:08.794Z"
    },
    {
        "id": "ca7b269f-44de-445b-a8ac-35744cbad917",
        "title": "The Great Gatsby",
        "author": "F.Scott Fitzgerald",
        "genre": "tragedy",
        "yearPublished": 1925,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:52:49.829Z"
    },
    {
        "id": "46a09426-0886-4a21-9a89-f311bacae78b",
        "title": "jujutsu kaisen",
        "author": "gege akutami",
        "genre": "fiction",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:43:18.711Z"
    },
    {
        "id": "11461614-8837-48ad-bec2-427c5c0e751b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:37:38.167Z"
    },
    {
        "id": "8b98c91b-5d6f-47a5-9cf9-7e2c9f80f96d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:21:30.828Z"
    },
    {
        "id": "8a5131df-281b-403c-b0ad-a59f67e87a07",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:18:33.608Z"
    },
    {
        "id": "d5cdfc70-c43a-4d08-a0e7-fdbe370c4b3d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:17:47.809Z"
    },
    {
        "id": "832ccdb1-431d-4bd3-94eb-137aa9d331b3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:15:34.316Z"
    },
    {
        "id": "f850fc5f-767e-42c7-9a4b-17c639402aef",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:14:24.149Z"
    },
    {
        "id": "3c197798-34c4-4436-85ac-b24258998b35",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:11:06.633Z"
    },
    {
        "id": "0ffec75c-1b5d-4aad-a4d5-477441c22159",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:09:07.124Z"
    },
    {
        "id": "c044327f-19ad-4ae4-a4e9-58bdf771750d",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:05:54.230Z"
    },
    {
        "id": "75cc2120-d016-4d97-8c2b-b9f75bb56f56",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T14:01:00.294Z"
    },
    {
        "id": "77582a68-4107-40fd-913b-34c5814f4287",
        "title": "dracula",
        "author": "bram stocker",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:53:12.758Z"
    },
    {
        "id": "0db8d058-b1cb-4824-8f1b-0c17980f9f84",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:52:07.829Z"
    },
    {
        "id": "243e7d0c-d28f-4887-919c-ae0248621dec",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:51:36.817Z"
    },
    {
        "id": "9f3d2869-c972-4384-bce8-cd1f2c4348c2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:48:31.952Z"
    },
    {
        "id": "d0c3fa83-16d4-4b7f-b866-af265dec555b",
        "title": "dracula",
        "author": "bram stocker",
        "genre": "fiction",
        "yearPublished": 1965,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:47:19.844Z"
    },
    {
        "id": "4379dc97-c524-4668-99e0-16b6f927e8f8",
        "title": "ATOMIC HABITS",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:47:19.053Z"
    },
    {
        "id": "91e8668d-97ad-4af2-a8a2-a936f0eec8f2",
        "title": "THE ALCHEMIST",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:46:01.163Z"
    },
    {
        "id": "3913d40c-78fd-475d-870e-9f1a1ae4ae57",
        "title": "THE ALCHEMIST",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:44:29.101Z"
    },
    {
        "id": "cacc67ce-ac8e-4090-aa8e-091be27bbbb5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1965,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:39:38.611Z"
    },
    {
        "id": "fa1791df-2875-4050-9cd9-9ffc410f140b",
        "title": "Science is a flying bird",
        "author": "Siddharth",
        "genre": "ski-fi",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:31:16.624Z"
    },
    {
        "id": "b70e8192-a37f-4498-b82a-60fe742d5f3d",
        "title": "Science is a flying bird",
        "author": "Siddharth",
        "genre": "ski-fi",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:31:14.802Z"
    },
    {
        "id": "40b66323-c050-4fae-817c-6da625257638",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:31:09.361Z"
    },
    {
        "id": "d6ac88b7-7e8b-4df1-953a-7e57f6c4be98",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:29:22.103Z"
    },
    {
        "id": "6cacda2c-c494-4408-b6bd-860ffb9ff3fa",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:27:34.853Z"
    },
    {
        "id": "4c825cd8-10d2-4d19-801a-0ca68772daf7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T13:22:57.082Z"
    },
    {
        "id": "64e14150-3eae-4d74-8d47-8b67bdd818f9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:59:02.247Z"
    },
    {
        "id": "68d945c5-ebf9-41ae-8be7-9ade3355df18",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:47:20.655Z"
    },
    {
        "id": "ce9a2aab-fce1-47b9-bc08-ee22ad45a6d0",
        "title": "Rich Dad Poor Dad",
        "author": "Robert T. Kiyosaki",
        "genre": "Literacy",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:46:53.483Z"
    },
    {
        "id": "202fd8ec-57f2-4bf4-b34c-428395dab985",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:46:29.498Z"
    },
    {
        "id": "46071ffe-e9a0-4f8f-b9cc-887c877a816a",
        "title": "Rich Dad Poor Dad",
        "author": "Robert T. Kiyosaki",
        "genre": "Literacy",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:45:54.891Z"
    },
    {
        "id": "5202e407-714c-4fc8-ab9a-1cfbd6a127d0",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:44:27.557Z"
    },
    {
        "id": "d90df067-34c0-4bfe-abfe-384a5d93ec31",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:44:16.684Z"
    },
    {
        "id": "d2193dab-4e9f-4250-b19c-022e93fe2dff",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:42:48.599Z"
    },
    {
        "id": "d9368b37-23ca-463b-9d7c-a0fa2d6f132a",
        "title": "Love Hypothethis",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:35:44.949Z"
    },
    {
        "id": "5ad829c0-42b1-47d3-8ffb-3969ad09781a",
        "title": "Rich Dad Poor Dad",
        "author": "Robert T. Kiyosaki",
        "genre": "Literacy",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:34:43.210Z"
    },
    {
        "id": "ab565e5e-152c-4212-b123-09412b145127",
        "title": "friendhip is a flying bird",
        "author": "siddharth",
        "genre": "bromance",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:27:56.688Z"
    },
    {
        "id": "5da2e12e-4f0e-46ad-98ca-7f17cd2ab2f0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:23:39.997Z"
    },
    {
        "id": "e1a913ca-eae6-489a-b38c-2c4a1e00157c",
        "title": "The light we carry",
        "author": "Michelle Obama",
        "genre": "bio",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:22:25.592Z"
    },
    {
        "id": "8b0ea325-d1c4-4acf-bad6-ad8257331356",
        "title": "Love is a flying bird",
        "author": "siddharth",
        "genre": "romance",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:17:06.035Z"
    },
    {
        "id": "d55e1a35-edf2-46d2-9d08-ca7dbd54a14e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:17:01.975Z"
    },
    {
        "id": "ab55267b-04bd-436e-8669-ce3fe09452d9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:10:53.275Z"
    },
    {
        "id": "942ca867-084f-43f9-84fb-b8c1a4af3a6a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:09:39.915Z"
    },
    {
        "id": "685113c7-3de2-4d8a-96cc-307341b30e1d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:04:25.692Z"
    },
    {
        "id": "2da16f48-25d0-46b0-b34a-ea4f5dde0251",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:03:50.507Z"
    },
    {
        "id": "518696cb-bd9b-4118-bdeb-dd926769a4e7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T12:03:14.181Z"
    },
    {
        "id": "a6c29a67-9d2c-414b-8200-088dcbe59c24",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:54:59.573Z"
    },
    {
        "id": "7c4a229e-6b58-43e0-8aa7-4f2a4f10c94d",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:53:51.863Z"
    },
    {
        "id": "2d0c6970-fc4e-4518-a968-33a7130056b4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:53:14.916Z"
    },
    {
        "id": "5d42588d-f98a-4bb2-a6e2-2199d3c316c5",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:52:12.628Z"
    },
    {
        "id": "1aa4be34-a976-4df6-bf2f-3968effbc5de",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:51:02.221Z"
    },
    {
        "id": "0ab7e4fd-2b8d-4fad-96e0-18c50afb2862",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:49:56.026Z"
    },
    {
        "id": "b67ce9c7-90a7-4c0d-a08a-1dc69a7c4391",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:48:59.974Z"
    },
    {
        "id": "a8d0e860-fe51-4f8e-9565-67bf4554c54d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:45:34.298Z"
    },
    {
        "id": "686f78eb-8ce1-4015-a113-2ce429c89d1c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:32:10.030Z"
    },
    {
        "id": "5a008397-9091-4102-b6c3-9334d536b4dd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:29:53.405Z"
    },
    {
        "id": "09d7b9b4-b580-46e5-abda-9218c14e220a",
        "title": "To Kill a Mockingbird",
        "author": "Faiz",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:29:10.439Z"
    },
    {
        "id": "d15671fe-c37b-4c41-a9c8-2f9c7f505e91",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:29:10.167Z"
    },
    {
        "id": "20d532e5-46b5-4072-95e0-3d67cb0e1481",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:28:20.452Z"
    },
    {
        "id": "03cbee97-d260-4fee-affd-4b3e2e05b833",
        "title": "The Art of Living",
        "author": "Grant Snider",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:28:16.678Z"
    },
    {
        "id": "b827ce38-3cef-46bb-8132-6beb30454bd2",
        "title": "Dit is nog een boek",
        "author": "Bruce Lee",
        "genre": "fiction",
        "yearPublished": 1987,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:28:13.266Z"
    },
    {
        "id": "04bba900-a37e-4955-9f8d-fdec31bb011d",
        "title": "To Kill a Mockingbird",
        "author": "Faiz",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:27:49.579Z"
    },
    {
        "id": "9c0eb038-43f0-4fa7-9def-f8ef76b79aca",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:27:49.312Z"
    },
    {
        "id": "a65dd928-7846-442b-988f-abded2de6b4d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:27:12.172Z"
    },
    {
        "id": "abe087ab-4e03-4b8a-a987-b0e8935f6168",
        "title": "The Game of Thrones",
        "author": "George R Martin",
        "genre": "fantasy",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:17:44.546Z"
    },
    {
        "id": "d53abd19-2272-4bb1-9fa2-9c1cbc089a00",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:16:52.427Z"
    },
    {
        "id": "95b13589-559c-4222-bd4f-3c95e4d6d4a4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:16:40.712Z"
    },
    {
        "id": "723f7b9a-a4a2-48a0-a0a1-95e5bea53aba",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:15:43.967Z"
    },
    {
        "id": "11d67c7e-e7b5-49c0-84de-33ad56367ee4",
        "title": "To Kill a Mockingbird",
        "author": "Faiz",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:14:02.567Z"
    },
    {
        "id": "29c2ee7b-25be-4928-b471-9d389be30624",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:08:53.219Z"
    },
    {
        "id": "e4a3f361-dac8-4b77-8ba4-2155252c36a6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T11:05:44.368Z"
    },
    {
        "id": "7e49895a-a284-4f1c-ac29-4e381d49b692",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:58:27.012Z"
    },
    {
        "id": "fb373b2c-0e3c-4775-b71f-4d7536f33474",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:57:16.731Z"
    },
    {
        "id": "d7334b55-f1e5-412a-86d5-d5f6c78f951d",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:49:08.659Z"
    },
    {
        "id": "d788a6a7-f11c-467b-a38b-7938d1853638",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:45:40.380Z"
    },
    {
        "id": "fe07a53e-5676-49fe-90b9-2c36895c790b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:44:07.595Z"
    },
    {
        "id": "d937c0ce-05f6-468c-897d-f4b5d46daca4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:43:34.659Z"
    },
    {
        "id": "d8e030b1-f3d7-49da-b736-00c483540104",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:42:59.568Z"
    },
    {
        "id": "8220f71d-55f2-4555-92a7-5b91cbdfc196",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:42:29.722Z"
    },
    {
        "id": "5bedac9b-4ad7-4389-94cc-dcdb94986ca3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:42:21.750Z"
    },
    {
        "id": "51d03481-5339-4a39-ada9-ac7a99ccb959",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:41:06.116Z"
    },
    {
        "id": "b89ddf0d-b6cf-4508-a88a-bd9511a9c455",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:55.819Z"
    },
    {
        "id": "637764c0-19e6-46fd-84f1-ccd086a23e10",
        "title": " MHA",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:55.657Z"
    },
    {
        "id": "b21bdbb6-dfa8-4301-8bfd-7c14916cae73",
        "title": "MHA",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:49.175Z"
    },
    {
        "id": "182b4d17-ccb0-4893-8e39-c25d75861442",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:47.663Z"
    },
    {
        "id": "aaa7a7f8-21aa-4fc0-bb9b-091665901115",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:42.006Z"
    },
    {
        "id": "992a7068-658b-48d9-bb05-687b70339561",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:29.543Z"
    },
    {
        "id": "707ad1af-a7d3-42ed-bb90-e17545826d7d",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:19.841Z"
    },
    {
        "id": "5ab86e1c-4884-49ea-a0b7-9d7991ea1b41",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:12.700Z"
    },
    {
        "id": "c2a4ccc5-e45c-4065-a707-741c36db602d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:04.476Z"
    },
    {
        "id": "fcf015d1-0e85-4441-8c8d-383845eaacbc",
        "title": "dkd",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:02.657Z"
    },
    {
        "id": "49d95d60-d659-40f8-8bbc-d647454bdbae",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:40:02.083Z"
    },
    {
        "id": "acb35c8e-60aa-46d6-bff3-da42e8cd2599",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:39:29.648Z"
    },
    {
        "id": "e3a31b93-e681-412e-a6ec-d04b3e3aa6dd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:39:26.006Z"
    },
    {
        "id": "67802a35-5716-45cb-8144-15fd2a3b1116",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:39:17.002Z"
    },
    {
        "id": "1aad80ed-24f8-4de7-8b02-d69874dbfdee",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:39:07.729Z"
    },
    {
        "id": "9de59491-3a33-492f-8c1e-c19bd86d2b41",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:38:58.206Z"
    },
    {
        "id": "7da2531b-62e5-4b92-a4d0-a9c4505ba82b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:38:37.285Z"
    },
    {
        "id": "e7fea55a-9101-416e-b1c9-b28079ab886d",
        "title": "one pieced",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:38:14.523Z"
    },
    {
        "id": "64efa452-c5e1-4944-b8b0-da8ae04507b5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:38:13.096Z"
    },
    {
        "id": "30373f6f-a2ab-4279-ae6a-6df6e722e156",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:38:10.595Z"
    },
    {
        "id": "27d4c940-1f10-4c04-b12c-fbc580aa7940",
        "title": "Dragon Ball Z",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:37:53.845Z"
    },
    {
        "id": "8f58c032-41f7-4997-ac11-e57f725aa707",
        "title": " JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:37:36.095Z"
    },
    {
        "id": "6a744335-20cd-4fef-8e26-07c72ff42831",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:35:57.424Z"
    },
    {
        "id": "604293cb-d0f0-4e36-9f84-07418182b52d",
        "title": "Atomic Habits",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:35:54.267Z"
    },
    {
        "id": "6945aee4-902c-4f1f-9770-3c8a3a5cb759",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:47.570Z"
    },
    {
        "id": "31464e87-8250-4a4b-870b-222bc0ee7728",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:45.167Z"
    },
    {
        "id": "b65076b0-9826-4a17-a737-c188bce7c607",
        "title": "Atomic Habits",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:44.659Z"
    },
    {
        "id": "22a2f1e7-7dc9-4957-9d2d-de2fdb16d5e2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:33.157Z"
    },
    {
        "id": "42b2609a-931a-4ae3-a345-55165fa2338c",
        "title": "one pieced",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:22.188Z"
    },
    {
        "id": "45149f95-f2a8-461e-9947-d00328c5aef4",
        "title": "JJK",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:34:20.459Z"
    },
    {
        "id": "2e9bdf05-60b9-4147-a50a-8fa519b35310",
        "title": "The Jungle Book",
        "author": "Rudyard Kipling",
        "genre": "fiction",
        "yearPublished": 1894,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:33:50.487Z"
    },
    {
        "id": "b61a026d-51d4-4b38-8db4-b3796c893b98",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:33:50.081Z"
    },
    {
        "id": "3ef33b67-fe3a-4cc5-91bc-687706927531",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:33:44.697Z"
    },
    {
        "id": "3c2bd8dc-6aa2-405c-bf90-ec0f1cef4837",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:33:22.059Z"
    },
    {
        "id": "b73aa63c-0dc5-49c1-b492-6895420f461a",
        "title": "Weird Stuff",
        "author": "Richard Tulloch",
        "genre": "fantasy",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:32:10.755Z"
    },
    {
        "id": "f51c2bef-417a-4833-a888-cf92bad220c7",
        "title": "The Jungle Book",
        "author": "Rudyard Kipling",
        "genre": "fiction",
        "yearPublished": 1894,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:31:37.660Z"
    },
    {
        "id": "ecdd51bb-418c-4653-8d1c-2a17101a9f41",
        "title": "Dit is een boek",
        "author": "Tom Carpenter",
        "genre": "roman",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:17:46.506Z"
    },
    {
        "id": "649f3fcd-51c6-4958-ba8c-c277b622e14c",
        "title": "Pathummede aadu",
        "author": "Vaikom Muhammad Basheer",
        "genre": "fiction",
        "yearPublished": 1959,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:15:02.472Z"
    },
    {
        "id": "d04af20f-c3a8-45bd-b113-a15797dad8a1",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:10:54.642Z"
    },
    {
        "id": "5c170f41-f8a1-467f-9bd6-943d30e7243b",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:08:39.234Z"
    },
    {
        "id": "2a15c9e7-dd11-43b8-ab5b-401216b74359",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "fiction",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:06:33.786Z"
    },
    {
        "id": "1bfdc4ce-57c3-4e93-a710-7dc9537beafd",
        "title": "Certified Wireless Design Professional",
        "author": "Tom Carpenter",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:03:46.542Z"
    },
    {
        "id": "bc8d0d13-eebc-4312-b2d5-8c6bbe4dccfb",
        "title": "The intelligent investor",
        "author": "Harshitha",
        "genre": "Documentory",
        "yearPublished": 2001,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T10:00:44.519Z"
    },
    {
        "id": "0cb14b7b-3f4a-4123-9c58-fd99bf120c11",
        "title": "Unser Wildes Erbe",
        "author": "Peter Wohlleben",
        "genre": "documentation",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:53:44.498Z"
    },
    {
        "id": "7966f09f-842e-40c3-8edc-164075a9cdf3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:51:01.803Z"
    },
    {
        "id": "888866ce-8ed0-4e74-ab0d-533e0b7a4b0d",
        "title": "Aadujeevitham",
        "author": "Benyamin",
        "genre": "fiction",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:50:30.154Z"
    },
    {
        "id": "57234424-81e9-4637-8e84-5d53b9af31b9",
        "title": "The Jungle Book",
        "author": "Rudyard Kipling",
        "genre": "Fiction",
        "yearPublished": 1894,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:49:57.006Z"
    },
    {
        "id": "200edb19-7aed-4a07-a090-627d6d5698a9",
        "title": "Weird Stuff",
        "author": "Richard Tulloch",
        "genre": "fantasy",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:49:41.441Z"
    },
    {
        "id": "8e6cc117-f6b4-467e-ba15-68bff8b5da35",
        "title": "Manjaveyil Maranangal",
        "author": "Benyamin",
        "genre": "thriller",
        "yearPublished": 2017,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:41:51.175Z"
    },
    {
        "id": "bffdb8b1-6ae5-49c5-bcfd-5420ed30e397",
        "title": "The secret life of trees",
        "author": "Peter Wohlleben",
        "genre": "documentation",
        "yearPublished": 2015,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:41:25.262Z"
    },
    {
        "id": "c9cda498-f49f-4115-a1d6-72383c1e54b4",
        "title": "Eve's Diary",
        "author": "Mark Twain",
        "genre": "Humor",
        "yearPublished": 1905,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:39:30.285Z"
    },
    {
        "id": "d8587535-d5de-4cf6-8cd9-b82630802a1b",
        "title": "Jujutsu Kaisen",
        "author": "Gege Akutami",
        "genre": "fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:39:07.669Z"
    },
    {
        "id": "80e4ab50-9f56-4c7d-928b-ebe90dd5ada9",
        "title": "Weird Stuff",
        "author": "Richard Tulloch",
        "genre": "fantasy",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:33:18.767Z"
    },
    {
        "id": "a5ddccbd-9061-4f20-9c3d-415d7a4f4cb3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:31:20.884Z"
    },
    {
        "id": "5a0628a0-4302-4c1d-9cf7-9343547bdcf4",
        "title": "My fault",
        "author": "Mercedes Ron ",
        "genre": "fiction",
        "yearPublished": 2017,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:29:55.435Z"
    },
    {
        "id": "bbbd792f-1ba0-47fc-8810-53f443369357",
        "title": "The Oath of the Vayuputras",
        "author": "Amish Tripathi",
        "genre": "Fantasy Fiction",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:23:14.907Z"
    },
    {
        "id": "2d661625-ecf5-4955-9e0c-b5471d814df4",
        "title": "Eve's Diary",
        "author": "Mark Twain",
        "genre": "Humor",
        "yearPublished": 1905,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:19:29.383Z"
    },
    {
        "id": "9b2ea3d3-ff18-432f-ad94-b579e9c42620",
        "title": "Eve's Diary",
        "author": "Mark Twain",
        "genre": "Humor",
        "yearPublished": 1905,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:18:53.805Z"
    },
    {
        "id": "6ed89f31-fc0d-4a11-ac81-ba6854936e10",
        "title": "Alchemist",
        "author": "Paulo Coelho",
        "genre": "fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:18:12.480Z"
    },
    {
        "id": "bcf17904-4781-4c80-8a2b-04d368d09b26",
        "title": "Bittersweet",
        "author": "Susan Cain",
        "genre": "nonfiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:17:01.731Z"
    },
    {
        "id": "1381957a-d666-4236-9033-544a496da8d5",
        "title": "Sita-Warrior of Mithila",
        "author": "Amish Tripathi",
        "genre": "Mythological Fiction",
        "yearPublished": 2017,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:09:48.410Z"
    },
    {
        "id": "1c68a534-d126-4838-ae36-70ccdb9e1b46",
        "title": "Dracula",
        "author": "Bram Stoker",
        "genre": "fiction",
        "yearPublished": 1897,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:05:41.059Z"
    },
    {
        "id": "58da309b-ec72-4995-ab3c-c249ddb5c5b4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:04:08.820Z"
    },
    {
        "id": "b40ed1e8-c4f0-4fb4-b9e3-1d9a5c308d3a",
        "title": "Catch-22",
        "author": "Joseph Heller",
        "genre": "fiction",
        "yearPublished": 1961,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:02:03.625Z"
    },
    {
        "id": "2745c03e-7b9b-4241-af4d-2b967e614d0c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T09:00:44.455Z"
    },
    {
        "id": "49ce9e56-b023-4859-b14e-465bc389fe42",
        "title": "City Under One Roof ",
        "author": "Iris Yamashita",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:57:20.669Z"
    },
    {
        "id": "cc066afe-658c-4d84-929e-9c2540c05c72",
        "title": "The Adventures of Sherlock Holmes",
        "author": "Arthur Conan Doyle",
        "genre": "Novel",
        "yearPublished": 1892,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:55:30.084Z"
    },
    {
        "id": "85e42789-a30e-4da5-9ee8-925e9bf501a4",
        "title": "City Under One Roof ",
        "author": "Iris Yamashita",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:54:46.759Z"
    },
    {
        "id": "b7a4e9ea-7ff3-4d0a-b156-e03df8919274",
        "title": "Dracula",
        "author": "Bram Stoker",
        "genre": "fiction",
        "yearPublished": 1897,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:53:02.090Z"
    },
    {
        "id": "d12d382e-324b-48ff-8444-871c3849411f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:44:22.373Z"
    },
    {
        "id": "f552346f-17b6-47e8-aa8e-eec21dcf825f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:43:48.454Z"
    },
    {
        "id": "bc06e8c0-9627-4f6d-b954-a0bbb5471e3f",
        "title": "The Doomsday Conspiracy",
        "author": "Sidney Sheldon",
        "genre": "Fiction",
        "yearPublished": 1991,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:41:28.173Z"
    },
    {
        "id": "fc6a670f-a9d8-4f08-8d89-ad219f898a0f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:41:13.343Z"
    },
    {
        "id": "63377396-8b14-41b3-9f8a-1bec4b06cfd4",
        "title": "The Doomsday Conspiracy",
        "author": "Sidney Sheldon",
        "genre": "Fiction",
        "yearPublished": 1991,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:39:42.812Z"
    },
    {
        "id": "e823119f-e044-49bb-962c-d5b51749cc82",
        "title": "The Richest Man in Babylon",
        "author": "George Samuel Clason",
        "genre": "self-help book",
        "yearPublished": 1926,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:36:38.322Z"
    },
    {
        "id": "0b656142-19c6-46c2-8a48-91e993edd597",
        "title": "The Richest Man in Babylon",
        "author": "George Samuel Clason",
        "genre": "self-help book",
        "yearPublished": 1926,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:35:50.338Z"
    },
    {
        "id": "bd8c6a1d-2168-41bb-be64-f5f157587ecc",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:34:40.554Z"
    },
    {
        "id": "b671d8db-7d7d-40ae-95f3-8ae5601c884c",
        "title": "Ugly love",
        "author": "Colleen hoover",
        "genre": "fiction",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:34:16.212Z"
    },
    {
        "id": "64f75941-b936-41f1-b562-f4701e344d74",
        "title": "Divergent",
        "author": "Veronica Ruth",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:33:51.444Z"
    },
    {
        "id": "2f37d39b-9f35-45f5-a91a-f04929b5ad82",
        "title": "The Richest Man in Babylon",
        "author": "George Samuel Clason",
        "genre": "self-help book",
        "yearPublished": 1926,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:33:17.723Z"
    },
    {
        "id": "6e1b7a39-e6b4-45cd-94d0-effc87fa0b16",
        "title": "The Monk Who Sold His Ferrari",
        "author": "Robin Sharma",
        "genre": "Fiction",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:32:14.359Z"
    },
    {
        "id": "269682b1-ff39-49f0-aec5-e3621a4b4a9a",
        "title": "The Richest Man in Babylon",
        "author": "George Samuel Clason",
        "genre": "self-help book",
        "yearPublished": 1926,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:31:07.649Z"
    },
    {
        "id": "8dbd7731-ad17-4486-81eb-a196ef075ce3",
        "title": "Goat Days",
        "author": "Benyamin",
        "genre": "novel",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:29:52.781Z"
    },
    {
        "id": "0cb816e2-8945-485d-ab72-2c82ad3c1904",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "Classic Narrative",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:24:52.606Z"
    },
    {
        "id": "8c64f9d3-6cc6-46d7-875e-d86a34f66a20",
        "title": "Goat Days",
        "author": "Benyamin",
        "genre": "novel",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:24:29.237Z"
    },
    {
        "id": "3e31db04-6344-4782-b948-cd7ddb8d8230",
        "title": "802.11n A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2012,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:22:42.098Z"
    },
    {
        "id": "cfed9920-6790-419d-8aec-6d3d3010b30c",
        "title": "Goat Days",
        "author": "Benyamin",
        "genre": "novel",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:19:36.641Z"
    },
    {
        "id": "4aca8717-4fff-45a1-b130-c9160b25a98e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:18:15.160Z"
    },
    {
        "id": "a6bf7d2d-e3dd-4765-a26a-429b4e5375c1",
        "title": "Things Fall Apart",
        "author": "Chinua Achebe",
        "genre": "Classic Narrative",
        "yearPublished": 1958,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:17:19.167Z"
    },
    {
        "id": "a1737dcf-e8fb-4490-bef9-3a5a210af91f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:15:50.257Z"
    },
    {
        "id": "a98bad01-0ade-4cc4-8056-df2529f4348e",
        "title": "Goat Days",
        "author": "Benyamin",
        "genre": "novel",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:05:52.332Z"
    },
    {
        "id": "3bcfc953-b988-4944-84b8-139bb5e5688c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:04:00.286Z"
    },
    {
        "id": "62f63424-fb9f-4005-9f15-9e6ef1ded051",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:03:48.539Z"
    },
    {
        "id": "ecec32ee-c32e-47e7-a815-bf5a19a62728",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T08:02:06.489Z"
    },
    {
        "id": "13f4a046-d544-454a-8b37-9b62209f4a3f",
        "title": "Goat Days",
        "author": "Benyamin",
        "genre": "novel",
        "yearPublished": 2008,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:59:37.391Z"
    },
    {
        "id": "16e828fe-3299-4384-af92-259250166a79",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:58:04.612Z"
    },
    {
        "id": "785c21bf-5595-4e9f-b424-a40503f237b1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:54:19.190Z"
    },
    {
        "id": "d9496945-3fa9-4845-8f67-d6ef512cfcf1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:54:06.543Z"
    },
    {
        "id": "99ece48e-1928-4357-87e8-7de2d80c2eea",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:51:54.869Z"
    },
    {
        "id": "b5621b8f-3602-4fa4-bea8-735af95247b5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:51:42.845Z"
    },
    {
        "id": "29fed81e-807f-4a20-86a8-a99d0a88e94e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:49:40.894Z"
    },
    {
        "id": "c929495d-4cd6-4621-877c-f1d2deecb494",
        "title": "wings of fire",
        "author": "abdul kalam",
        "genre": "thriller",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:38:52.920Z"
    },
    {
        "id": "2e4195a9-f413-4359-9e77-153c8440998b",
        "title": "Harry Potter",
        "author": "JK Rowling",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:30:33.297Z"
    },
    {
        "id": "787a7739-d1e2-415b-b94b-f6723418ad38",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:30:22.731Z"
    },
    {
        "id": "7dd205f9-cd74-4605-abaa-f4cfc1582cf2",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure,fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:29:50.490Z"
    },
    {
        "id": "2811834b-baca-4caa-bdad-3617cc29d95c",
        "title": "twisted series",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:22:20.696Z"
    },
    {
        "id": "195046f4-574f-4ee5-b969-ceca279ddcc5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:20:54.979Z"
    },
    {
        "id": "7c2af9fb-df2f-4d2d-a965-50a78554c4b5",
        "title": "twisted games",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:19:23.548Z"
    },
    {
        "id": "bb553f1f-ca89-47aa-b3ad-588d863c6148",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:18:50.477Z"
    },
    {
        "id": "b8334dc4-7607-4416-8437-31d09c8c6f68",
        "title": "twisted games",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:16:49.973Z"
    },
    {
        "id": "e6413734-5111-47b3-9ee3-e76ec5c3300c",
        "title": "Rich dad, Poor son",
        "author": "Aditya Paliwal",
        "genre": "fiction",
        "yearPublished": 1999,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:14:32.015Z"
    },
    {
        "id": "f477781f-c4e2-4780-aea6-f9ecc8f5edc2",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure,fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:14:02.627Z"
    },
    {
        "id": "1771f5a6-8bae-49fe-ad3f-d303bc61c7f9",
        "title": "Rich dad, Poor son",
        "author": "Aditya Paliwal",
        "genre": "fiction",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:11:45.492Z"
    },
    {
        "id": "cc35614f-3b88-44d8-8ad1-fbd45ea1839c",
        "title": "The Blue Umbrella",
        "author": "Ruskin Bond",
        "genre": "fiction",
        "yearPublished": 1974,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:11:26.788Z"
    },
    {
        "id": "80e3248b-5458-4950-9e8e-a286e60a7432",
        "title": "Rich dad, Poor son",
        "author": "Aditya Paliwal",
        "genre": "fiction",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:11:06.766Z"
    },
    {
        "id": "cece58a9-f57b-41dc-b5be-9c0fdf1a64fc",
        "title": "Fue un privilegio estar aqui",
        "author": "Melva Frias Vda. Carrillo",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:06:21.564Z"
    },
    {
        "id": "211b3956-3b60-46c0-bcea-5547b9a71da7",
        "title": "Las sagas de Potter",
        "author": "Josepi LucasMoi",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:06:19.223Z"
    },
    {
        "id": "05bb2765-d1f5-4491-9df5-f3944dbd05c5",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:05:55.807Z"
    },
    {
        "id": "da906446-0e28-438a-9f4c-b204659a5bdf",
        "title": "Tempora *** hic. Omnis sed voluptatum odio corporis ***. Est quas itaque commodi animi voluptatum. Aut earum quo id itaque aut porro in adipisci eaque. Nobis ad rerum modi.",
        "author": "Kelly Glover",
        "genre": "tech",
        "yearPublished": 86,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:05:23.436Z"
    },
    {
        "id": "7cd351a2-777c-4c91-bf1c-d771fde6a232",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure,fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:04:38.680Z"
    },
    {
        "id": "f548842e-3d5d-4a91-ae38-d816cee67cc6",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:04:26.954Z"
    },
    {
        "id": "0bdf4ef4-4652-4274-80c9-5d6050591666",
        "title": "The Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure ``fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:03:45.665Z"
    },
    {
        "id": "3398e563-7276-4187-8f08-06cd23940968",
        "title": "twisted games",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:01:06.286Z"
    },
    {
        "id": "99353d21-63a3-4cec-9f58-2f028a90bf39",
        "title": "De-engineered systematic support",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T07:00:24.396Z"
    },
    {
        "id": "16380e97-a4b2-46e0-8dda-1fb847257f6e",
        "title": "twisted games",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:59:45.235Z"
    },
    {
        "id": "62a7826a-8f3b-429e-8136-8f1f459f7ade",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:55:11.796Z"
    },
    {
        "id": "75cf7672-7770-4ee6-971c-1d461e01cf70",
        "title": "king of wrath",
        "author": "ana huang",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:52:18.471Z"
    },
    {
        "id": "b821b737-3d7e-4768-b382-bc4123ade83c",
        "title": "Wings of Fire",
        "author": "Dr. A P J Abdul Kalam",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:52:02.595Z"
    },
    {
        "id": "c3c4a8ad-1dde-4f71-b59c-6231354430f1",
        "title": "geronimo stilton",
        "author": "geronimo stilton",
        "genre": "fantasy",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:45:24.508Z"
    },
    {
        "id": "3d1c1349-b46c-4b62-ac20-b972a339411c",
        "title": "Wings of Fire",
        "author": "Dr. A P J Abdul Kalam",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:43:03.531Z"
    },
    {
        "id": "cfcaec48-ddf4-489a-adb8-65e206a95df3",
        "title": "geronimo stilton",
        "author": "geronimo stilton",
        "genre": "fantasy",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:32:38.944Z"
    },
    {
        "id": "80466da0-fdab-4055-87eb-242521f21218",
        "title": "Global",
        "author": "Ahzem",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:26:27.757Z"
    },
    {
        "id": "1ac488f8-1d53-472d-80b7-e304f9d338d0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:25:35.895Z"
    },
    {
        "id": "eaac025a-e933-4408-b7c2-fc16a852811c",
        "title": "Exploring IT Professions Worldwide",
        "author": "Ahzem",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:18:21.889Z"
    },
    {
        "id": "ee48ffd7-79f5-4447-9a1d-51c6f1151c19",
        "title": "To Kill A Mocknight Bird",
        "author": "Herper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:15:30.633Z"
    },
    {
        "id": "53b1503d-b0bd-4c7e-ad73-d2106141ceb9",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:14:53.534Z"
    },
    {
        "id": "d93b2d6d-0895-47db-8bf0-f271b7e9c4e8",
        "title": "Exploring IT Professions Worldwide",
        "author": "Ahzem",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:13:51.745Z"
    },
    {
        "id": "e72d7a27-a175-4586-a1f4-170c4d9eef9f",
        "title": "The Book Thief",
        "author": "Markus Zusak",
        "genre": "Novel",
        "yearPublished": 2005,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:12:58.531Z"
    },
    {
        "id": "24142115-9c32-4ba9-aa57-3dbb9e2b82c7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:10:14.601Z"
    },
    {
        "id": "d170e07f-f977-49eb-b41d-067de9e3b1b0",
        "title": "And the Mountains Echoed",
        "author": "Khaled Hosseini",
        "genre": "Novel",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:09:46.912Z"
    },
    {
        "id": "b72ca5a1-c015-43c7-a6af-e29ad442b22c",
        "title": "Hyperion",
        "author": "Dan Simmons",
        "genre": "fiction",
        "yearPublished": 1989,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:09:33.417Z"
    },
    {
        "id": "8abf312b-7074-491d-91af-6be859bc67f3",
        "title": "The Alchemists",
        "author": "Pablo Coelo",
        "genre": "fiction",
        "yearPublished": 2002,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:07:02.937Z"
    },
    {
        "id": "c5317576-0dd4-4586-9376-d75e97e86942",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:06:56.677Z"
    },
    {
        "id": "ced5e8f8-5d32-4cbb-8bfe-d7863e5162a6",
        "title": "The Alchemist",
        "author": "Pablo Coelo",
        "genre": "fiction",
        "yearPublished": 2002,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:03:08.537Z"
    },
    {
        "id": "b93f17ea-7c08-4ffd-9449-91dbc4cc7739",
        "title": "Wuthering Heights",
        "author": "Emily Bronte",
        "genre": "Novel",
        "yearPublished": 1847,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:02:16.372Z"
    },
    {
        "id": "e1892a87-b04d-4907-beb4-f804eb8ce9e6",
        "title": "Dolores dolor debitis deserunt. Voluptatum esse quam. Et fuga in et dolore. Exercitationem quia reprehenderit dolorum natus vitae praesentium qui voluptatum. Optio voluptates aut suscipit.",
        "author": "Gene Davis",
        "genre": "tech",
        "yearPublished": 120,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:01:32.835Z"
    },
    {
        "id": "a68b0203-45df-4e20-9547-415e1bf4b1fd",
        "title": "omnis ut repellendus",
        "author": "Gene Kunde",
        "genre": "tech",
        "yearPublished": 177,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:01:32.687Z"
    },
    {
        "id": "64cd504f-a15b-43e6-ba38-b0a59be75465",
        "title": "Rerum sit dolor. Soluta nihil quo omnis nam fugiat cupiditate. Similique architecto atque nemo.",
        "author": "Dianne Witting",
        "genre": "tech",
        "yearPublished": 883,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:01:32.533Z"
    },
    {
        "id": "2933ae18-234c-4f3a-9dee-13785a466043",
        "title": "et",
        "author": "Gwendolyn Prosacco",
        "genre": "tech",
        "yearPublished": 742,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:01:32.349Z"
    },
    {
        "id": "a457d514-2412-4548-930a-9a69cf73e68a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T06:01:01.409Z"
    },
    {
        "id": "6b64b148-c1b4-44d0-93ee-51d5aa03b569",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:59:46.590Z"
    },
    {
        "id": "e3bc181e-2a3c-4eb9-8a11-82887856f24e",
        "title": "To Kill a bird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:56:15.351Z"
    },
    {
        "id": "518f036a-3ee0-470f-9a96-816128162db1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:54:24.473Z"
    },
    {
        "id": "e9afbc2c-0a6a-405f-9770-786bc9449a6e",
        "title": "The Kite Runner",
        "author": "Khaled Hosseini",
        "genre": "Novel",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:49:58.198Z"
    },
    {
        "id": "01c71b1e-a669-41cf-a126-e8df5d42913d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:49:41.154Z"
    },
    {
        "id": "650b7162-7155-4e97-ba7a-7bd5bcb175b4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:43:39.684Z"
    },
    {
        "id": "51ff0a24-ef87-44d8-add9-cdf993650667",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:42:02.131Z"
    },
    {
        "id": "9677dab2-889e-4d33-a101-567f0385832d",
        "title": "To Kill a bird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:33:22.212Z"
    },
    {
        "id": "970c14b2-f476-4309-b817-0ac8f2c3edb0",
        "title": "To Kill a bird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:33:10.174Z"
    },
    {
        "id": "83f46ae7-ab16-433b-ab26-3a32032595ad",
        "title": "To Kill a bird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:32:55.094Z"
    },
    {
        "id": "9847a22f-d984-4eda-9e85-79d3eadad391",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:24:43.688Z"
    },
    {
        "id": "1836a857-edcc-49fa-b26d-e2bf14d2dfdf",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:20:10.746Z"
    },
    {
        "id": "658398e3-78c2-4f2e-a99b-e7fc89420d12",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:18:55.103Z"
    },
    {
        "id": "5da17202-2859-46fa-8cf2-ceffa8e710ee",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:17:25.820Z"
    },
    {
        "id": "eb026e46-a751-4a5b-9615-d844302be0b6",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:12:35.916Z"
    },
    {
        "id": "e360cb61-d7dd-4412-9bb1-be41fc9aa266",
        "title": "To Kill a Mockingbird 3",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:06:12.848Z"
    },
    {
        "id": "d3ab9704-815a-459b-98e4-93c2742b1afa",
        "title": "Nobis quos veniam dolorem eveniet reiciendis expedita odit nobis.",
        "author": "Elmer Ruecker IV",
        "genre": "tech",
        "yearPublished": 952,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:03:30.069Z"
    },
    {
        "id": "3dc13c0a-6807-45d3-96a8-51199ebbb09d",
        "title": "soluta",
        "author": "Mr. Dana Trantow",
        "genre": "tech",
        "yearPublished": 89,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:03:29.957Z"
    },
    {
        "id": "fdcc26f8-5cc5-4f61-a066-73becf1bbeef",
        "title": "Blanditiis ut ratione voluptatem eveniet ut dolor accusantium. Labore excepturi consequatur ut sit. Sunt suscipit ut facilis quia ea facilis.",
        "author": "Holly Nolan",
        "genre": "tech",
        "yearPublished": 978,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:03:29.837Z"
    },
    {
        "id": "28eeb5d3-954e-4964-a085-94761a8f9b8d",
        "title": "voluptatem",
        "author": "Edward Cartwright",
        "genre": "tech",
        "yearPublished": 108,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:03:29.358Z"
    },
    {
        "id": "57306a48-1227-4f0a-bfcb-bb73cffd0348",
        "title": "To Kill a Mockingbird 2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T05:01:28.948Z"
    },
    {
        "id": "f1ccb2ed-b892-4632-94ab-648895f42913",
        "title": "becoming",
        "author": "michelle Obama",
        "genre": "biography",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:58:07.945Z"
    },
    {
        "id": "c112c790-e310-4e66-86f4-808fa503b359",
        "title": "To Kill a Mockingbird 2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:52:51.559Z"
    },
    {
        "id": "b661e3ed-2316-4a69-ab79-6804ddcd1e77",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:46:26.308Z"
    },
    {
        "id": "5f1a8e9d-a140-4135-97d0-0629f927ba2a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:43:43.577Z"
    },
    {
        "id": "c1c1ca71-adb5-4007-a42d-4436bd6deb4e",
        "title": "Pride and Prejudice",
        "author": "Jane Austen",
        "genre": "Novel",
        "yearPublished": 1813,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:28:39.818Z"
    },
    {
        "id": "c64f7355-1c0d-4ed8-a339-008f3b9391d7",
        "title": "Pride and Prejudice",
        "author": "Jane Austen",
        "genre": "Novel",
        "yearPublished": 1813,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:28:07.561Z"
    },
    {
        "id": "486faf42-3a3f-41d1-90f6-2956f3f2a895",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:26:07.445Z"
    },
    {
        "id": "02d1ad55-5a62-4550-8f57-9c60352cf1a3",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:24:13.063Z"
    },
    {
        "id": "54cc61f0-9b14-415c-b728-fc90c9d811ea",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:23:17.311Z"
    },
    {
        "id": "f83e8354-938d-4988-98ef-a2a27e93408b",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:21:44.493Z"
    },
    {
        "id": "c1ac397e-29fc-4986-b24d-bf1582607a05",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:21:17.546Z"
    },
    {
        "id": "7fba8daa-e0dd-4129-9222-3c78e42c1078",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:18:47.096Z"
    },
    {
        "id": "01cbb0d7-b553-4186-9806-348204ba8895",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:18:37.633Z"
    },
    {
        "id": "6c97d166-2896-464a-8249-9722d5d81037",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:18:34.604Z"
    },
    {
        "id": "e5e21415-978b-43cb-9b28-b7f12ca9ba64",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:18:29.629Z"
    },
    {
        "id": "6274de59-67a2-4762-a89c-47dc578f7350",
        "title": "The Pursuit of Happyness",
        "author": "Chris Gardner",
        "genre": "Biography",
        "yearPublished": 2006,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:17:22.086Z"
    },
    {
        "id": "a908dd0d-ffc1-446f-bb9c-2f4987316858",
        "title": "et molestiae mollitia",
        "author": "Neil Howe",
        "genre": "tech",
        "yearPublished": 792,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:04:47.258Z"
    },
    {
        "id": "c0b4e0d4-3c8c-46b2-bf28-7b862e82a6ab",
        "title": "Sit iusto quidem ut magni ipsum est labore. Odit modi magni magni nobis laudantium repellat odio vero. Quidem eos dolorum ipsa. Quia consequuntur qui. Velit sint voluptatem voluptatem autem dolorum cumque ipsa expedita vel.",
        "author": "Mrs. Jasmine Kohler",
        "genre": "tech",
        "yearPublished": 774,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:04:45.785Z"
    },
    {
        "id": "b0ca6f03-8a67-4915-a63a-af3f20acade0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:00:48.836Z"
    },
    {
        "id": "15031bdd-f20f-4ec4-9ae1-469ef50b53fc",
        "title": "A Thousand Splendid Suns",
        "author": "Khaled Hosseini",
        "genre": "Novel",
        "yearPublished": 2007,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:00:31.705Z"
    },
    {
        "id": "f7697178-d1b7-4c9b-a0e2-c7d1d8017898",
        "title": "One Hundred Years of Solitude",
        "author": "Gabriel García Márquez",
        "genre": "Novel",
        "yearPublished": 1967,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:00:31.634Z"
    },
    {
        "id": "f4218eec-e5a9-4c19-9877-4f235669c2fc",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T04:00:13.651Z"
    },
    {
        "id": "3728033c-7c32-4cb3-b563-a093c085107a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:51:52.069Z"
    },
    {
        "id": "16cd72f0-a9e5-4b49-a95d-34404df51d95",
        "title": "To Love is to hate",
        "author": "Vanice Banks",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:31:16.965Z"
    },
    {
        "id": "ec393166-b30c-4fda-bab4-e19496d74e38",
        "title": " The Stranger",
        "author": "Albert Camus",
        "genre": "Philosophical novel",
        "yearPublished": 1946,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:28:13.402Z"
    },
    {
        "id": "59699948-bf0f-47ea-9eb0-fe72159d4d94",
        "title": "To Love is to hate",
        "author": "Vanice Banks",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:17:09.613Z"
    },
    {
        "id": "ccd7e274-cfaf-4f8b-910e-ef2fb9c9fa37",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:06:58.455Z"
    },
    {
        "id": "11122611-b8cd-4d15-840f-7d8dcc4d5026",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:06:09.065Z"
    },
    {
        "id": "2f241fe7-dccd-4c50-b8c5-26bdb0198f2a",
        "title": "Eligendi pariatur voluptatem maiores totam quia error.",
        "author": "Tina Borer",
        "genre": "tech",
        "yearPublished": 55,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:00:32.500Z"
    },
    {
        "id": "ff78f6c9-5711-427f-93f4-c1a967e7dd03",
        "title": "Distinctio quo perspiciatis. Qui est quia officiis sed non reprehenderit hic. Consequatur quaerat cupiditate dolores dolorem. Iusto tempore numquam est expedita expedita. Atque iste quo ullam.",
        "author": "Bridget Kub",
        "genre": "tech",
        "yearPublished": 400,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:00:32.310Z"
    },
    {
        "id": "d13e6e01-8c94-4f8a-8c8d-cca81ad254a1",
        "title": "Perspiciatis possimus ut.",
        "author": "Rosalie Dicki",
        "genre": "tech",
        "yearPublished": 194,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:00:32.069Z"
    },
    {
        "id": "f1990ed0-ef2e-4092-92d6-ea1ad02b122c",
        "title": " The Stranger",
        "author": "Albert Camus",
        "genre": "Philosophical novel",
        "yearPublished": 1946,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T03:00:22.216Z"
    },
    {
        "id": "c089384f-f4dd-4c6b-9462-a9bbcbd15935",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:52:55.933Z"
    },
    {
        "id": "52e84bc6-76b1-4010-b6af-1b31ad948790",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:51:21.378Z"
    },
    {
        "id": "b0c8d456-6f03-4ecb-b146-3081e9cc7a33",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:50:04.285Z"
    },
    {
        "id": "1c21266e-2761-4423-a5b0-e640de1248b3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:38:23.276Z"
    },
    {
        "id": "02c990ec-37ff-403a-8a44-87d946f4bfb0",
        "title": "itaque",
        "author": "Jose Berge",
        "genre": "tech",
        "yearPublished": 860,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:00:30.808Z"
    },
    {
        "id": "c20da0b3-f2cb-42bb-803a-f5d828dd87f9",
        "title": "Non repellat et aut aut. Omnis tempora deleniti eos fugiat libero et non numquam. Aut libero explicabo mollitia officiis. Quia et qui quisquam dolores ut. Eaque impedit ea atque. Quis et quidem eaque.",
        "author": "Ms. Megan Champlin",
        "genre": "tech",
        "yearPublished": 766,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:00:30.605Z"
    },
    {
        "id": "c6899842-74a1-4366-be74-207c0cbd71d4",
        "title": "labore",
        "author": "Victor Price DVM",
        "genre": "tech",
        "yearPublished": 298,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:00:30.388Z"
    },
    {
        "id": "27ac1e07-a435-4795-8730-ad0d6d6efa53",
        "title": "Atque voluptatem qui et qui eaque sed dolor.",
        "author": "Dr. Pablo Luettgen",
        "genre": "tech",
        "yearPublished": 418,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:00:30.278Z"
    },
    {
        "id": "95a88ec8-2dbc-4fd3-afbe-1d81815481d5",
        "title": "autem",
        "author": "Walter Runolfsson",
        "genre": "tech",
        "yearPublished": 16,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T02:00:30.105Z"
    },
    {
        "id": "f81c4836-3203-4dc3-bd50-ac5e83a5a8b5",
        "title": "abirahs dupatha",
        "author": "Silva",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T01:37:19.736Z"
    },
    {
        "id": "2d23fe37-9afe-46a8-935b-c7cb9abd2959",
        "title": "Adipisci debitis ut numquam omnis ut.",
        "author": "Antonia Stamm",
        "genre": "tech",
        "yearPublished": 541,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T01:00:25.014Z"
    },
    {
        "id": "0b2d70f9-eb17-4d68-804a-7b056f6c98b8",
        "title": "Ut in dolorem facilis dolorem. Sit inventore id architecto omnis sed deleniti alias vitae est.",
        "author": "Kenny Rutherford",
        "genre": "tech",
        "yearPublished": 947,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T01:00:24.114Z"
    },
    {
        "id": "94888635-71d3-430b-840e-6be54789a2cb",
        "title": "El Visitante",
        "author": "Stephen King",
        "genre": "Novela",
        "yearPublished": 1985,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T00:58:35.939Z"
    },
    {
        "id": "28ba7748-1286-46a0-b441-be2c45174231",
        "title": "El Código Da Vinci",
        "author": "Dan Brown",
        "genre": "Fiction",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T00:57:09.061Z"
    },
    {
        "id": "73da17f8-1676-42ed-8788-4a150e483f43",
        "title": "Soluta sed porro.",
        "author": "Reginald Homenick DDS",
        "genre": "tech",
        "yearPublished": 434,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T00:01:34.802Z"
    },
    {
        "id": "957eab4a-eff2-4d41-86bd-7c989c78251e",
        "title": "non",
        "author": "Armando D'Amore",
        "genre": "tech",
        "yearPublished": 236,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T00:01:34.715Z"
    },
    {
        "id": "0c07127a-a82f-48a1-a8a5-c13190d9b5dc",
        "title": "Aut porro at accusantium qui animi odio eveniet nobis.",
        "author": "Clarence Walsh",
        "genre": "tech",
        "yearPublished": 790,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-14T00:01:34.621Z"
    },
    {
        "id": "eec32807-1e20-426d-801d-7b541b8f3a5f",
        "title": "Godan",
        "author": "Munsi Premchand",
        "genre": "Drama",
        "yearPublished": 1989,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:37:17.613Z"
    },
    {
        "id": "ac2fc405-5353-4695-aac4-c8ea26cdbd26",
        "title": "Godan",
        "author": "Munsi Premchand",
        "genre": "Drama",
        "yearPublished": 1989,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:36:45.638Z"
    },
    {
        "id": "88c0e94e-9fb5-4e4b-979c-81f6d4a5bb48",
        "title": "Godan",
        "author": "Munsi Premchand",
        "genre": "Drama",
        "yearPublished": 1989,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:36:18.373Z"
    },
    {
        "id": "e082aa9d-8cef-49dc-92cc-74eb8b21f032",
        "title": "et",
        "author": "Mack Koss V",
        "genre": "tech",
        "yearPublished": 864,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:00:55.878Z"
    },
    {
        "id": "23ec37e6-0f97-4084-b967-58625b519ce2",
        "title": "dolores provident veritatis",
        "author": "Dr. Felix Torp",
        "genre": "tech",
        "yearPublished": 284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:00:55.763Z"
    },
    {
        "id": "d44c57e5-f4b4-4943-9f05-672038b62ed1",
        "title": "Et sint in sequi illum. Cumque *** modi quia adipisci.",
        "author": "Willis Nolan DDS",
        "genre": "tech",
        "yearPublished": 688,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:00:55.657Z"
    },
    {
        "id": "d318f383-807e-4033-a574-2ecd0e0a16f0",
        "title": "Animi in saepe reiciendis enim nostrum eveniet.",
        "author": "Oliver Gutmann",
        "genre": "tech",
        "yearPublished": 187,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:00:55.529Z"
    },
    {
        "id": "a08ae96f-15ec-49ad-921f-92eff876bef9",
        "title": "sit",
        "author": "Mark Erdman",
        "genre": "tech",
        "yearPublished": 705,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T23:00:55.390Z"
    },
    {
        "id": "d454d6b8-dc47-48f2-96e1-6d051769f066",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:56:35.434Z"
    },
    {
        "id": "34f98145-9659-4edd-bd34-f0759860f808",
        "title": "kuldeep saini",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:43:56.574Z"
    },
    {
        "id": "35bec504-4fc7-4e6b-8d8f-a88741f4eb5a",
        "title": "kuldeep saini",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:43:27.869Z"
    },
    {
        "id": "1c9673c0-20b7-40f0-8ca8-b5e4c3e2c186",
        "title": "kuldeep saini",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:37:39.072Z"
    },
    {
        "id": "602222ee-cc84-4131-ac4e-a1e2ac2a0b6f",
        "title": "kuldeep saini",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:36:04.951Z"
    },
    {
        "id": "d9079e3a-9f6d-432d-9a25-019dc91c75bd",
        "title": "kuldeep saini",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:31:31.998Z"
    },
    {
        "id": "3d69d311-1bf0-4cef-a96a-457bf8493c14",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:29:15.480Z"
    },
    {
        "id": "4a3273e5-e27d-4584-8e0b-76c619fda04f",
        "title": "voluptas",
        "author": "Franklin Watsica",
        "genre": "tech",
        "yearPublished": 767,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:06:19.803Z"
    },
    {
        "id": "f60eb07d-e692-4394-a96f-760bae9c6fdb",
        "title": "itaque",
        "author": "Katie Barrows",
        "genre": "tech",
        "yearPublished": 448,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:06:19.167Z"
    },
    {
        "id": "cdc36370-94a8-4d11-91e7-c99c93de02c3",
        "title": "aut ullam blanditiis",
        "author": "Theresa Barton",
        "genre": "tech",
        "yearPublished": 340,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T22:06:19.001Z"
    },
    {
        "id": "f6d3a95d-7bb0-4db8-8e84-e363ea04ea2d",
        "title": "The Doomsday Conspiracy",
        "author": "Sidney Sheldon",
        "genre": "Adventure fiction",
        "yearPublished": 1991,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T21:49:21.989Z"
    },
    {
        "id": "fb0eea47-e5b1-41aa-a5db-bda7dd0e658c",
        "title": "The Monk Who Sold His Ferrari",
        "author": "Robin Sharma",
        "genre": "inspirational fiction",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T21:01:04.972Z"
    },
    {
        "id": "ddf3e61d-8b05-49ec-be66-3d68a6191cce",
        "title": "occaecati",
        "author": "Opal Olson",
        "genre": "tech",
        "yearPublished": 285,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T21:00:45.141Z"
    },
    {
        "id": "5bf23a08-3c4c-4d4e-bf4e-0940e0edfd20",
        "title": "Quasi optio quae. Fuga voluptatem necessitatibus voluptas neque ut. Quia maxime et animi reprehenderit quia sed quis voluptatem.",
        "author": "Grant Kihn",
        "genre": "tech",
        "yearPublished": 464,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T21:00:44.951Z"
    },
    {
        "id": "4f133764-7980-422c-853c-07229aed5b79",
        "title": "est",
        "author": "Linda Reichel",
        "genre": "tech",
        "yearPublished": 197,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T21:00:44.723Z"
    },
    {
        "id": "0b142c24-e6b4-4147-8217-f5c613d4e63c",
        "title": "Travle to heaven",
        "author": "Sultan",
        "genre": "Novel",
        "yearPublished": 2011,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:53:14.096Z"
    },
    {
        "id": "81e2eb76-6637-4c9f-89ec-82c23b2f2ab5",
        "title": "Harry Potter",
        "author": "J.K.Rowling",
        "genre": "fantasy literature",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:44:04.358Z"
    },
    {
        "id": "3120c30d-c43b-4a32-a962-608f8b68885c",
        "title": "Seven way to die",
        "author": "Awon Abbas",
        "genre": "Novel",
        "yearPublished": 2010,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:32:53.428Z"
    },
    {
        "id": "c0ccb66b-22d8-4a49-9cd5-ccbc2ecbbbd4",
        "title": "Around the sea",
        "author": "Ali Amjad",
        "genre": "Novel",
        "yearPublished": 1970,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:25:04.340Z"
    },
    {
        "id": "fc44fa4b-eab1-4de2-80ce-73d6f0f13219",
        "title": "Gamperaliya",
        "author": "Gunadasa Kapuge",
        "genre": "Adventure",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:19:33.064Z"
    },
    {
        "id": "916b427b-10b3-4788-8af8-5e3e09ef9a6d",
        "title": "Harry Potter and My Baby Sitter",
        "author": "Anbu",
        "genre": "comedy",
        "yearPublished": 1995,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:18:23.712Z"
    },
    {
        "id": "c86a1476-ee73-4974-9f1d-b26b05e56f5e",
        "title": "mother",
        "author": "Arunodi",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:17:42.971Z"
    },
    {
        "id": "b8c1ac4d-f901-405b-a783-ec4a89b230fa",
        "title": "To Kill a Mockingbird New",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:16:08.305Z"
    },
    {
        "id": "94463fe9-ce2c-4a96-abe6-20b3299242b3",
        "title": "Gamperaliya",
        "author": "Gunadasa Kapuge",
        "genre": "Adventure",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:15:15.883Z"
    },
    {
        "id": "31cf337f-5467-4a20-b9e4-7a887887e6b5",
        "title": "Alchemist",
        "author": "Paulo Coelho",
        "genre": "Adventure fiction",
        "yearPublished": 1988,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:14:59.748Z"
    },
    {
        "id": "f15bcc6c-21d4-4564-b6bf-ae7a4846ddbb",
        "title": "Hath Pana",
        "author": "Kumarathunga Munidasa",
        "genre": "Comedy",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:11:59.912Z"
    },
    {
        "id": "c6400d20-c841-44a8-8551-c5d0354a7ec8",
        "title": "Harry Potter and My Baby Sitter",
        "author": "Anbu",
        "genre": "comedy",
        "yearPublished": 1995,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:10:08.537Z"
    },
    {
        "id": "c81f6fda-a0be-4af9-83e3-191424fd78e9",
        "title": "est exercitationem quibusdam",
        "author": "Ernestine Rosenbaum",
        "genre": "tech",
        "yearPublished": 796,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T20:02:04.309Z"
    },
    {
        "id": "e1fe1ea9-cfc8-4794-895f-7723906819fa",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:49:08.324Z"
    },
    {
        "id": "2e5cf73b-a3e5-43c0-a3a2-73ce2be0eb04",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:42:28.884Z"
    },
    {
        "id": "e1b82649-5b8a-4cee-9ce5-241d7abf39d1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:40:37.795Z"
    },
    {
        "id": "97aac99a-eb3f-4bfa-8d82-dc96358a6e86",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:33:42.244Z"
    },
    {
        "id": "1554e5a6-a2e5-45a2-bb49-663a14484823",
        "title": "Madolduwa",
        "author": "Martin Wickramasinghe",
        "genre": "Adventure",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:32:53.830Z"
    },
    {
        "id": "7c7781b2-d03e-4d4e-b8db-0f069e07bcd5",
        "title": "Madolduwa",
        "author": "Martin Wickramasinghe",
        "genre": "Adventure",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:28:54.631Z"
    },
    {
        "id": "1a3d928d-d675-4c41-a0c8-3667ee9fbc22",
        "title": "Madolduwa",
        "author": "Martin Wickramasinghe",
        "genre": "Adventure",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:27:15.539Z"
    },
    {
        "id": "372491ec-ad8a-498b-a76e-fcb37a01143b",
        "title": "hvhvkhj",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:12:06.008Z"
    },
    {
        "id": "103d3eb7-22fe-4e3d-993c-19036794cb20",
        "title": "The Island",
        "author": "Victoria Hislop",
        "genre": "fiction",
        "yearPublished": 1980,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:08:57.354Z"
    },
    {
        "id": "d47bb02e-466f-410a-8447-fbc21da2c640",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:05:07.941Z"
    },
    {
        "id": "fa43e016-4f55-413e-9434-a1bbcd7cbe6c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:04:24.459Z"
    },
    {
        "id": "64a0b374-af19-45c9-b9e2-2ad75b34ddb4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:02:03.753Z"
    },
    {
        "id": "8900c183-f936-45a6-8d54-086034bb3c0f",
        "title": "Quo ab est officiis aliquam.",
        "author": "Miss Rosie Huels",
        "genre": "tech",
        "yearPublished": 237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:01:19.028Z"
    },
    {
        "id": "4b287310-f992-400c-a44d-ca399ec46cd7",
        "title": "temporibus",
        "author": "Peggy Pollich",
        "genre": "tech",
        "yearPublished": 878,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T19:01:17.585Z"
    },
    {
        "id": "8e441188-7ee2-4c7a-a9d2-d74ee77d05b0",
        "title": "Diary-of-a-young-girl",
        "author": "Anne Frank",
        "genre": "novel",
        "yearPublished": 1980,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:56:01.946Z"
    },
    {
        "id": "488f0a86-029d-4dc2-9095-aa737985ef9b",
        "title": "Diary-of-a-young-girl",
        "author": "Anne Frank",
        "genre": "novel",
        "yearPublished": 1980,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:51:53.548Z"
    },
    {
        "id": "2a01f186-3723-41b2-9d18-008938dfa2ec",
        "title": "To Kill a Mockingbird 2 ",
        "author": "Harper Lee 2",
        "genre": "fiction",
        "yearPublished": 1961,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:51:22.703Z"
    },
    {
        "id": "5a2458d3-58f2-4d10-89cf-fbf17ed9dc10",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:50:59.485Z"
    },
    {
        "id": "ed912b68-d02e-4908-bc2d-1d3af9bdef07",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:49:12.519Z"
    },
    {
        "id": "7548fd37-8474-4601-b57c-30c12be347f2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:48:52.208Z"
    },
    {
        "id": "425ad64f-8a34-409e-8446-ad93f71b286a",
        "title": "Ikigai",
        "author": "Anonymous",
        "genre": "non-fiction",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:48:26.785Z"
    },
    {
        "id": "c70f29e2-3bec-46ba-b150-e08da98d4e8f",
        "title": "Ikigai",
        "author": "Anonymous",
        "genre": "non-fiction",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:47:58.761Z"
    },
    {
        "id": "c1c44d40-4937-497c-af86-c139827b5c27",
        "title": "Ikigai",
        "author": "Anonymous",
        "genre": "non-fiction",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:47:45.678Z"
    },
    {
        "id": "1373c903-dfd9-415f-a8f9-8a16681bee8a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:46:13.602Z"
    },
    {
        "id": "70a560e4-cae2-4ebd-9067-e2961cdf9936",
        "title": "hvhvkhj",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:45:44.513Z"
    },
    {
        "id": "ed3a706b-0202-4c1a-8f66-9f9412f60cc1",
        "title": "Jesus",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:44:47.852Z"
    },
    {
        "id": "e81cb132-c904-4f80-b6d3-dcedc3984d07",
        "title": "Jesus",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:44:41.714Z"
    },
    {
        "id": "3274804e-3ac3-49ff-b304-fb185feb2ad8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:43:59.202Z"
    },
    {
        "id": "54cba6ab-9876-4344-856f-fd0a2ef5c325",
        "title": "The Island",
        "author": "Victoria Hislop",
        "genre": "fiction",
        "yearPublished": 1980,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:42:11.849Z"
    },
    {
        "id": "f1a3d432-02e2-426f-85dd-8bc3c275adb6",
        "title": "To Kill a Mockingbird 2 ",
        "author": "Harper Lee 2",
        "genre": "fiction",
        "yearPublished": 1961,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:38:44.320Z"
    },
    {
        "id": "b87b1237-318e-4869-8881-c87d8c818245",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:34:25.500Z"
    },
    {
        "id": "1c6af265-dbea-4407-8b47-52c9ce975ed9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:31:55.668Z"
    },
    {
        "id": "38bd233c-73ec-4f9b-93de-36c8778d584e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:31:52.568Z"
    },
    {
        "id": "75ec9c16-30e1-4852-b8f2-2b0642196ad3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:29:50.317Z"
    },
    {
        "id": "834c8929-6107-40ea-bc19-0d5c326f8dd0",
        "title": "Sapiens",
        "author": "Yuval Noah",
        "genre": "non-fiction",
        "yearPublished": 2011,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:29:44.318Z"
    },
    {
        "id": "311db349-9371-4433-aa09-004e6bcdfd40",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:26:35.631Z"
    },
    {
        "id": "04d6bfe9-b033-47a7-8a9f-56bfc0208e09",
        "title": "Understanding Chemistry",
        "author": "Ojuwkuku Sr",
        "genre": "fiction",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:20:51.309Z"
    },
    {
        "id": "b1220d0f-215a-4266-99e7-553cb58f6edb",
        "title": "Jesus",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:14:36.837Z"
    },
    {
        "id": "d5ccd3b9-358c-4ed3-913e-1956d6d57739",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:12:49.578Z"
    },
    {
        "id": "d13e165c-c853-4897-8787-88b9dca3abd4",
        "title": "BIG DATA 3",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:12:04.213Z"
    },
    {
        "id": "fd34c5ee-f104-4778-911b-1d2f46f08091",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:08:55.288Z"
    },
    {
        "id": "21e0baed-39f9-4570-b810-3af8c5190fa7",
        "title": "BIG DATA 3",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:06:04.681Z"
    },
    {
        "id": "ee961d37-49f7-4c9f-8f91-9005d0f020ce",
        "title": "Minima illum similique dolor laudantium exercitationem laudantium aut molestiae fugiat.",
        "author": "Darnell Collins",
        "genre": "tech",
        "yearPublished": 327,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:41.741Z"
    },
    {
        "id": "cc64096a-e7ff-4fef-a8b4-d8dffc890fcf",
        "title": "Deserunt debitis quia et.",
        "author": "Thelma Senger PhD",
        "genre": "tech",
        "yearPublished": 575,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:41.678Z"
    },
    {
        "id": "2098d144-9730-4cb9-9d79-fdf6934ec69a",
        "title": "Dolores temporibus minus ut ipsam facilis ipsa reiciendis dolor dolores. Neque cupiditate et amet consequatur ipsum et reiciendis. Ipsa consequatur perspiciatis animi rerum officia. Mollitia est vel et dolore omnis. Et molestias quia ut et.",
        "author": "Rebecca Marquardt",
        "genre": "tech",
        "yearPublished": 403,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:41.608Z"
    },
    {
        "id": "e4bf3b0c-9aae-4d45-9480-4478273fdea2",
        "title": "Accusantium earum et itaque quia quia sit. Qui culpa dolore in tenetur ratione. Ullam quia quo dolorem eius laborum nihil ipsum atque. Consequuntur recusandae maiores suscipit debitis. Perferendis maiores accusantium placeat et atque voluptatem iusto.",
        "author": "Don Schroeder Jr.",
        "genre": "tech",
        "yearPublished": 512,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:41.451Z"
    },
    {
        "id": "a2b01946-ce82-4039-a832-fb0237449417",
        "title": "modi recusandae harum",
        "author": "Rufus Lindgren",
        "genre": "tech",
        "yearPublished": 809,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:41.264Z"
    },
    {
        "id": "167cc73a-054d-463a-8c5d-072075cf92a8",
        "title": "BIG DATA 3",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:05:13.981Z"
    },
    {
        "id": "3394cdf7-fce7-4376-81ce-3b4efcdb6921",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T18:02:56.069Z"
    },
    {
        "id": "b7bb88a8-d835-482d-b381-1a1ea4b09cd2",
        "title": "Jane Eyre",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:58:39.133Z"
    },
    {
        "id": "2c39c73b-493e-46a8-94c9-ff5e8bfa9024",
        "title": "How to win friends and influene people",
        "author": "Dale Carnegie",
        "genre": "religion",
        "yearPublished": 1936,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:53:53.244Z"
    },
    {
        "id": "604728a7-751f-48e5-8688-070902430ba1",
        "title": "Bhagwad Gita",
        "author": "Gita Press",
        "genre": "religion",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:49:38.485Z"
    },
    {
        "id": "9cc7c0dd-79aa-4e28-a0b3-dcc5531d41e3",
        "title": "Sahil khilari ",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:42:46.071Z"
    },
    {
        "id": "0d01447e-b5c3-4cc4-8768-583726b692ea",
        "title": "Sahil khilari ",
        "author": "Harper Lee",
        "genre": "horror",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:30:07.127Z"
    },
    {
        "id": "20d3f800-ff27-408f-84df-4ff4ab05d55b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:28:01.720Z"
    },
    {
        "id": "f7974662-10d4-4866-9dfd-bd2b2a8cdb5c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:20:42.077Z"
    },
    {
        "id": "38fabc58-7f8d-4cf6-9a30-ebb3f64d46da",
        "title": "Ikigai",
        "author": "Anonymous",
        "genre": "non-fiction",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:07:17.158Z"
    },
    {
        "id": "6bd308f1-b8ca-4e99-b4e5-f4adf46e401d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:06:11.195Z"
    },
    {
        "id": "34be4ada-2975-4659-a8fc-a1b6cca424d8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:06:07.388Z"
    },
    {
        "id": "4b4f03d8-7664-4394-af95-a054fb8e2010",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:06:05.900Z"
    },
    {
        "id": "b70a86e4-7960-4b5d-8e5b-859498ce3601",
        "title": "architecto",
        "author": "Amy Casper",
        "genre": "tech",
        "yearPublished": 840,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:02:10.406Z"
    },
    {
        "id": "d44aabf7-70be-4ce3-968b-e0d3e4b1cf58",
        "title": "Eius animi eum in.",
        "author": "Ida Hudson",
        "genre": "tech",
        "yearPublished": 222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:02:10.283Z"
    },
    {
        "id": "e4b02af0-1c5f-4888-bc1d-d3fc5b69b6cf",
        "title": "Dolores autem dolorum dolores quas aut est beatae. Molestias et totam magnam adipisci est. Corrupti et soluta. Id ipsum nulla repellat sed id. Deserunt eius et fugit qui sint doloribus a.",
        "author": "Ms. Marcia Vandervort",
        "genre": "tech",
        "yearPublished": 706,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:02:10.137Z"
    },
    {
        "id": "b48a6983-9c6a-41ad-9e55-670cf2906006",
        "title": "Quas est dicta et qui dicta voluptatum velit eligendi.",
        "author": "Brandi Pfeffer",
        "genre": "tech",
        "yearPublished": 773,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:02:09.904Z"
    },
    {
        "id": "7678feb7-4e85-4728-9439-71ff7ea20e61",
        "title": "labore et atque",
        "author": "Miss Phil Mann",
        "genre": "tech",
        "yearPublished": 347,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T17:02:09.699Z"
    },
    {
        "id": "0d5dec1f-c232-4dce-8811-2b978feb5de4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:56:48.797Z"
    },
    {
        "id": "05d122ca-097f-4cdf-b16d-a2272773d69f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:56:40.071Z"
    },
    {
        "id": "581f2fa1-cb82-477f-ac5b-136c79bcb17d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:56:38.084Z"
    },
    {
        "id": "0db39e94-6843-4538-9321-3d19ca789b67",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:56:36.073Z"
    },
    {
        "id": "a798e9e0-bf9f-474a-bb6a-92224e45a5cb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:49:59.687Z"
    },
    {
        "id": "4c63c097-8d0b-4117-85a9-cb773136ac7b",
        "title": "To Kill",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1961,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:49:19.026Z"
    },
    {
        "id": "05bbdeed-7112-4751-9ec0-4b30aabe932a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:48:03.697Z"
    },
    {
        "id": "a5051b2d-0a6d-424d-bc4d-f61e4b629b4b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:46:08.234Z"
    },
    {
        "id": "d0a6acb6-44d3-408b-8b02-4fd9b25e014a",
        "title": "Hyperion",
        "author": "Dan Simmons",
        "genre": "fiction",
        "yearPublished": 1989,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:39:34.316Z"
    },
    {
        "id": "11b3e80b-da86-4f31-97bd-6488b2ce7dd2",
        "title": "Jesus",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:37:29.642Z"
    },
    {
        "id": "0735da74-1bd8-4fae-9c26-5499618404b9",
        "title": "Astrophysics for people in a hurry",
        "author": "Neil degrasse tyson",
        "genre": "science",
        "yearPublished": 2016,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:37:10.402Z"
    },
    {
        "id": "7976f3bf-2f66-4243-b256-7511f824a223",
        "title": "Inferno",
        "author": "Dan Brown",
        "genre": "fiction",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:35:39.486Z"
    },
    {
        "id": "1844b364-77fa-4f16-99e8-4c609479ff65",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:27:08.933Z"
    },
    {
        "id": "dee2966e-6d64-4f15-83a7-d161c24820b5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:26:50.652Z"
    },
    {
        "id": "577b0ae3-a0aa-4ebb-bbb4-e5372f5ad193",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:26:44.463Z"
    },
    {
        "id": "e8e06424-d39f-429f-a80d-882ae8955f5f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:23:56.017Z"
    },
    {
        "id": "ecb4d1b0-9213-494e-9d30-936b327ee97c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:23:18.970Z"
    },
    {
        "id": "a2920b6c-f50e-4f32-9426-e66f2c33db00",
        "title": "Jesus",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:20:08.936Z"
    },
    {
        "id": "3e8ba1af-ed9c-4f82-aac5-4a431cbdbc97",
        "title": "Astrophysics for people in a hurry",
        "author": "Neil degrasse tyson",
        "genre": "science",
        "yearPublished": 2016,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:19:33.926Z"
    },
    {
        "id": "e7c55c8c-f83e-41e7-afe4-53e810c3d970",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:14:33.148Z"
    },
    {
        "id": "cd615037-7e62-484c-8dca-bb02e56b1050",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:13:26.533Z"
    },
    {
        "id": "295cd91f-0265-4672-90cb-56eb361be49b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:11:45.843Z"
    },
    {
        "id": "f0703ee5-a271-432e-a7ac-8981203d1eef",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:08:45.030Z"
    },
    {
        "id": "b1f86cc2-78c1-401c-9e92-a2bd68fc5aac",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:08:15.536Z"
    },
    {
        "id": "939bad9e-a785-4568-9b16-9e95d27cfd49",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:07:39.569Z"
    },
    {
        "id": "72630f6f-023c-43c2-8596-72636ab6d34f",
        "title": "Tenetur eos iusto fugiat inventore debitis similique ullam voluptatem.",
        "author": "Johanna Hoppe",
        "genre": "tech",
        "yearPublished": 222,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:04:58.357Z"
    },
    {
        "id": "4bd984e2-bdbd-4666-af9b-5053703f7255",
        "title": "Dicta quasi qui.",
        "author": "Cody Flatley",
        "genre": "tech",
        "yearPublished": 375,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:04:58.282Z"
    },
    {
        "id": "0a53f062-fa72-4522-a854-620a2f271876",
        "title": "Quibusdam suscipit aut. Ab enim qui. *** consectetur quod mollitia quibusdam soluta. Maiores blanditiis dolore ipsa.",
        "author": "Harry Cremin",
        "genre": "tech",
        "yearPublished": 323,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:04:58.211Z"
    },
    {
        "id": "9efc1fe6-4074-4e85-a3fa-d5a25de4206e",
        "title": "Omnis tempore adipisci nisi est vitae eos eveniet.",
        "author": "Darrell O'Kon Jr.",
        "genre": "tech",
        "yearPublished": 500,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:04:58.129Z"
    },
    {
        "id": "5b2332b8-b3e5-4a9e-861c-c4102c0cd522",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:02:25.338Z"
    },
    {
        "id": "999caccd-a605-43ee-bbf8-2ad32d149a44",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T16:02:23.176Z"
    },
    {
        "id": "5b72925a-74a8-4c2d-a528-bef861cd757c",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:59:41.702Z"
    },
    {
        "id": "d05411a3-3d2b-49be-99c9-2d784484436b",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:49:35.657Z"
    },
    {
        "id": "87b5b58c-44f0-4c28-a5a8-dbba1e0e45f6",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:49:03.836Z"
    },
    {
        "id": "92f40c77-d2bd-41cd-b67d-bca6afa6fa1d",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:46:09.832Z"
    },
    {
        "id": "5eb87ff0-7ec2-4d7c-ad33-d35fbce6ec3c",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:44:53.690Z"
    },
    {
        "id": "d8bcb659-46e1-490f-baff-c6d8ea4d16cb",
        "title": "BIG DATA",
        "author": "SYL",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:40:54.177Z"
    },
    {
        "id": "0fd97312-a366-4795-9b07-3e1380431885",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1965,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:26:55.288Z"
    },
    {
        "id": "806989be-82c0-4f50-8d7d-8d91ff2caf41",
        "title": "QARMY´s book",
        "author": "Dinno",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:24:15.480Z"
    },
    {
        "id": "8564b3f3-3881-4914-8be2-6f2328f8a295",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:24:04.870Z"
    },
    {
        "id": "60287c32-da56-4f17-9f4a-dd6cb87a7c21",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:23:33.054Z"
    },
    {
        "id": "5a3e29a1-7a3e-41a9-8ed6-99acabbe632f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:20:11.975Z"
    },
    {
        "id": "5f697b7b-ab2f-4e6e-b506-74cc9c9d5ba2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1965,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:20:00.609Z"
    },
    {
        "id": "72656c5d-79bc-4a76-bcc5-0e26acf0362e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1965,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:18:52.208Z"
    },
    {
        "id": "4861eb94-44c3-42d4-82d8-2eb4603d8572",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:15:38.034Z"
    },
    {
        "id": "97397274-2754-43dc-8dbb-a8ee3c2d89c3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:14:45.566Z"
    },
    {
        "id": "f21e66ab-fbf9-4be4-b727-f5c2c841a2f1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:14:35.763Z"
    },
    {
        "id": "ed7de74d-2738-41d1-b449-046f2406e04b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:13:05.771Z"
    },
    {
        "id": "f4ed2384-f12a-4e42-b168-94ffe6145224",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:11:15.833Z"
    },
    {
        "id": "98f78cd7-2c6f-46e9-99aa-da19e73f723b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:11:02.549Z"
    },
    {
        "id": "5101ed52-ab66-4605-ba13-ff37cb6d1030",
        "title": "To Kill a Mockingbird",
        "author": "Harper ",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:10:53.271Z"
    },
    {
        "id": "669c6745-eca5-4cb4-9116-2112db5b9016",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:10:21.316Z"
    },
    {
        "id": "08632a6a-3dbf-441c-8c75-658aa86f02c9",
        "title": "KM_Book_1",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:04:54.711Z"
    },
    {
        "id": "3bc9f3b5-259d-49a4-aa9c-b270ea1c050a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:04:23.667Z"
    },
    {
        "id": "21263c96-2d36-4be2-99d7-45726e8e17c6",
        "title": "Porro quo nam sit minima suscipit. Asperiores magni quibusdam est quis exercitationem enim voluptas occaecati. Similique et nisi in.",
        "author": "Reginald Kemmer",
        "genre": "tech",
        "yearPublished": 388,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:01:36.826Z"
    },
    {
        "id": "37579bcb-4d28-4e11-a456-f96623d76e9d",
        "title": "A dolorum voluptas.",
        "author": "Martin Green IV",
        "genre": "tech",
        "yearPublished": 708,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:01:36.531Z"
    },
    {
        "id": "ceab0d7f-c106-425e-84b1-bdebea4d2435",
        "title": "Sit velit omnis repudiandae. Et facilis placeat quidem. Aspernatur cumque harum porro dolores cupiditate expedita. Iusto delectus sit aut odio a et dicta veritatis qui. Adipisci et laboriosam. Ut ad officiis dolorum et.",
        "author": "Jeannette Paucek",
        "genre": "tech",
        "yearPublished": 754,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T15:01:36.419Z"
    },
    {
        "id": "2b49a4df-dffc-4e9d-97ba-f98a41f018bc",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:53:09.647Z"
    },
    {
        "id": "da0c9dab-943e-4d1c-a156-8d1d87a3b055",
        "title": "KM_Book_1",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:52:14.197Z"
    },
    {
        "id": "b1c11bdb-0068-4f8a-8ae8-88e52851de3b",
        "title": "KM_Book_1",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:46:27.396Z"
    },
    {
        "id": "8db13e05-ee33-4a52-985e-2f8fea342cde",
        "title": "QARMY´s book",
        "author": "Dinno",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:46:03.589Z"
    },
    {
        "id": "b1a7bc3c-07cf-477a-9f0a-21b174bda8d1",
        "title": "Understanding Chemistry",
        "author": "Ojuwkuku Sr",
        "genre": "fiction",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:33:01.988Z"
    },
    {
        "id": "e4e5312b-70a2-44e4-b59d-cc36f0740d70",
        "title": "QARMY´s book",
        "author": "Dinno",
        "genre": "IT",
        "yearPublished": 2020,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:27:55.927Z"
    },
    {
        "id": "7358ef03-db8e-418a-b0be-d7690018da9e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:20:29.380Z"
    },
    {
        "id": "88568d98-107d-479d-b7a6-04821d99e599",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:19:45.401Z"
    },
    {
        "id": "8d04f675-4842-4f1a-acb9-9abb5a09e4a9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:18:59.022Z"
    },
    {
        "id": "1f6c3ba2-9af0-4c10-a9b1-98dc0469e097",
        "title": "A New Book by Elina",
        "author": "Elina",
        "genre": "children book",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:16:56.668Z"
    },
    {
        "id": "ae07f0bc-490d-4037-9e1a-549ddc50ec80",
        "title": "A New Book by Elina",
        "author": "Elina",
        "genre": "children book",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:15:29.679Z"
    },
    {
        "id": "706449e6-ac94-4bfa-b8aa-cd857adaff07",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:12:33.870Z"
    },
    {
        "id": "ce3a10dd-c091-4b5a-87a1-51d3b8696251",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:12:31.458Z"
    },
    {
        "id": "d9f8b2a9-6d60-42b4-a116-9e7f5a5be0e1",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:10:19.027Z"
    },
    {
        "id": "7afdfeed-0270-4b08-8069-155cf4ebd09b",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:09:57.977Z"
    },
    {
        "id": "a39e25cd-006b-4e27-a421-6892fe5fe8a5",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:08:45.059Z"
    },
    {
        "id": "20e53039-0459-4b4c-addf-7a43841213a5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:08:12.013Z"
    },
    {
        "id": "ce716ebb-7063-4c83-ac30-92bae8a3e618",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:07:16.107Z"
    },
    {
        "id": "3ff42d9a-fc76-46d6-8f20-489daffb7cee",
        "title": "A New Book by Elina",
        "author": "Elina",
        "genre": "children book",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:06:40.013Z"
    },
    {
        "id": "3bc476c9-4186-4ec1-8704-3ad7b785205c",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:04:35.524Z"
    },
    {
        "id": "0409ea40-967c-4ca6-9441-d7381ab4276b",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:02:39.096Z"
    },
    {
        "id": "b93e1307-3353-40a9-ac73-bb738ab5e788",
        "title": "Inferno",
        "author": "Dan Brown",
        "genre": "fiction",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:01:58.363Z"
    },
    {
        "id": "a66bed0c-4b1c-4ff6-9864-10222d34f4cc",
        "title": "perspiciatis nemo sapiente",
        "author": "Bradford Brown",
        "genre": "tech",
        "yearPublished": 426,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:01:53.946Z"
    },
    {
        "id": "618d1258-016a-486f-818c-e01dfcacd5fe",
        "title": "quia nesciunt asperiores",
        "author": "Alan Cassin II",
        "genre": "tech",
        "yearPublished": 994,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:01:53.854Z"
    },
    {
        "id": "66d26a20-b7ba-415f-b7db-a18de88a8976",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T14:00:41.841Z"
    },
    {
        "id": "822d54db-9710-49a7-b994-00b9e722503c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:58:29.748Z"
    },
    {
        "id": "11a9ef12-dc43-4ff8-9f64-fb443891cc22",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:58:27.792Z"
    },
    {
        "id": "9cf36a39-c12b-4d1c-b361-b7874d490565",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:55:54.557Z"
    },
    {
        "id": "043b8ad3-3a35-4649-bff9-5de0ad4ceb1d",
        "title": "Ala ma kota",
        "author": "Ala Aldona",
        "genre": "biography",
        "yearPublished": 2023,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:55:03.372Z"
    },
    {
        "id": "c3bba7fb-a773-4ef1-9f11-b1dd03bd9d6e",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:53:36.423Z"
    },
    {
        "id": "f81dcf38-e2e6-46c4-9123-e0de69edd206",
        "title": "Ala ma kota",
        "author": "Ala Aldona",
        "genre": "biography",
        "yearPublished": 2023,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:52:45.325Z"
    },
    {
        "id": "6e4cadc9-71ba-4e7d-835d-10f16aae295e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:18:03.884Z"
    },
    {
        "id": "cd5b5c0d-9275-42c9-bf26-fe55a905f057",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:13:59.843Z"
    },
    {
        "id": "2ec20d54-9778-4ae4-9d18-528224f93c45",
        "title": "802.11ac A Survival Guide",
        "author": "Matthew Gast",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:11:56.322Z"
    },
    {
        "id": "73692e8a-994b-4471-b213-0445fa4d3dc2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:11:06.734Z"
    },
    {
        "id": "20e9ec56-0009-4bc4-833c-bf64030512c7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:10:28.966Z"
    },
    {
        "id": "21dce1a2-66be-4c08-af81-a57b9b19c6af",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:09:35.479Z"
    },
    {
        "id": "a9230e9e-5ccf-43d0-aee7-0d18b7cd77dd",
        "title": "Mrutunjay",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:08:46.821Z"
    },
    {
        "id": "b0ce4a87-4caf-497a-9525-aa8d2e50b5b7",
        "title": "USIM",
        "author": "Anonymous",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:07:06.701Z"
    },
    {
        "id": "627358fc-8484-461c-b245-398b41a30f74",
        "title": "Janata Raja",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1962,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:01:56.257Z"
    },
    {
        "id": "eb89a873-1dbf-4772-b878-b6a9794e5553",
        "title": "et",
        "author": "Christy Sanford Sr.",
        "genre": "tech",
        "yearPublished": 762,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:00:53.232Z"
    },
    {
        "id": "ed1394a0-1556-4b9e-a9c2-4482aec07ce5",
        "title": "Suscipit praesentium omnis sit et officiis id id et consequuntur.",
        "author": "Stewart Zieme",
        "genre": "tech",
        "yearPublished": 445,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:00:53.088Z"
    },
    {
        "id": "034c90f6-8194-4b28-91f8-716da5a89f28",
        "title": "Cupiditate atque saepe dolores quia.",
        "author": "Thomas Rau",
        "genre": "tech",
        "yearPublished": 596,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T13:00:52.479Z"
    },
    {
        "id": "0aa14db6-96c3-4ad7-a80e-c1ce265dcefa",
        "title": "postman false book 2",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:41:55.149Z"
    },
    {
        "id": "750c4c5e-983d-4d9a-908f-5f0ce49d54cd",
        "title": "postman false book 2",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:41:09.846Z"
    },
    {
        "id": "2a897a7b-cb04-4b2a-a3b5-ba876c6ee861",
        "title": "postman false book 2",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:40:54.157Z"
    },
    {
        "id": "9ed61b11-f0d3-4a8a-a294-1b81590eb4a4",
        "title": "postman false book 2",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:35:26.663Z"
    },
    {
        "id": "e2d363fe-ee6f-4f2d-9a34-55bc9c7b68fd",
        "title": "KM_Book_MyVar",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:32:30.077Z"
    },
    {
        "id": "0fa007f6-b8c8-40dd-9dd7-9158cae938c2",
        "title": "KM_Book_JavaScript",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:30:37.884Z"
    },
    {
        "id": "1bfe86df-0af3-4214-90ed-e35ea6db69af",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:22:44.548Z"
    },
    {
        "id": "699d587f-cab0-4a77-ae45-58add2a2f6c1",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:22:36.617Z"
    },
    {
        "id": "a54b0bc0-763f-4664-b78b-c444cf8bee5f",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:22:24.671Z"
    },
    {
        "id": "d5e6a65b-dcff-4779-874f-9e4beeb8b5d1",
        "title": "KM_Book_JavaScript",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:21:31.415Z"
    },
    {
        "id": "07c574f8-badf-47a7-9564-60447f948150",
        "title": "KM_Book_JavaScript",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:20:36.520Z"
    },
    {
        "id": "7e704a33-1b89-488e-b16b-736386fa99e1",
        "title": "KM_Book_JavaScript",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:20:36.127Z"
    },
    {
        "id": "63d457d9-b955-4dfa-b189-c4e6f43d31fd",
        "title": "City of Bones",
        "author": "Cassandra Clare",
        "genre": "fiction",
        "yearPublished": 2007,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:14:44.824Z"
    },
    {
        "id": "dbceb5a4-7319-470f-ae93-0830c07116eb",
        "title": "Half Girlfriend",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2010,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:14:31.928Z"
    },
    {
        "id": "a7ce9dfe-e10c-41e2-afc3-5d97395d2fa7",
        "title": "psycho cybernetics",
        "author": "maltz",
        "genre": "self help",
        "yearPublished": 1996,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:12:44.206Z"
    },
    {
        "id": "c21c8795-cef9-4935-9823-2496be2805e6",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:12:24.170Z"
    },
    {
        "id": "dc99f121-8f0c-445c-8084-eaea4d2b26da",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:12:21.103Z"
    },
    {
        "id": "a179214c-4d88-4a42-bf51-396d0d405f47",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:12:14.929Z"
    },
    {
        "id": "783d67d9-8283-4f44-926a-faa728febccb",
        "title": "5.someone",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2010,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:10:53.959Z"
    },
    {
        "id": "84359a82-8bbd-41e6-8ab1-6f080d185837",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:08:14.974Z"
    },
    {
        "id": "40a5ffbb-2a91-4eb9-9de3-a72bdd7df23a",
        "title": "Active Interviewing",
        "author": "Eric k Kramer",
        "genre": "self help",
        "yearPublished": 2012,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:04:40.332Z"
    },
    {
        "id": "6219eaa3-635f-4091-abe3-9e0c114b9a1e",
        "title": "Veritatis odit excepturi in reiciendis aliquid voluptas in quibusdam. Accusamus architecto architecto culpa omnis. *** non itaque omnis fugit laboriosam sint est libero. Earum sapiente velit fugit consectetur qui. Unde consequatur aliquid voluptatum.",
        "author": "Kevin Kling",
        "genre": "tech",
        "yearPublished": 786,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:00:43.142Z"
    },
    {
        "id": "dd91b625-cfd3-418c-a115-45b6c7b3bee0",
        "title": "omnis",
        "author": "Elijah VonRueden DDS",
        "genre": "tech",
        "yearPublished": 505,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:00:42.829Z"
    },
    {
        "id": "6ca9fe25-e4e4-4936-9f7b-a12f4939cf5a",
        "title": "Voluptatem explicabo adipisci libero non magni nesciunt sint.",
        "author": "Mrs. Ora Kassulke",
        "genre": "tech",
        "yearPublished": 773,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:00:42.654Z"
    },
    {
        "id": "f0cffbcc-7ca8-40af-a6a9-e1a96131926c",
        "title": "nisi atque iusto",
        "author": "Thelma Stoltenberg III",
        "genre": "tech",
        "yearPublished": 79,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:00:42.561Z"
    },
    {
        "id": "011e41f3-c6f7-4e2b-9078-a28918d0bc48",
        "title": "Non accusamus iusto.",
        "author": "Darren Nolan",
        "genre": "tech",
        "yearPublished": 266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T12:00:42.417Z"
    },
    {
        "id": "abc09131-3fbc-4255-ae6e-1aa46878927b",
        "title": "To kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:59:49.622Z"
    },
    {
        "id": "af9fb575-417f-4f20-b56b-e769e9520447",
        "title": "KM_Book_2",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:53:39.590Z"
    },
    {
        "id": "7f97a972-9a62-4b17-85f2-95465030c94f",
        "title": "Age of Vice",
        "author": "Deepti Kapoor",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:49:42.667Z"
    },
    {
        "id": "d6116286-e5c8-468f-a26a-62ca7210df1e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:48:22.874Z"
    },
    {
        "id": "8c40b5ed-14fb-421a-82a7-87165d731c7b",
        "title": "KM_Book_1",
        "author": "KM",
        "genre": "cool",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:46:43.937Z"
    },
    {
        "id": "6a4ac1b0-49e6-43e6-ac64-ae79c73875e4",
        "title": "g-20",
        "author": "narendra modi",
        "genre": "new world order",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:45:24.844Z"
    },
    {
        "id": "672c0b54-e354-48d6-b7fb-5c2ef71af200",
        "title": "postman false book",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:28:00.988Z"
    },
    {
        "id": "c3f3c553-f39c-453f-8569-d10b93b1d98f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1962,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:27:33.008Z"
    },
    {
        "id": "96813545-f511-4200-95c2-d566dd19c740",
        "title": "postman false book",
        "author": "Dima",
        "genre": "documentary",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:25:14.250Z"
    },
    {
        "id": "6231b32c-725b-488c-8cfe-d37df747b802",
        "title": "Inferno",
        "author": "Dan Brown",
        "genre": "fiction",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:18:22.465Z"
    },
    {
        "id": "d8b642e4-1037-4169-adc9-f50c32482328",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:12:29.681Z"
    },
    {
        "id": "dc93a12d-a1ae-4b33-aab4-43f8b2bfe372",
        "title": "Joys of Compounding",
        "author": "Gautam Baid",
        "genre": "non-fiction",
        "yearPublished": 2015,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:10:07.195Z"
    },
    {
        "id": "f02be608-0b47-4a72-ae3c-6147d4bd9110",
        "title": "Arduino Workshop",
        "author": "John Boxall",
        "genre": "tech",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:04:51.945Z"
    },
    {
        "id": "0459dd56-77e2-41a7-b9be-8c4a549aacdc",
        "title": "Ducimus et et harum. Itaque quisquam animi tenetur perferendis autem reprehenderit ex nam et. Sed esse similique sed voluptatem nesciunt officia maxime ad qui. Voluptatem nesciunt aut. Consequatur quia maiores sed ducimus.",
        "author": "Colleen Kuhlman",
        "genre": "tech",
        "yearPublished": 622,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:00:19.722Z"
    },
    {
        "id": "366d3a22-988a-4b40-a27c-da2362357a61",
        "title": "voluptates",
        "author": "Dan Barrows II",
        "genre": "tech",
        "yearPublished": 902,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:00:19.584Z"
    },
    {
        "id": "cfa924e7-0970-45be-9591-162256b947b6",
        "title": "In laudantium libero rerum voluptas magni. Maiores et quibusdam asperiores nisi minus. Delectus ipsum repellat ut voluptatem ut. Sunt itaque vel amet quia. Ex facere veniam enim quo modi eos id.",
        "author": "Jo Ratke",
        "genre": "tech",
        "yearPublished": 85,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:00:19.431Z"
    },
    {
        "id": "58e15b32-c44d-4ab4-ba24-ac008205b2e3",
        "title": "a nisi sed",
        "author": "Sadie Carroll",
        "genre": "tech",
        "yearPublished": 494,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:00:19.214Z"
    },
    {
        "id": "18e001e0-397b-4d8b-a0ce-39d92178c100",
        "title": "sint sequi ut",
        "author": "Mr. Ben Dach",
        "genre": "tech",
        "yearPublished": 503,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T11:00:19.071Z"
    },
    {
        "id": "8548f27f-4338-4793-a561-f6940690dec5",
        "title": "Ala ma kota",
        "author": "Ala Aldona",
        "genre": "biography",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:51:59.069Z"
    },
    {
        "id": "32d79390-dddc-46a7-9e2a-ebf89503930a",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:45:12.174Z"
    },
    {
        "id": "50ef4bb4-5f83-4f5b-bc1a-1588dc71580a",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:43:28.434Z"
    },
    {
        "id": "e2ea070e-02b5-4677-9c21-61a0bf74cc6f",
        "title": "5.someone",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2010,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:42:46.985Z"
    },
    {
        "id": "f8ff48f2-6863-4ce1-be66-143d7c2366b2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:38:03.208Z"
    },
    {
        "id": "5673fc19-0a60-47d6-a06f-557a1e01593c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:37:44.121Z"
    },
    {
        "id": "de6b25a2-25ef-4cf3-bc83-02ca7ba4b688",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:36:00.422Z"
    },
    {
        "id": "6f24e028-babc-4d44-864a-03938e5d5509",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:35:55.784Z"
    },
    {
        "id": "313b04a0-abf4-4ee7-8ff8-7c58d078cdba",
        "title": "One Indian Girl",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:35:08.782Z"
    },
    {
        "id": "7b684971-21a8-48e5-98a6-d9804d58d51f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:30:33.871Z"
    },
    {
        "id": "f2345ef1-48de-4c2f-8330-047c754c48d4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:27:29.921Z"
    },
    {
        "id": "90fa676e-67ee-45c2-a005-aab0acb47359",
        "title": "My Journey",
        "author": "Dr. APJ Abdul Kalam",
        "genre": "Biography Story",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:13:40.547Z"
    },
    {
        "id": "04f3fce2-c9d2-48c5-b819-11ec3ba4ea8c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:08:44.271Z"
    },
    {
        "id": "59194491-2c04-42b7-a7b0-efafc7d27fe5",
        "title": "Fuga provident ipsa quo esse labore consequuntur.",
        "author": "Jaime Wuckert",
        "genre": "tech",
        "yearPublished": 426,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:01:38.754Z"
    },
    {
        "id": "e97bdabd-6d81-465a-afef-fc3be2ba9b0b",
        "title": "voluptatem dolores eos",
        "author": "Herman Mann",
        "genre": "tech",
        "yearPublished": 899,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:01:38.564Z"
    },
    {
        "id": "b9463af4-48a9-498c-8b69-fc9d24c897cf",
        "title": "Quisquam qui commodi numquam aliquam et quia doloremque nobis.",
        "author": "Wendy Walsh",
        "genre": "tech",
        "yearPublished": 799,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:01:38.343Z"
    },
    {
        "id": "4eff918d-c564-422e-87cb-98d82e6c2faa",
        "title": "Animi excepturi sit maiores impedit qui tempora et sed.",
        "author": "Gwen Stokes",
        "genre": "tech",
        "yearPublished": 371,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T10:01:38.006Z"
    },
    {
        "id": "11cdab07-96b2-41ca-96a1-594cc2e8db15",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:58:36.357Z"
    },
    {
        "id": "b0917849-cb88-40c6-9165-09017077ccf7",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:58:16.520Z"
    },
    {
        "id": "82e0bd59-5585-479e-8494-40c864063d59",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:56:57.440Z"
    },
    {
        "id": "c615639a-e324-49c4-9a2a-4522211efa61",
        "title": "untold story of Smith2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:48:32.277Z"
    },
    {
        "id": "076242e6-8957-4652-b34f-88ac5741f459",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:35:44.114Z"
    },
    {
        "id": "864baefc-0622-4860-b7ed-107c64915a8d",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:24:02.766Z"
    },
    {
        "id": "806a2cc3-b654-44c1-bc68-2e37b27ef44b",
        "title": "the mystery",
        "author": "sona",
        "genre": "thrilled",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:11:25.099Z"
    },
    {
        "id": "760813f0-fe3c-424e-9c8b-5869fb209b4c",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:10:56.756Z"
    },
    {
        "id": "493de765-a164-4ef8-a793-a5dee43371d0",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:10:37.588Z"
    },
    {
        "id": "86e8cdbd-3f70-4f73-8b25-2919c8ec5886",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:10:30.111Z"
    },
    {
        "id": "96a55c41-9c21-4f1a-820b-c16cd7c526c9",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:07:30.885Z"
    },
    {
        "id": "df6067eb-4ecc-409a-b35b-c3fca7981dfa",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:06:29.870Z"
    },
    {
        "id": "eb5f6da8-cad5-4689-a1f6-d8c6477c5d01",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:05:40.566Z"
    },
    {
        "id": "6ad782f9-d14a-499c-ba1a-67be7dae0d44",
        "title": "accusantium",
        "author": "Robin Strosin",
        "genre": "tech",
        "yearPublished": 79,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:01:40.626Z"
    },
    {
        "id": "4a2b2c3b-bdc2-463d-ad80-9ede3f3580d6",
        "title": "similique",
        "author": "Mr. Jeanette Dickinson",
        "genre": "tech",
        "yearPublished": 776,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:01:40.315Z"
    },
    {
        "id": "1d9eaa1e-0142-47ee-a7ca-a611fad30e6d",
        "title": "ab",
        "author": "Stacy Swaniawski",
        "genre": "tech",
        "yearPublished": 676,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T09:01:40.126Z"
    },
    {
        "id": "c3c2cfb9-7df2-45f2-870c-c4570db2315d",
        "title": "untold story of Smith1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:56:40.858Z"
    },
    {
        "id": "100010b4-f0b1-421c-a932-81ba1ee0712c",
        "title": "The muddy muddy wedding",
        "author": "kiki Lee",
        "genre": "fiction",
        "yearPublished": 1940,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:52:37.713Z"
    },
    {
        "id": "7c4edb10-08eb-4cdf-aa05-d469b3c4acba",
        "title": "The muddy muddy wedding",
        "author": "kiki Lee",
        "genre": "fiction",
        "yearPublished": 1940,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:51:56.256Z"
    },
    {
        "id": "572c28b6-0a24-4185-941d-3e90a0120a08",
        "title": "untold story of Smith",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:51:43.769Z"
    },
    {
        "id": "d39a4283-70b3-48f9-be07-af41552920cd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:49:56.227Z"
    },
    {
        "id": "2ade0a28-4cff-4c34-9ff4-2f21f08cf7ab",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:46:56.533Z"
    },
    {
        "id": "74de1e21-462d-494d-a746-43c108491008",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:43:09.854Z"
    },
    {
        "id": "f02f81d9-b1d2-45cc-a30e-e9e5d8eaba06",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:39:10.167Z"
    },
    {
        "id": "e6ba099c-ccce-492f-8bae-0fe29201cd18",
        "title": "untold story",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:34:20.022Z"
    },
    {
        "id": "634a2db0-7633-4d9d-831f-116d07a65270",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:33:21.435Z"
    },
    {
        "id": "929b6e5a-7b7e-4ca7-81c2-5a5ee3016a8d",
        "title": "Martin Eden",
        "author": "Jack London",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:15:58.964Z"
    },
    {
        "id": "7b542b2c-8420-45cb-8c63-4bf3255d6cc0",
        "title": "Martin Eden",
        "author": "Jack London",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:15:44.082Z"
    },
    {
        "id": "4cee01e6-1a7b-49ca-acd9-d43294e16293",
        "title": "White Fang",
        "author": "Jack London",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:12:55.713Z"
    },
    {
        "id": "10026faf-656a-4c4b-b436-289d0f1d0da1",
        "title": "Treasure Island",
        "author": "William Dafoeee",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:08:36.413Z"
    },
    {
        "id": "74b8bdf4-f6dc-4a4d-8904-57f12986c3db",
        "title": "Treasure Island",
        "author": "William Dafoeee",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:00:38.688Z"
    },
    {
        "id": "901766b4-1dad-4a45-a43d-4776da76e4ec",
        "title": "Eaque voluptas laboriosam. Voluptates eligendi fuga molestias eius quisquam *** amet. Velit earum esse pariatur minima quasi. Perferendis ab optio atque est numquam esse alias inventore.",
        "author": "Miss Tim Wyman",
        "genre": "tech",
        "yearPublished": 950,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:00:08.506Z"
    },
    {
        "id": "f19f72c2-4001-41b3-808d-1ad36ce1ea76",
        "title": "laudantium molestiae nam",
        "author": "Mr. Leigh Kovacek",
        "genre": "tech",
        "yearPublished": 687,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:00:07.798Z"
    },
    {
        "id": "33d54780-8946-4f54-93bf-084a3699ccc3",
        "title": "Enim doloremque ex blanditiis. Id qui adipisci quas laboriosam nisi aut hic et. Perferendis corporis harum iste nostrum adipisci culpa cupiditate qui. Vero illo modi quasi. A aut repellat.",
        "author": "Domingo Walker",
        "genre": "tech",
        "yearPublished": 266,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:00:07.569Z"
    },
    {
        "id": "34cde329-103d-463b-9d95-a1e22f899e58",
        "title": "Magni quibusdam minima animi impedit voluptatem ut non et. Laboriosam corrupti enim assumenda exercitationem molestiae. Ad quam et nihil quia ut asperiores ex magni deleniti. Tenetur delectus eaque error in ut est explicabo ratione quaerat.",
        "author": "Leonard Satterfield",
        "genre": "tech",
        "yearPublished": 130,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T08:00:07.284Z"
    },
    {
        "id": "7cdc7cb2-9790-4826-aaf0-b0d2de726227",
        "title": "Treasure Island",
        "author": "William Dafoee",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:59:52.429Z"
    },
    {
        "id": "dd606fcf-d6b7-43ea-8bcf-3f76598b765e",
        "title": "Treasure Island",
        "author": "William Dafoe",
        "genre": "fiction",
        "yearPublished": 1890,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:57:01.650Z"
    },
    {
        "id": "2bb36d3f-b774-45d1-abee-f68352cbc41f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:55:25.748Z"
    },
    {
        "id": "bdd6187e-ca79-4546-b23a-e5b8fb254072",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:51:35.342Z"
    },
    {
        "id": "25c4b8c1-4cdc-4cd7-b332-eb35ed141aa0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:47:10.589Z"
    },
    {
        "id": "aa710f24-8f32-4fbe-8f13-a83bf9d060b9",
        "title": "hello kill",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 2001,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:45:15.841Z"
    },
    {
        "id": "fd3c858e-4ad9-42e4-a29e-873a5eb740b4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:43:20.830Z"
    },
    {
        "id": "41b2a43e-b43a-4184-b813-fc8b4232b1d6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:40:16.913Z"
    },
    {
        "id": "958ecd4e-c0c6-462d-861b-c52877213891",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:38:50.910Z"
    },
    {
        "id": "4ae2e92e-83c0-4ec2-bd23-1ebd3106b9eb",
        "title": "untold story",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:36:26.003Z"
    },
    {
        "id": "32d73158-8b41-4800-b37a-43d104cf2a93",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:34:38.398Z"
    },
    {
        "id": "939b6f6b-b507-4bbc-a9a4-bb74a7a49865",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:34:17.835Z"
    },
    {
        "id": "02e9840c-f995-4ed0-824b-2864544465d4",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:33:34.060Z"
    },
    {
        "id": "bd5b5b10-5341-47e6-a103-fa8f94bbe90a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:29:05.220Z"
    },
    {
        "id": "ac6d8203-fd33-4bca-92f7-e24cd2823c1d",
        "title": "API 101 with AP",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:19:29.144Z"
    },
    {
        "id": "1e1dfdc5-61de-4be8-a10f-372aebc40f80",
        "title": "API 101 with AP",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:14:22.913Z"
    },
    {
        "id": "82fe1bed-90c6-4c29-8c59-a50c1d9cc8ae",
        "title": "API 101 with AP",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:10:24.708Z"
    },
    {
        "id": "a8a19c06-8da2-4bda-9bab-6796586091a4",
        "title": "API 101 with AP",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:10:15.262Z"
    },
    {
        "id": "4e7c53b0-2aa7-44ca-82cb-a5996243c8ce",
        "title": "API 101 with AP",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:08:12.821Z"
    },
    {
        "id": "fe51c0cb-63f5-403c-8e16-065a3e4fb58d",
        "title": "Fundamental transitional concept",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:04:59.893Z"
    },
    {
        "id": "dc4c7b15-6d32-47b7-b01a-b51f272a91da",
        "title": "accusantium",
        "author": "Alejandro Schulist",
        "genre": "tech",
        "yearPublished": 107,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:03:22.409Z"
    },
    {
        "id": "423076b4-bebb-41e1-b67e-9870f1ac2c92",
        "title": "dolor",
        "author": "Noah Bernier",
        "genre": "tech",
        "yearPublished": 940,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:03:22.156Z"
    },
    {
        "id": "2fc21b20-8fcb-4663-aafa-4635ebb20efa",
        "title": "ut",
        "author": "Mrs. Caleb Bahringer",
        "genre": "tech",
        "yearPublished": 995,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:03:21.644Z"
    },
    {
        "id": "30c6f75d-da79-43b1-9086-81215c1b1a73",
        "title": "Fue un privilegio estar aqui",
        "author": "Melva Frias Vda. Carrillo",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:02:15.983Z"
    },
    {
        "id": "2f1fe886-8c16-469a-97b5-e16bf7bb1985",
        "title": "Las sagas de Potter",
        "author": "Josepi LucasMoi",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T07:02:15.716Z"
    },
    {
        "id": "7717b53b-c2ee-40c1-9db1-9513f9734d51",
        "title": "My Journey",
        "author": "Dr. APJ Abdul Kalam",
        "genre": "Biography Story",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:55:15.788Z"
    },
    {
        "id": "27d3ff10-3fe2-4644-a0f3-18af867d1cd9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:47:30.707Z"
    },
    {
        "id": "8dd401d5-825a-4261-bd19-3b7ffd502159",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:41:49.467Z"
    },
    {
        "id": "d1a70888-1a0c-4381-b06b-d2ccdf3b1407",
        "title": "How life changes",
        "author": "Aayush Chaudhary",
        "genre": "Auto Biography",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:41:41.468Z"
    },
    {
        "id": "cba5ba9a-dedf-4a89-a99d-44f06703e70d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:38:12.857Z"
    },
    {
        "id": "1274db9a-f777-4e09-93e1-580f8f650ffb",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:34:29.811Z"
    },
    {
        "id": "dfc34942-daa2-4ef9-bf2b-06eb83f97d2c",
        "title": "How life changes",
        "author": "Aayush Chaudhary",
        "genre": "Auto Biography",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:29:50.085Z"
    },
    {
        "id": "d48ddf1e-a3c5-47a7-915a-d8b3f2bdb74c",
        "title": "Rich Dad Poor Dad",
        "author": "Robert T Kiyoshaki",
        "genre": "Finance",
        "yearPublished": 1998,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:26:56.741Z"
    },
    {
        "id": "61c25aa0-5a0d-408c-a8ac-7422c38f8913",
        "title": "Architecto recusandae tempora velit velit. Eum tempore aliquid vitae. Blanditiis voluptatibus non et qui quas qui.",
        "author": "Lorraine Buckridge",
        "genre": "tech",
        "yearPublished": 503,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:02:34.801Z"
    },
    {
        "id": "1c44f8e5-c6b1-4bca-89e6-a334904a49fc",
        "title": "Officia eligendi laboriosam totam et impedit. Eos consequuntur recusandae odio dicta. Amet quasi soluta et et atque. Voluptatibus mollitia mollitia atque aut.",
        "author": "Kurt Wiegand",
        "genre": "tech",
        "yearPublished": 808,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:02:34.676Z"
    },
    {
        "id": "2da55672-62d2-4703-99a9-b2e94eef4c93",
        "title": "est repellat asperiores",
        "author": "Mario Waelchi",
        "genre": "tech",
        "yearPublished": 330,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:02:34.554Z"
    },
    {
        "id": "5f1e4c97-a440-4286-9019-118c8c670e05",
        "title": "Quaerat tempora soluta mollitia voluptas numquam voluptatem consectetur.",
        "author": "Isabel Labadie",
        "genre": "tech",
        "yearPublished": 728,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:02:34.153Z"
    },
    {
        "id": "b15a3c12-d783-4dbc-ac92-43a1ffd86f02",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T06:00:49.100Z"
    },
    {
        "id": "095c78a3-e655-4db9-a662-9df27c52925b",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:59:22.965Z"
    },
    {
        "id": "8c5e4686-cc4b-47a5-b002-b96294664b24",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:58:57.812Z"
    },
    {
        "id": "3ad8ea92-9073-4b4e-a97a-208fd9983616",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:46:54.167Z"
    },
    {
        "id": "7f456ce6-0405-4201-96f4-4ccbe911982e",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:44:35.424Z"
    },
    {
        "id": "8eacfb67-0f30-4425-a87b-3dd830fc4282",
        "title": "To Kill a Mockingbird1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:41:40.763Z"
    },
    {
        "id": "09be9063-aee3-4ae8-ac6e-2703cc6f9b17",
        "title": "Madol Duwa",
        "author": "Martin",
        "genre": "fiction",
        "yearPublished": 1964,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:36:13.942Z"
    },
    {
        "id": "3ee948ce-bc89-4cd4-a4a1-562f48e88aa6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:23:28.592Z"
    },
    {
        "id": "9cd3d9d0-2298-42d8-87e6-a095219c6712",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:21:06.849Z"
    },
    {
        "id": "ba1b4056-05ad-4b56-8411-3ba3adbd96a9",
        "title": "Wodderful my world",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:09:05.507Z"
    },
    {
        "id": "0f541ebd-49b3-4932-b67d-cdf81bdc81e9",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:04:37.371Z"
    },
    {
        "id": "7604358f-55c1-4867-b925-87fbf064c82f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:03:57.035Z"
    },
    {
        "id": "92f0e1b4-aac0-472b-86d9-f9f946468a39",
        "title": "provident voluptas assumenda",
        "author": "Arturo Okuneva",
        "genre": "tech",
        "yearPublished": 750,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:02:57.451Z"
    },
    {
        "id": "a87f4fdd-f309-4cca-9e9e-38c03e258ec8",
        "title": "Officia aut dolor tempora maiores quod. Sed praesentium quis optio in suscipit ea et ducimus sed. Ipsam consequuntur facilis magni tenetur nostrum consequatur id corporis beatae. Ducimus commodi consequuntur sint quia ut perferendis.",
        "author": "Guadalupe Oberbrunner",
        "genre": "tech",
        "yearPublished": 392,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:02:57.316Z"
    },
    {
        "id": "e0fd4391-fb46-4f53-8450-55170ad0d851",
        "title": "qui",
        "author": "Dr. Francisco Schuster",
        "genre": "tech",
        "yearPublished": 237,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:02:57.165Z"
    },
    {
        "id": "319dc728-9b49-45a0-ab0f-5a4ddfe91b34",
        "title": "rerum",
        "author": "Sam Bernier",
        "genre": "tech",
        "yearPublished": 537,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:02:57.053Z"
    },
    {
        "id": "8057c73d-4fe1-411a-9d8d-f94f3ce1cd0c",
        "title": "vel et commodi",
        "author": "Frank Steuber",
        "genre": "tech",
        "yearPublished": 749,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:02:56.957Z"
    },
    {
        "id": "2fdd059f-f254-4e52-b07c-dca811d015c3",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:01:29.031Z"
    },
    {
        "id": "4db08547-96a1-4803-99e9-682681d4fb43",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T05:00:21.320Z"
    },
    {
        "id": "ed24c190-aa97-4a7f-b90a-b63d9ac47524",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:58:56.200Z"
    },
    {
        "id": "6bb67c2a-a6c8-4a51-92b0-f6277e2e653d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:56:46.038Z"
    },
    {
        "id": "8ed025c4-a392-4ff1-8e2c-c170e37f600d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:53:55.640Z"
    },
    {
        "id": "0ed8532c-0d93-4ec1-8185-b21cc8e3b6d6",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:45:40.822Z"
    },
    {
        "id": "2b5c6114-ecc2-4b7d-80c9-196b937ce1e0",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:45:28.325Z"
    },
    {
        "id": "98cf62ef-45f8-4ede-b055-589c2e5d8892",
        "title": "To Kill",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:43:13.885Z"
    },
    {
        "id": "aa32ad4a-e968-44cb-904f-889f06ee145d",
        "title": "To Me",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1962,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:38:59.742Z"
    },
    {
        "id": "a5f90d5d-ccdb-4952-b0cd-2cf6afb6cfc3",
        "title": "Atomic Habits 2",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:34:23.403Z"
    },
    {
        "id": "e31b1af0-1937-4139-85e8-a75f21bc3244",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "Motivation",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:25:00.693Z"
    },
    {
        "id": "16fa327e-934e-4434-a481-86d2d036d987",
        "title": "New Version To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:06:53.161Z"
    },
    {
        "id": "ebae9893-c4eb-4b8b-a72f-4343b1f8c8e2",
        "title": "Reiciendis incidunt reiciendis.",
        "author": "Nancy Altenwerth",
        "genre": "tech",
        "yearPublished": 349,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:00:43.768Z"
    },
    {
        "id": "994c79f8-316a-4dfa-9485-a9a9f9779b96",
        "title": "Ut earum dolores.",
        "author": "Joe Hahn",
        "genre": "tech",
        "yearPublished": 815,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:00:43.542Z"
    },
    {
        "id": "3223a808-2690-4c4b-8cb6-2cb0fb6820ae",
        "title": "eos",
        "author": "Miss Crystal Sanford",
        "genre": "tech",
        "yearPublished": 854,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:00:43.446Z"
    },
    {
        "id": "77f5ccaf-79b7-464c-a715-eca1dc28c236",
        "title": "beatae",
        "author": "Nancy Krajcik",
        "genre": "tech",
        "yearPublished": 117,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:00:43.134Z"
    },
    {
        "id": "a5fc7038-c419-4b08-84ac-a91d533b819e",
        "title": "illum aut exercitationem",
        "author": "Shelia Altenwerth",
        "genre": "tech",
        "yearPublished": 447,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T04:00:36.974Z"
    },
    {
        "id": "d1ccd556-0e2d-4215-b73b-fead7d409f70",
        "title": "Jane Eyre",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:53:51.659Z"
    },
    {
        "id": "cb25b01d-fb30-4bda-b672-389661deaddf",
        "title": "To Me",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1962,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:31:22.541Z"
    },
    {
        "id": "8f0dd1fb-1dc0-4d10-847a-25baf562ff54",
        "title": "To Kill Me",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1962,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:29:01.487Z"
    },
    {
        "id": "f5af695a-6d9e-4428-b5a3-98ceadefe70e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:05:37.438Z"
    },
    {
        "id": "c3ba4e0f-685d-48b8-b74a-505de9136063",
        "title": "Jane Eyre",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:02:49.008Z"
    },
    {
        "id": "7fb500e7-3fa6-4ac7-936f-9b01b8407db3",
        "title": "Ad necessitatibus consectetur culpa qui placeat facere minima adipisci perferendis. Ipsam et corporis facilis. Voluptas maiores perspiciatis. Molestias esse et. Temporibus voluptatem soluta recusandae pariatur rerum quia est explicabo rerum.",
        "author": "Natalie Crona",
        "genre": "tech",
        "yearPublished": 900,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:01:13.464Z"
    },
    {
        "id": "cff9ec46-a82a-42a6-bc69-a3d81cb28152",
        "title": "Ut et non est voluptas officiis quod aut inventore. Id nulla quasi quibusdam nisi tenetur vero tempore beatae dolores. Accusantium ex quia veritatis iure error. Cumque numquam omnis quidem exercitationem dolorem consequatur.",
        "author": "Marcella Lubowitz",
        "genre": "tech",
        "yearPublished": 967,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:01:13.296Z"
    },
    {
        "id": "9b006225-2f2c-447b-85df-d003ea9a7d0e",
        "title": "Ipsa iste repudiandae. Enim quo quo.",
        "author": "Wade Bednar DVM",
        "genre": "tech",
        "yearPublished": 770,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T03:01:13.143Z"
    },
    {
        "id": "2b6a7bdb-cfe4-4c17-992e-026b3bba6a74",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:50:10.705Z"
    },
    {
        "id": "60a51c0b-277a-46c7-a040-4c76dc6528a6",
        "title": "Jane",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1985,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:48:08.393Z"
    },
    {
        "id": "2e37cd4c-4d25-436e-bf7c-82ff2568f44b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1985,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:47:48.601Z"
    },
    {
        "id": "a0a4ecb3-ade6-4be0-8253-840c07f5eee2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:47:01.155Z"
    },
    {
        "id": "45fe5982-b2bd-4706-82db-8ddfc7d865e5",
        "title": "voluptas est voluptatibus",
        "author": "Clinton Ferry",
        "genre": "tech",
        "yearPublished": 737,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:01:04.034Z"
    },
    {
        "id": "ceceebf1-a0c4-496c-93f7-5220490fc1c6",
        "title": "quidem et dolorem",
        "author": "Ryan Windler",
        "genre": "tech",
        "yearPublished": 990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:01:03.820Z"
    },
    {
        "id": "a39ec041-633f-49dd-a034-0e5722df4445",
        "title": "fugiat dolorem qui",
        "author": "Eric Bartoletti",
        "genre": "tech",
        "yearPublished": 28,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:01:03.673Z"
    },
    {
        "id": "80d343be-f8f2-44a8-896c-b5cf00702c8e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T02:00:52.848Z"
    },
    {
        "id": "335976f8-7d95-49fd-8e57-4ed924e7f563",
        "title": "New Version To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:37:03.410Z"
    },
    {
        "id": "71f4b6e5-4d46-41a1-8e27-9fbbef72a264",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:32:58.672Z"
    },
    {
        "id": "b4a1ada5-3878-4aa0-a729-7a2e4953b87a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:18:44.744Z"
    },
    {
        "id": "7041f06a-6529-42e4-bb1a-8e9dd9e9a6bd",
        "title": "Et earum maiores odit non vel aut iste adipisci. Quaerat et delectus. Sint tempora eum.",
        "author": "Lester Olson",
        "genre": "tech",
        "yearPublished": 953,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:00:58.401Z"
    },
    {
        "id": "87f7dbce-012c-4ae9-a2e3-44a240b9a24d",
        "title": "delectus est incidunt",
        "author": "Sandy Hessel",
        "genre": "tech",
        "yearPublished": 573,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:00:57.938Z"
    },
    {
        "id": "69e8f438-2983-4a1b-b245-d9a0952c39e9",
        "title": "Rem officiis molestias.",
        "author": "Sergio Johns Sr.",
        "genre": "tech",
        "yearPublished": 339,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:00:57.755Z"
    },
    {
        "id": "7df4f86b-439c-433a-8e2e-f1e2b7462342",
        "title": "Blanditiis et et totam et enim quibusdam ut sunt sit. Eos aut hic sunt necessitatibus recusandae laboriosam incidunt consequuntur magnam. Temporibus nulla impedit velit at non. Commodi ut voluptates. Corporis fuga illum.",
        "author": "Carroll O'Conner",
        "genre": "tech",
        "yearPublished": 421,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:00:57.546Z"
    },
    {
        "id": "63fc4f39-15de-44c8-91d9-8ff36a5ae60d",
        "title": "iusto",
        "author": "Betty Doyle",
        "genre": "tech",
        "yearPublished": 686,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T01:00:57.211Z"
    },
    {
        "id": "ed8b6152-d644-4fb2-b6d6-46444f1af65d",
        "title": "Tejiendo la Red",
        "author": "Tim Bernners-Lee",
        "genre": "Tecnología",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:38:56.764Z"
    },
    {
        "id": "0ee85237-ad3f-48ad-b2cb-17a14bf22bf8",
        "title": "Tejiendo la Red",
        "author": "Tim Bernners-Lee",
        "genre": "Tecnología",
        "yearPublished": 2000,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:37:22.984Z"
    },
    {
        "id": "59a547ec-9127-4888-8c62-a4ba18034a73",
        "title": "Ipsam ea facere earum. Sapiente ratione tempora nemo adipisci quia rem at dolores et. Et nihil dolores qui. Eum non distinctio enim odit. Quo suscipit recusandae itaque.",
        "author": "Fred Heller",
        "genre": "tech",
        "yearPublished": 740,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:01:42.616Z"
    },
    {
        "id": "c54d70b2-b6d9-4bf7-ad8b-52e75709bcc1",
        "title": "Voluptas et accusantium earum non sunt.",
        "author": "Deborah Hickle",
        "genre": "tech",
        "yearPublished": 186,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:01:42.489Z"
    },
    {
        "id": "a4c45d4f-32f9-467d-b3fa-18e0bddd4c96",
        "title": "id",
        "author": "Armando Berge",
        "genre": "tech",
        "yearPublished": 678,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:01:42.354Z"
    },
    {
        "id": "88621c82-e21a-4361-9b03-fd1e834a8c01",
        "title": "repellendus",
        "author": "Gene Kris",
        "genre": "tech",
        "yearPublished": 998,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-13T00:01:42.187Z"
    },
    {
        "id": "3a2e1c5b-b90b-4f18-8259-9fce13fbb067",
        "title": "Tejiendo la Red",
        "author": "Tim Bernners-Lee",
        "genre": "Tecnología",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T23:16:44.152Z"
    },
    {
        "id": "365fd34a-be2c-471b-bbbb-91eca84659fc",
        "title": "*** voluptate deleniti",
        "author": "Leah Hamill",
        "genre": "tech",
        "yearPublished": 794,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T23:04:30.800Z"
    },
    {
        "id": "f211b0de-6f36-47bf-95d7-441564a79d1e",
        "title": "Et omnis nemo. Et ab numquam tenetur quis veniam et voluptate voluptatem neque. Eos reprehenderit et qui doloribus et. Qui tempora eligendi aut pariatur numquam ut minus.",
        "author": "Mrs. Dexter Von",
        "genre": "tech",
        "yearPublished": 526,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T23:04:30.629Z"
    },
    {
        "id": "d0f74d6c-ac11-43c5-893c-e104e2dce422",
        "title": "Recusandae recusandae soluta ex vel sit. Neque sit quod ea facilis. Necessitatibus minima odit minus rerum numquam omnis est. Unde accusamus quidem odit perferendis vero provident sit et unde. Enim consequuntur necessitatibus quo autem ut reiciendis.",
        "author": "Hugo Effertz",
        "genre": "tech",
        "yearPublished": 701,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T23:04:30.487Z"
    },
    {
        "id": "def024d9-329c-4a80-a05f-66d0bfc212c9",
        "title": "eligendi",
        "author": "Todd Huels",
        "genre": "tech",
        "yearPublished": 616,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T23:04:30.361Z"
    },
    {
        "id": "f7d73411-3702-4643-b041-5505756997e1",
        "title": "Impedit quia magni.",
        "author": "Bernadette Schuster",
        "genre": "tech",
        "yearPublished": 673,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T22:05:25.603Z"
    },
    {
        "id": "a4f26f14-5996-4da4-972f-0002d56d3fe8",
        "title": "perspiciatis est fuga",
        "author": "Steve Watsica",
        "genre": "tech",
        "yearPublished": 425,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T22:05:25.094Z"
    },
    {
        "id": "e2b9c8b6-703f-43cd-9a7b-64f18d3d1e5d",
        "title": "tempora",
        "author": "Mr. Floyd Altenwerth",
        "genre": "tech",
        "yearPublished": 736,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T21:03:26.698Z"
    },
    {
        "id": "a27c0e17-b4b9-4e78-93ab-0d4627978bea",
        "title": "Minus quae est quo porro. Culpa facilis qui alias rem dolor et accusantium quisquam. Est harum aut. Accusamus delectus praesentium iure non est.",
        "author": "Freda Rolfson",
        "genre": "tech",
        "yearPublished": 586,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T21:03:26.401Z"
    },
    {
        "id": "93b8339e-33a5-4d26-bf2b-bfbe242d4e05",
        "title": "Vero sed adipisci vitae aut. Rerum non quia vitae accusamus blanditiis numquam fugit rerum illo. Cupiditate assumenda perspiciatis in. Atque sit a possimus iure maxime quas cumque est quia.",
        "author": "Ms. Jodi Abshire",
        "genre": "tech",
        "yearPublished": 349,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T21:03:26.196Z"
    },
    {
        "id": "6ff68873-2df6-411f-ac89-e6e823688e23",
        "title": "aliquam",
        "author": "Luz Goodwin III",
        "genre": "tech",
        "yearPublished": 25,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T21:03:25.729Z"
    },
    {
        "id": "384f5c66-9326-45d7-9130-6437856e6746",
        "title": "To Kill a Mockingbird New",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:12:19.222Z"
    },
    {
        "id": "3f15ce40-b3ec-4a15-9b03-1ff163ba3e00",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:05:59.364Z"
    },
    {
        "id": "c530bb3e-b37b-4ecc-ac19-4462946fac45",
        "title": "*** soluta architecto vitae aliquid et ullam libero qui. Voluptas eos vel quos accusamus repellendus sunt. Quo veniam sint sit natus et corporis qui beatae quas.",
        "author": "Marilyn Bashirian",
        "genre": "tech",
        "yearPublished": 453,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:02:20.148Z"
    },
    {
        "id": "4b98dee5-23c3-4fcf-adbf-712a3d7543a3",
        "title": "Ipsam ut nam dolore ut quibusdam. Occaecati maiores quod eligendi rerum vero beatae et excepturi. Nostrum voluptatum voluptatem nulla voluptas.",
        "author": "Ted Conn",
        "genre": "tech",
        "yearPublished": 207,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:02:19.170Z"
    },
    {
        "id": "31ebed73-9aff-409f-a6ac-08894a064cc1",
        "title": "aut",
        "author": "Edmond Hauck PhD",
        "genre": "tech",
        "yearPublished": 139,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:02:18.886Z"
    },
    {
        "id": "46fcaef8-83ed-4127-99d8-9f957a84591d",
        "title": "Qui tempora consequatur dolorum illo et.",
        "author": "Billy Beatty",
        "genre": "tech",
        "yearPublished": 338,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T20:02:18.626Z"
    },
    {
        "id": "2980b3ce-17e5-4255-8f9b-ffc6eb09ebb1",
        "title": "Rich Dad Poor Dad",
        "author": "bhavya",
        "genre": "life goals",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:58:28.565Z"
    },
    {
        "id": "e873f706-5340-4659-bce7-5b3e765506e2",
        "title": "Rich Dad Poor Dad",
        "author": "bhavya",
        "genre": "life goals",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:56:17.719Z"
    },
    {
        "id": "0717177b-e3cd-4550-9439-f35b5b8d237f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:43:46.864Z"
    },
    {
        "id": "a91f4396-4236-46f9-8507-8d81e892f20b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:42:22.161Z"
    },
    {
        "id": "8d091e08-bd18-4f38-acf3-6d42da0bc26c",
        "title": "Rich Dad Poor Dad",
        "author": "bhavya",
        "genre": "life goals",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:39:17.955Z"
    },
    {
        "id": "cd2310bf-d328-4a05-9a48-e2b59ecc9ebf",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:36:50.755Z"
    },
    {
        "id": "8d48f86b-80f2-4ca3-841e-3bac1b33b85a",
        "title": "Konkan-RanManus",
        "author": "kingoflight",
        "genre": "Nature",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:30:57.310Z"
    },
    {
        "id": "79d13e7e-6bf8-4b51-b6a4-d6b302c622fd",
        "title": "delectus possimus sit",
        "author": "Scott Schmeler DDS",
        "genre": "tech",
        "yearPublished": 628,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:00:09.640Z"
    },
    {
        "id": "0a644cef-0a0a-4048-8094-cec0089e2bd6",
        "title": "deserunt rem ut",
        "author": "Terrell Heller",
        "genre": "tech",
        "yearPublished": 659,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:00:09.305Z"
    },
    {
        "id": "5e877bef-7ade-4a31-b23f-7301e577883e",
        "title": "recusandae",
        "author": "Luis Rogahn",
        "genre": "tech",
        "yearPublished": 923,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:00:09.011Z"
    },
    {
        "id": "2ed7e371-30e1-4047-b411-1a3b5dbf8681",
        "title": "voluptatum est ex",
        "author": "Angelica Hyatt",
        "genre": "tech",
        "yearPublished": 995,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:00:08.778Z"
    },
    {
        "id": "0953844e-8248-418c-bb9d-72344184b851",
        "title": "alias",
        "author": "Lynn Christiansen",
        "genre": "tech",
        "yearPublished": 567,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T19:00:08.533Z"
    },
    {
        "id": "9de246a0-fb7c-458d-99e0-febbb2c0b7cf",
        "title": "Konkan-RanManus",
        "author": "kingoflight",
        "genre": "Nature",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:59:59.102Z"
    },
    {
        "id": "7b8400a9-6a6f-416f-85de-243bf4dbbc65",
        "title": "Heartstopper Volume Three",
        "author": "Alice Oseman",
        "genre": "graphic novel",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:56:04.986Z"
    },
    {
        "id": "d44c1d1d-09e0-4b4b-a2ed-0808a8a7e002",
        "title": "Konkan-RanManus",
        "author": "kingoflight",
        "genre": "Nature",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:53:31.705Z"
    },
    {
        "id": "dde089c3-405e-46af-bcdf-065a0612a069",
        "title": "Atomic Habits",
        "author": "udit",
        "genre": "life goals",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:48:19.313Z"
    },
    {
        "id": "3bbb5254-946e-4f88-97ba-8d4027a3eccf",
        "title": "Heartstopper Volume Two",
        "author": "Alice Oseman",
        "genre": "graphic novel",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:36:43.523Z"
    },
    {
        "id": "02dad838-1171-4750-8344-d720b8967235",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:29:35.086Z"
    },
    {
        "id": "5c76235b-eaae-4672-949f-5b6c50773423",
        "title": "Heartstopper Volume One",
        "author": "Alice Oseman",
        "genre": "graphic novel",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:29:33.024Z"
    },
    {
        "id": "7bd3f27a-a938-4256-b267-1ffd8de3a88b",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:16:56.919Z"
    },
    {
        "id": "6cb36517-e38d-4578-bb26-0c29e888eb9e",
        "title": "API 101 with Ali",
        "author": "Ved Bhoir",
        "genre": "education",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:05:21.053Z"
    },
    {
        "id": "a85bd155-e1ba-49e9-bfc7-ce6f7d61ca44",
        "title": "Mathematics",
        "author": "Ion Petrica",
        "genre": "Math",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:03:00.158Z"
    },
    {
        "id": "7dee1aa6-37f2-47ab-85b7-08d0be0799d2",
        "title": "Eaque laudantium autem porro cumque harum. Et explicabo sint vel voluptas aut dolor minima consequatur ipsam. Qui sed architecto eos sapiente non quia expedita. In molestiae id non sunt officiis omnis.",
        "author": "Blanca Yundt",
        "genre": "tech",
        "yearPublished": 231,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:00:36.965Z"
    },
    {
        "id": "3152a2a1-f514-4d95-8ca4-aae6758f24cc",
        "title": "Vero laborum facilis.",
        "author": "Tracey Gutmann",
        "genre": "tech",
        "yearPublished": 180,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:00:36.739Z"
    },
    {
        "id": "22a8d1c9-0246-4e1b-91d4-15283a296eef",
        "title": "natus",
        "author": "Luther Beier",
        "genre": "tech",
        "yearPublished": 769,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T18:00:36.301Z"
    },
    {
        "id": "d2e8d6bc-e755-47eb-8a1a-cdece506792f",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:57:17.245Z"
    },
    {
        "id": "19c48c9f-708f-4aba-b114-b10c55bdb1e4",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:57:09.016Z"
    },
    {
        "id": "9c738fb2-7bc8-4621-ae17-df9405d4ad80",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:57:03.277Z"
    },
    {
        "id": "5c7a69e2-3737-4ae8-9248-f24095a5e8c8",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:56:56.323Z"
    },
    {
        "id": "5bec7064-93c8-4ef3-b9ab-7d0ee5b230c9",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:50:15.580Z"
    },
    {
        "id": "ea30dee0-f602-4982-9533-410794f24650",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:49:35.412Z"
    },
    {
        "id": "ad14ebae-0f17-4a0f-bc1f-8552cef2a690",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:49:08.957Z"
    },
    {
        "id": "3178f03e-8909-431d-bbad-18dbe713bcc6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:48:11.193Z"
    },
    {
        "id": "4a0e81f5-bb64-4758-8b41-2bb336987e46",
        "title": "Xamiles Ptiseis",
        "author": "Arkas",
        "genre": "fiction",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:47:07.816Z"
    },
    {
        "id": "be236547-2b93-4600-9592-2ef6af289ded",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:44:27.777Z"
    },
    {
        "id": "5685161b-09ad-405f-8974-4c18d38c86f6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:42:07.741Z"
    },
    {
        "id": "93cde339-db3a-4a27-9407-aafe7b240a70",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:01:11.263Z"
    },
    {
        "id": "b86cd71b-2d45-4352-9963-fb9c014861de",
        "title": "Saepe omnis nulla dolorem animi consectetur earum tenetur et.",
        "author": "Elaine Little",
        "genre": "tech",
        "yearPublished": 468,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:00:55.531Z"
    },
    {
        "id": "7e23cdd6-1b8f-47d8-ade5-20b4a6b92d26",
        "title": "Quae tenetur doloremque et saepe quod sed magni laborum. Aut aliquam nam ullam. Alias rerum sed illo architecto vero.",
        "author": "Luke Bechtelar",
        "genre": "tech",
        "yearPublished": 414,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:00:55.395Z"
    },
    {
        "id": "67cbdbfb-be16-4116-a7e2-2f4ffacb23de",
        "title": "Recusandae et sed voluptas maxime ipsa sit minus debitis vero.",
        "author": "Sally Steuber",
        "genre": "tech",
        "yearPublished": 122,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:00:55.235Z"
    },
    {
        "id": "fc2dd803-7bb0-4ee5-8a39-42a2ce07fc99",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T17:00:20.961Z"
    },
    {
        "id": "a6a5880e-9721-461b-874e-b046220bb38c",
        "title": "USIM NI BOSS",
        "author": "Anonymous",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:59:59.462Z"
    },
    {
        "id": "edb5dbbe-19dc-4898-95a3-208ed17c2f15",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:59:36.442Z"
    },
    {
        "id": "75e3dc26-9485-4751-b2c0-176b0eb9e82b",
        "title": "The New Book",
        "author": "Author Name",
        "genre": "Fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:23:57.511Z"
    },
    {
        "id": "0bd77e49-dddb-4ce4-ad09-75d78d8fab07",
        "title": "Wings of fire",
        "author": "Dr. A. P. J. Abdul Kalam",
        "genre": "biography",
        "yearPublished": 2000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:20:59.680Z"
    },
    {
        "id": "489c845e-3b1f-4dbc-a1b9-41fab75ebc08",
        "title": "Test Book 235",
        "author": "JVC235",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:20:50.382Z"
    },
    {
        "id": "71c2d41b-7db9-4ea0-a2db-3fb84a622d4b",
        "title": "Dolor voluptatem quo blanditiis.",
        "author": "Sherman *******",
        "genre": "tech",
        "yearPublished": 402,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:02:33.370Z"
    },
    {
        "id": "3b344d69-3343-4271-be5f-af45a7cc16f8",
        "title": "culpa",
        "author": "Jake Rutherford",
        "genre": "tech",
        "yearPublished": 992,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:02:32.507Z"
    },
    {
        "id": "7afb2252-f646-460c-8e5f-39169f072dfa",
        "title": "Quibusdam dignissimos et.",
        "author": "Rachel McCullough",
        "genre": "tech",
        "yearPublished": 84,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:02:31.552Z"
    },
    {
        "id": "f6acc9e5-e23f-4355-a4ce-55f8bacd4a13",
        "title": "Velit qui labore doloremque porro et.",
        "author": "Chester Luettgen",
        "genre": "tech",
        "yearPublished": 340,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:02:29.652Z"
    },
    {
        "id": "2674e446-ee52-43a5-b99a-9078d0efa189",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T16:01:58.110Z"
    },
    {
        "id": "69daadf3-4163-4ecd-a983-06c12ae004a7",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:45:40.483Z"
    },
    {
        "id": "3f766ef6-b291-4273-a7cd-bc069c200e98",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:45:00.466Z"
    },
    {
        "id": "16e5e1a4-d362-4754-8037-94e324ea2c7b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:44:38.960Z"
    },
    {
        "id": "b0f249b9-6101-4d3a-af16-7de03823f16c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:42:34.596Z"
    },
    {
        "id": "7a457ca1-186b-4a7d-80d9-785a8ef086ec",
        "title": "Fahrenheit 451",
        "author": "Ray Bradbury",
        "genre": "fiction",
        "yearPublished": 1953,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:41:26.445Z"
    },
    {
        "id": "ae2c873e-ae78-4a01-88b6-8bf1264267dd",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:38:52.251Z"
    },
    {
        "id": "8f322c99-cb56-4236-9bb0-bc9968564048",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:36:44.687Z"
    },
    {
        "id": "20377d84-8b8a-4692-958a-d9da53c6c436",
        "title": "2 states",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:09:05.450Z"
    },
    {
        "id": "59696204-c808-45ff-82ad-bc98d52a79e1",
        "title": "Deserunt facilis nisi sed maxime dolorem.",
        "author": "Lorraine Fritsch",
        "genre": "tech",
        "yearPublished": 37,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:02:07.058Z"
    },
    {
        "id": "f9e5fa1c-fdd8-4269-9588-0dd9768fbed8",
        "title": "Vel voluptas repellat voluptatem aut excepturi qui.",
        "author": "Alberta Grimes",
        "genre": "tech",
        "yearPublished": 868,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:02:06.902Z"
    },
    {
        "id": "30283f9a-19c1-43cc-886d-0b73daf6e383",
        "title": "Eius veniam dolorem minus aut aut velit vitae.",
        "author": "Marshall Cormier V",
        "genre": "tech",
        "yearPublished": 712,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:02:06.679Z"
    },
    {
        "id": "4beb83b9-fe46-4cee-98b4-0d77a387801a",
        "title": "deleniti",
        "author": "Dr. Agnes Bogisich",
        "genre": "tech",
        "yearPublished": 88,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T15:02:06.540Z"
    },
    {
        "id": "f09ecae5-72b6-44e3-8ed1-03b7a095d78e",
        "title": "Sahil khilari ",
        "author": "Harper Lee",
        "genre": "horror",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:50:46.166Z"
    },
    {
        "id": "dd24ed40-f0a0-4fc8-ad2c-430cf2f23a23",
        "title": "Quantum Radio",
        "author": "A.G. Riddle",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:49:06.466Z"
    },
    {
        "id": "14b19379-331a-46b2-aad4-2a80a42926c1",
        "title": "Sahil ",
        "author": "Harper Lee",
        "genre": "horror",
        "yearPublished": 2004,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:45:58.468Z"
    },
    {
        "id": "b968495e-a1ff-4bea-ad4e-488b53f4fbb6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:44:10.342Z"
    },
    {
        "id": "2e8792e8-816e-4225-af67-2054de05d3c0",
        "title": "Do Androids Dream of Electric Sheep?",
        "author": "Philip K. ****",
        "genre": "fiction",
        "yearPublished": 1968,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:41:34.633Z"
    },
    {
        "id": "c162b21d-fe10-4622-ae5a-c7e344be988e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:40:28.364Z"
    },
    {
        "id": "8289e1d9-4a0c-462b-ad95-084760b94eb8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:39:26.248Z"
    },
    {
        "id": "39129ba9-59fc-4ca1-8bb2-56247d01bc7b",
        "title": "Fourth Wing",
        "author": "Rebecca Yarros",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:33:43.104Z"
    },
    {
        "id": "b9f35beb-ae49-43d9-bc4f-14768653a45a",
        "title": "Nineteen Eighty-Four",
        "author": "George Orwell",
        "genre": "fiction",
        "yearPublished": 1949,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:15:24.897Z"
    },
    {
        "id": "bca827b6-3c5a-47e4-9db3-bb2b38955a3a",
        "title": "Nineteen Eighty-Four",
        "author": "George Orwell",
        "genre": "fiction",
        "yearPublished": 1949,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:15:12.508Z"
    },
    {
        "id": "61d4848e-941e-46af-81ac-f2ae88dbcb83",
        "title": "Alika y sus sueños",
        "author": "Camila Paule",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T14:08:09.758Z"
    },
    {
        "id": "0619dd34-8e6a-4af5-806c-84294b02867a",
        "title": "The prem",
        "author": "Harper gillala",
        "genre": "fiction",
        "yearPublished": 1968,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:57:15.180Z"
    },
    {
        "id": "824feb55-1582-491e-8cd2-705a86ec7fe8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:57:06.810Z"
    },
    {
        "id": "62a0b353-4277-4c04-a904-2013ef7bbc16",
        "title": "The champ",
        "author": "Harper prem",
        "genre": "fictionss",
        "yearPublished": 1968,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:56:44.417Z"
    },
    {
        "id": "368f826d-a409-4d5f-8ed8-910f0165165c",
        "title": "Elevation",
        "author": "Stephen King",
        "genre": "fiction",
        "yearPublished": 2019,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:55:21.046Z"
    },
    {
        "id": "ceeeba50-b81d-4c81-8314-3c70e968bf61",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:22:48.093Z"
    },
    {
        "id": "68e5bf20-a18b-4971-9b67-522da6ba1b5d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:18:53.831Z"
    },
    {
        "id": "bcecca32-7e40-4734-a028-d27a6a6c8a93",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:15:13.707Z"
    },
    {
        "id": "936ed7bf-d03a-46f9-ad78-6c05fbcd4a95",
        "title": "Rerum eos quo necessitatibus voluptatum excepturi.",
        "author": "Jeanette Runolfsson I",
        "genre": "tech",
        "yearPublished": 780,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:00:34.692Z"
    },
    {
        "id": "63b8cd6b-a975-49fb-b1d8-ee6a7eadbb36",
        "title": "Aut fugit nostrum perspiciatis aut et quas.",
        "author": "Rickey McKenzie",
        "genre": "tech",
        "yearPublished": 171,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:00:34.636Z"
    },
    {
        "id": "f331a902-ef09-4489-8a56-99286ebb9695",
        "title": "Et quas nostrum omnis quas rerum nesciunt asperiores ut.",
        "author": "Jo Dooley",
        "genre": "tech",
        "yearPublished": 839,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:00:34.584Z"
    },
    {
        "id": "0599e964-e109-489c-befe-ac0d0e9ca62d",
        "title": "Sunt libero molestiae nesciunt quis. Consequatur et dicta ut excepturi debitis fugit. Non iusto officia voluptas et est explicabo. Ea et cumque quidem voluptas ea.",
        "author": "Leo Waters",
        "genre": "tech",
        "yearPublished": 730,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:00:34.517Z"
    },
    {
        "id": "06c081e2-54fb-4a69-ae08-c85fc7b56220",
        "title": "voluptas",
        "author": "Sheri Bahringer",
        "genre": "tech",
        "yearPublished": 455,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T13:00:34.419Z"
    },
    {
        "id": "4e2d7093-0b17-409a-93a9-64b8681dfc1f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:45:54.149Z"
    },
    {
        "id": "b2528023-5b23-43f2-9c5e-dba36c207219",
        "title": "The Love of Harshit",
        "author": "Jusifer",
        "genre": "Romance",
        "yearPublished": 2026,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:42:59.092Z"
    },
    {
        "id": "0242d3ed-e573-4357-9a54-2edf27f31db0",
        "title": "Harshit is Dalal",
        "author": "Jusifer",
        "genre": "Comedy",
        "yearPublished": 2026,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:39:59.859Z"
    },
    {
        "id": "4d486182-2644-430d-a34d-53d5fe033387",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:34:58.296Z"
    },
    {
        "id": "31438362-8b18-42b6-ba05-41436d700b08",
        "title": "Harshit is Dalal",
        "author": "Jusifer",
        "genre": "Comedy",
        "yearPublished": 2026,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:33:36.179Z"
    },
    {
        "id": "48b0e10e-ef9c-4eba-9a84-a64296db8f70",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:32:54.522Z"
    },
    {
        "id": "82b5d98e-3c08-430e-91d1-f52a280107c2",
        "title": "Yo Yeah",
        "author": "Jusifer",
        "genre": "Erotica",
        "yearPublished": 2025,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:27:37.123Z"
    },
    {
        "id": "c50e9646-eddb-4949-9087-6ddcecadd198",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:27:30.248Z"
    },
    {
        "id": "385cf650-9a1b-4670-8a44-92542e9285bc",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:22:32.873Z"
    },
    {
        "id": "0cbfed01-0a4f-44c4-ba39-075f422f2031",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:20:37.164Z"
    },
    {
        "id": "11db8556-60b3-40cd-94f9-04ceefcfa730",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:13:23.587Z"
    },
    {
        "id": "7212bb1d-8fbd-4203-8716-b8d661ebe403",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:12:27.629Z"
    },
    {
        "id": "cd7d99d3-f535-4b33-8646-feeafd2cc2d1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:09:15.150Z"
    },
    {
        "id": "157bcc66-e950-420b-9c28-428002e03f0d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:04:15.121Z"
    },
    {
        "id": "9346a398-37e1-48d2-af4e-fea3e4ff44f6",
        "title": "molestias totam debitis",
        "author": "Krista Crona Jr.",
        "genre": "tech",
        "yearPublished": 592,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:00:33.720Z"
    },
    {
        "id": "7cbfab44-b7ad-467c-a977-ad76a35a3b7b",
        "title": "dicta ut corrupti",
        "author": "Dr. Dolores Lebsack",
        "genre": "tech",
        "yearPublished": 550,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:00:33.665Z"
    },
    {
        "id": "871d51d2-6bde-414d-bcce-a8ed567f2de6",
        "title": "Et sed dolor tempora dolorem ullam officiis *** natus voluptates. Nihil animi rerum earum praesentium. Debitis eius excepturi voluptas quas enim. Veritatis unde nihil numquam et modi odio omnis dolores.",
        "author": "Hugo Breitenberg",
        "genre": "tech",
        "yearPublished": 50,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:00:33.590Z"
    },
    {
        "id": "2a76874b-261c-4bbf-ad1d-10d6159365a5",
        "title": "Et deserunt voluptas porro itaque qui. Neque iste minima libero *** exercitationem aliquid debitis. Atque deleniti aliquid hic vel ut. Quis blanditiis unde rem sequi aut et ad ea nobis. Dolore maxime provident similique.",
        "author": "Pat Jones",
        "genre": "tech",
        "yearPublished": 80,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T12:00:33.463Z"
    },
    {
        "id": "8f8d7052-6a99-4130-a138-bb69a4ab6cc1",
        "title": "HarryPotter3",
        "author": "Joan Roaling",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:59:26.286Z"
    },
    {
        "id": "50a41469-d181-4ad3-94f3-e6fba69eac3e",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:59:26.272Z"
    },
    {
        "id": "916bc56d-c52f-4cda-bab0-8c756ee03e09",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:54:11.116Z"
    },
    {
        "id": "c4dacb89-663b-4f87-8228-b0274758655f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:53:30.865Z"
    },
    {
        "id": "35760b1a-887a-4943-92e4-9b1527a6fd3c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:52:44.906Z"
    },
    {
        "id": "96e44498-09a0-46cd-ae89-a3b7522a0d32",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:49:02.854Z"
    },
    {
        "id": "b3dca8ff-7e1c-4b12-99d3-e4ed370ce3e0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:45:31.679Z"
    },
    {
        "id": "f024bb60-de6c-44c3-a768-ebeca523cad2",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:45:16.647Z"
    },
    {
        "id": "ad199cdc-f6ea-4f77-bd16-77f036b7e34d",
        "title": "HarryPotter2",
        "author": "Joan Roaling",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:43:39.150Z"
    },
    {
        "id": "41a6145f-b896-42cd-baf4-2329e8bd4e86",
        "title": "HarryPotter",
        "author": "Joan Roaling",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:39:53.881Z"
    },
    {
        "id": "f255baa4-4571-4527-955e-3d7e43bc0693",
        "title": "Harry Potter",
        "author": "Joan Roaling",
        "genre": "fiction",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:38:25.108Z"
    },
    {
        "id": "62074252-59ed-4e41-ab74-594b97a7271f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:33:43.144Z"
    },
    {
        "id": "7af36179-6f18-4e07-b617-d28d564bfb0a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:33:13.591Z"
    },
    {
        "id": "9258522e-9797-4ce9-827f-f47687ab41d9",
        "title": "Wodderful world",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:29:39.564Z"
    },
    {
        "id": "b5120fcd-76a2-49c4-a34f-1e88a248e1da",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:24:56.403Z"
    },
    {
        "id": "98f81e69-98b3-4b4c-9485-bf3005052ba0",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:23:22.256Z"
    },
    {
        "id": "876b8364-d106-4de2-b70e-d4a2c5908f2a",
        "title": "NonSense2",
        "author": "Mali Movie2",
        "genre": "True Events2",
        "yearPublished": 20132,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:20:26.892Z"
    },
    {
        "id": "59203eb8-2f88-4eec-b755-53370297f6f2",
        "title": "To Kill a Mockingbird",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:20:08.647Z"
    },
    {
        "id": "59d6dada-26e6-4ae9-b067-14c1a66a4ab7",
        "title": "To Kill a Mockingbird",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:13:47.177Z"
    },
    {
        "id": "6aefc97c-3dfe-4350-a112-11d4d8bdbde6",
        "title": "Hello World, my test doesn't work as planning",
        "author": "Fahd Al-Khulaifi",
        "genre": "fiction",
        "yearPublished": 2040,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:02:30.779Z"
    },
    {
        "id": "cb9079e0-f4a4-4c26-bd2f-0233e4bad3b8",
        "title": "Dolorum quo voluptate quam molestiae sed.",
        "author": "Max Macejkovic",
        "genre": "tech",
        "yearPublished": 545,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:01:40.941Z"
    },
    {
        "id": "5b86009e-e4f6-4728-8ad2-2ec003bb502a",
        "title": "laudantium beatae qui",
        "author": "David Hamill Jr.",
        "genre": "tech",
        "yearPublished": 697,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:01:40.815Z"
    },
    {
        "id": "8af58a9d-3814-4733-93e3-cc4836da95a3",
        "title": "Ut omnis dolorum dolore sunt omnis necessitatibus magnam soluta. Quae commodi rerum rem harum quo assumenda esse voluptatem. Iure ducimus doloremque labore eos autem placeat facilis ut doloremque.",
        "author": "Alonzo Lynch",
        "genre": "tech",
        "yearPublished": 544,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:01:40.630Z"
    },
    {
        "id": "db2e3331-5860-4f78-9e1a-049115eea483",
        "title": "Autem accusamus enim dolor delectus.",
        "author": "Simon Koepp",
        "genre": "tech",
        "yearPublished": 636,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T11:01:40.463Z"
    },
    {
        "id": "3238c497-7dc9-496a-9f61-e59bfb928973",
        "title": "Thw Wings Of Fire",
        "author": "Dr. APJ Abdul Kalam",
        "genre": "Biography",
        "yearPublished": 2001,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:29:46.475Z"
    },
    {
        "id": "9c54582f-1321-4edd-9905-bf0d52d686fc",
        "title": "Mahabharatham",
        "author": "Ganesha",
        "genre": "Legend",
        "yearPublished": -40000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:21:56.014Z"
    },
    {
        "id": "9e2f22b5-d5aa-442a-bd6b-5ad4f1339062",
        "title": "Demon Lord of the Deserted World 3",
        "author": "SAS House",
        "genre": "fiction",
        "yearPublished": 2026,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:20:59.895Z"
    },
    {
        "id": "0aab0784-4f09-46c7-8d09-1f27efe84d82",
        "title": "Ramayana",
        "author": "Valmiki",
        "genre": "Legend",
        "yearPublished": -70000,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:17:38.493Z"
    },
    {
        "id": "f2f8fc11-e326-469f-a8c1-36b4191edc67",
        "title": "Demon Lord of the Deserted World 2",
        "author": "SAS House",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:14:05.411Z"
    },
    {
        "id": "7c84bf15-8172-4e6b-8f96-5a82750f2feb",
        "title": "To Kill a Mockingbird2",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:13:17.988Z"
    },
    {
        "id": "ea702951-34ad-4155-8458-4197780076d6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:13:04.568Z"
    },
    {
        "id": "96b1e3e2-28c0-43c1-bad6-d2708e84d403",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:12:19.845Z"
    },
    {
        "id": "74226b24-ff3b-4c3c-a9d4-5fefa1fa9c6b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:12:02.189Z"
    },
    {
        "id": "d0490f8e-c1fe-4b46-9106-cbba70c20a21",
        "title": "Demon Lord of the Deserted World",
        "author": "SAS",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:10:32.608Z"
    },
    {
        "id": "9a8b08a8-3536-4d60-bd4d-f2b1db77d889",
        "title": "Demon Lord of the Deserted World",
        "author": "SAS",
        "genre": "fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:10:28.172Z"
    },
    {
        "id": "6b2f99b8-0116-4a1f-b94c-7eecc4755b3d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:08:45.077Z"
    },
    {
        "id": "25b84a3b-8836-407f-bf61-3db6902d83f6",
        "title": "Ut et aut est dolorum. Amet inventore nihil aperiam quae. Ipsa autem id tenetur non doloribus porro. Ducimus cupiditate harum id odio debitis.",
        "author": "Darrell Hayes",
        "genre": "tech",
        "yearPublished": 270,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:00:11.383Z"
    },
    {
        "id": "30d2e375-ebde-473d-b607-6c778d33a112",
        "title": "Laborum et qui. Sit et earum distinctio omnis. Nisi dolorum ut saepe qui ut inventore sapiente autem recusandae.",
        "author": "Robert Bins",
        "genre": "tech",
        "yearPublished": 373,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:00:11.123Z"
    },
    {
        "id": "e58421ce-895e-4715-a7d5-514456649415",
        "title": "Enim et rem. Ipsa consequuntur laboriosam. Veniam autem esse nihil quisquam eos corporis exercitationem exercitationem ipsa. Deserunt omnis magni magnam culpa. *** voluptatibus occaecati.",
        "author": "Krista Greenholt III",
        "genre": "tech",
        "yearPublished": 721,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:00:10.883Z"
    },
    {
        "id": "8298f4f4-5ab8-44d6-a461-bcc2e5c7562a",
        "title": "Sint magni dolorum.",
        "author": "Jerald Satterfield",
        "genre": "tech",
        "yearPublished": 417,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T10:00:10.413Z"
    },
    {
        "id": "c06b4e34-babc-400a-aae5-62b9b44d5eb3",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:49:02.032Z"
    },
    {
        "id": "a3cdd66e-0b2f-41c9-af98-d5486c5a5194",
        "title": "Onepiece",
        "author": "Oda",
        "genre": "fiction",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:44:37.263Z"
    },
    {
        "id": "fa52860f-08f4-4ba5-a65a-5ca6700a5eab",
        "title": "AOT",
        "author": "Eren",
        "genre": "fiction",
        "yearPublished": 2014,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:41:50.249Z"
    },
    {
        "id": "84cbba08-eef3-4e9e-a292-21c67fb298ea",
        "title": "Social syndrome",
        "author": "Jayanth Krishna",
        "genre": "Reality",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:24:48.246Z"
    },
    {
        "id": "f65377a2-a910-4e1a-8b93-11b3643eff5c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:19:42.797Z"
    },
    {
        "id": "46cecd70-5067-4125-8e7a-5ffcd6a22657",
        "title": "sunt",
        "author": "Tomas Brakus",
        "genre": "tech",
        "yearPublished": 888,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:19:29.778Z"
    },
    {
        "id": "0a59485d-22a5-4b41-b646-3b7d546656fd",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:09:48.254Z"
    },
    {
        "id": "2590e34e-2564-43ab-8d26-3149750ea9ed",
        "title": "The Four Agreements",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:07:16.782Z"
    },
    {
        "id": "12cda96c-5b72-4e5b-818c-7e9495c40140",
        "title": "Labore aut est quibusdam. Ducimus sit sed molestiae sint est et. Qui sed non quia similique ut pariatur. Aliquam dolor libero aliquam tempora molestiae suscipit autem expedita. Iusto nobis libero et et veniam quo.",
        "author": "Harry Balistreri",
        "genre": "tech",
        "yearPublished": 718,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:00:51.922Z"
    },
    {
        "id": "9661c3b5-fe31-4661-94c5-4e7d4b6c795c",
        "title": "Dolor debitis omnis quae officia amet dolores inventore ea doloribus.",
        "author": "Jessica Hodkiewicz",
        "genre": "tech",
        "yearPublished": 446,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T09:00:51.767Z"
    },
    {
        "id": "c95c1d27-a065-4af2-8715-b8444a4f598d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:52:12.733Z"
    },
    {
        "id": "dfa74b90-752f-4689-b5fd-a495ba7561d6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:50:47.512Z"
    },
    {
        "id": "731e7af4-9740-4d87-a79b-b38ac20c043c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:46:25.820Z"
    },
    {
        "id": "7486a23e-f848-4bf2-a2bb-5fc78facbec1",
        "title": "ABCD",
        "author": "XYZ",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:04:53.861Z"
    },
    {
        "id": "4c9d2abc-cdf3-47d6-a447-a77dcc460e04",
        "title": "ABCD",
        "author": "XYZ",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:04:01.663Z"
    },
    {
        "id": "2c01dfc0-bdfa-4714-8637-338df4587279",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:01:48.314Z"
    },
    {
        "id": "436469db-1782-4c53-9131-f5c1904671d5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:01:39.649Z"
    },
    {
        "id": "b41d66e9-fb97-4ef3-b800-f86b72fda99c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:00:47.752Z"
    },
    {
        "id": "f5e1bd6f-8c54-47ff-ad62-f2d91b0d25e5",
        "title": "qui",
        "author": "Renee Mitchell",
        "genre": "tech",
        "yearPublished": 501,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:00:32.648Z"
    },
    {
        "id": "b793a676-ca48-455f-8611-ffa5338955f8",
        "title": "Est aliquid pariatur eligendi similique. Nihil voluptas quisquam. Provident blanditiis eligendi officiis quod assumenda est temporibus explicabo quibusdam. Est dolorem aliquid veritatis dolore. Ratione libero ab et.",
        "author": "Mr. Sylvia Rosenbaum",
        "genre": "tech",
        "yearPublished": 820,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:00:32.599Z"
    },
    {
        "id": "d9172099-7b4f-4f07-8942-4f1fddabbb00",
        "title": "voluptatibus",
        "author": "Daisy Romaguera",
        "genre": "tech",
        "yearPublished": 248,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:00:32.460Z"
    },
    {
        "id": "39db2c8b-5dcd-4679-8ef0-ec2514c627f4",
        "title": "Ut vel natus est.",
        "author": "Malcolm Jenkins",
        "genre": "tech",
        "yearPublished": 104,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T08:00:32.382Z"
    },
    {
        "id": "c5d289ae-b9dc-484f-80fb-f5a622d6203c",
        "title": "Entreprenuer",
        "author": "gitesh",
        "genre": "non-fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:53:41.796Z"
    },
    {
        "id": "59c051b9-2e16-4f4e-8734-3ceb1e69846b",
        "title": "5 Things you shouldn't do as a senior programmer",
        "author": "Fahd Al-Khulaifi",
        "genre": "fiction",
        "yearPublished": 2040,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:36:03.623Z"
    },
    {
        "id": "30362d04-7af4-4d54-b324-e88b793806f6",
        "title": "Entreprenuer",
        "author": "gitesh",
        "genre": "non-fiction",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:34:24.367Z"
    },
    {
        "id": "c5038f31-41f3-48f4-b072-c453b8ad4ea5",
        "title": "The champ",
        "author": "Harper Lee",
        "genre": "fictionss",
        "yearPublished": 1968,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:24:23.911Z"
    },
    {
        "id": "a92e6c7a-352c-4d15-9362-2c154c787d49",
        "title": "To Kill a Mockingbird",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:17:42.156Z"
    },
    {
        "id": "9f6d31d3-0147-45e6-ba0c-5adab38e2fec",
        "title": "AI/ML",
        "author": "Saltman",
        "genre": "fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:13:55.856Z"
    },
    {
        "id": "6c39c23d-36b1-4b03-aa08-65d3edea9a0a",
        "title": "The way to success`",
        "author": "Fahd Al-Khulaifi",
        "genre": "fiction",
        "yearPublished": 2040,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:12:31.280Z"
    },
    {
        "id": "8029af6d-4f5d-4d47-9320-8ac83b5e5a09",
        "title": "To Kill a Mockingbird",
        "author": "Harper",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:11:30.855Z"
    },
    {
        "id": "017c779a-b301-4710-bd94-fb98108339f5",
        "title": "The way to greatness`",
        "author": "Fahd Al-Khulaifi",
        "genre": "fiction",
        "yearPublished": 2040,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:07:18.882Z"
    },
    {
        "id": "dd616b8f-d42f-4005-9063-f40042146ab5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:04:41.292Z"
    },
    {
        "id": "d53e4e88-b235-44b4-a845-3600366cc8e5",
        "title": "Porro eveniet beatae aut laboriosam explicabo. Et quisquam nobis. Qui qui nesciunt est nulla dolore. Sint blanditiis quod quidem enim in porro hic.",
        "author": "Mrs. Javier Langosh",
        "genre": "tech",
        "yearPublished": 400,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:54.589Z"
    },
    {
        "id": "134eb5f5-521e-4eb6-afce-04ae5f09e023",
        "title": "In voluptatibus ut id accusantium hic.",
        "author": "Roger Conroy Jr.",
        "genre": "tech",
        "yearPublished": 554,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:54.380Z"
    },
    {
        "id": "03d9712c-5b2c-4242-9f1a-e773c48e86bd",
        "title": "Optio in sed ad facilis qui reiciendis officiis aut minima. Aliquam sapiente corrupti voluptate. Et quos aliquam omnis. Provident animi enim consequatur corporis dolor tempora.",
        "author": "Wilbert Hartmann Sr.",
        "genre": "tech",
        "yearPublished": 27,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:54.268Z"
    },
    {
        "id": "c9b30980-a054-471f-8c8f-5924e50615f4",
        "title": "Visionary dedicated parallelism",
        "author": "don Miguel Ruiz",
        "genre": "self-help",
        "yearPublished": 1997,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:39.169Z"
    },
    {
        "id": "be6d7079-5982-45e3-a002-8ddbc972bfdd",
        "title": "Fue un privilegio estar aqui",
        "author": "Melva Frias Vda. Carrillo",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:11.296Z"
    },
    {
        "id": "3c737242-7417-4a3a-a865-4439e0b81215",
        "title": "Las sagas de Potter",
        "author": "Josepi LucasMoi",
        "genre": "Accion",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T07:01:10.854Z"
    },
    {
        "id": "01b05be0-321d-4315-8a2f-ee78bcee0b5f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:59:19.369Z"
    },
    {
        "id": "e068dc78-f209-4e92-8fce-2df42e0a4f1c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:57:58.197Z"
    },
    {
        "id": "1bce6625-35bd-4055-99ea-cff960ad3e09",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:56:42.924Z"
    },
    {
        "id": "071812c9-a3dd-47ec-b76c-5b1f34a4e16f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:52:00.983Z"
    },
    {
        "id": "0cc4d883-42d8-4ceb-ae25-05b69621135a",
        "title": "2 states",
        "author": "Chetan Bhagat",
        "genre": "fiction",
        "yearPublished": 2009,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:51:25.583Z"
    },
    {
        "id": "0db5d82d-53f9-4aad-8a50-cb63fccf0b2d",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:49:30.704Z"
    },
    {
        "id": "382c5c2f-1959-422b-840c-0ae603cc455a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:48:49.551Z"
    },
    {
        "id": "fd7702f3-13e7-4c53-bd91-4b71a707be39",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:43:58.614Z"
    },
    {
        "id": "4b1d55cc-8f45-48ec-b052-596f2cd47821",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:34:31.268Z"
    },
    {
        "id": "7782c08a-8963-44af-b4cf-57d0d343e3ba",
        "title": "New Book",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1999,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:34:16.057Z"
    },
    {
        "id": "ce69d6f4-00ad-4e81-9fc8-d4319ac28d25",
        "title": "New Book",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:34:01.842Z"
    },
    {
        "id": "ec2a9776-5891-40b5-9b50-a2efeb1a3864",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:33:06.512Z"
    },
    {
        "id": "b6490251-33a3-4430-b861-97ac6381534c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:32:22.903Z"
    },
    {
        "id": "8a965ea9-aaf2-4805-ab26-8b490b87f569",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:28:47.247Z"
    },
    {
        "id": "47d4f725-63ec-4263-8586-0d632ac9686c",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:22:11.762Z"
    },
    {
        "id": "6ebba631-042b-44cc-929c-cfaa28113c7c",
        "title": "The Death of Evelyn Sanchez Mendeleiv",
        "author": "Marcus Johnson",
        "genre": "fiction",
        "yearPublished": 1977,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:21:35.712Z"
    },
    {
        "id": "b41e0c86-ced1-43f1-8b2e-ce7482176453",
        "title": "The Death of Evelyn Sanchez Mendeleiv",
        "author": "Marcus Johnson",
        "genre": "fiction",
        "yearPublished": 1977,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:21:26.764Z"
    },
    {
        "id": "cb4308c9-306e-4923-8058-bd7485da8771",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:20:11.843Z"
    },
    {
        "id": "9bede2e8-efd1-4c08-87db-d2eee48c2580",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:20:04.223Z"
    },
    {
        "id": "3704058c-85fe-4703-8f23-399e37e33210",
        "title": "The Death of Evelyn Sanchez Mendeleiv",
        "author": "Marcus Johnson",
        "genre": "fiction",
        "yearPublished": 1977,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:19:06.929Z"
    },
    {
        "id": "f2349e33-5f24-42f4-85f2-8bd945faae3e",
        "title": "Harry Potter",
        "author": "J.K Rowling",
        "genre": "fiction",
        "yearPublished": 1990,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:19:01.575Z"
    },
    {
        "id": "97d9c100-a4ca-4428-b607-09894951469a",
        "title": "To Kill a Mockingbird",
        "author": "Sourav",
        "genre": "workshop",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:15:36.653Z"
    },
    {
        "id": "90406de5-c90e-4899-9929-4271601bf74f",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:13:52.228Z"
    },
    {
        "id": "71605271-d24d-4eeb-b741-08d3bf4b944e",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:13:45.509Z"
    },
    {
        "id": "eca3cc6f-6cdc-4f36-8443-3a82554c3bf1",
        "title": "To Kill a Mockingbird",
        "author": "Sourav",
        "genre": "workshop",
        "yearPublished": 2023,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:04:56.399Z"
    },
    {
        "id": "f5b2ede2-0c00-45ea-a3b9-a63331a96ae6",
        "title": "To Kill a Mockingbird",
        "author": "Sourav",
        "genre": "workshop",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:02:23.297Z"
    },
    {
        "id": "bbf0d3f5-db39-4822-aaee-a982ada96614",
        "title": "sint",
        "author": "Nancy Emard",
        "genre": "tech",
        "yearPublished": 838,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:01:35.796Z"
    },
    {
        "id": "4b14fc47-92e7-4e70-b1c7-0f30146ca71b",
        "title": "sequi quod molestiae",
        "author": "Ms. Alyssa Kuhlman",
        "genre": "tech",
        "yearPublished": 127,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:01:35.707Z"
    },
    {
        "id": "110b31bc-8ae2-4174-9fea-112072ec7d37",
        "title": "Veniam tempora necessitatibus recusandae repellat repellendus harum ullam soluta dignissimos.",
        "author": "Jessie Kihn",
        "genre": "tech",
        "yearPublished": 843,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:01:35.661Z"
    },
    {
        "id": "f47280c3-4ea6-4db2-ad57-7031cd555c90",
        "title": "adipisci",
        "author": "Rudolph Shanahan",
        "genre": "tech",
        "yearPublished": 896,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:01:35.592Z"
    },
    {
        "id": "4ff53c12-db54-4ba8-9f0a-fed266085c40",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T06:00:12.799Z"
    },
    {
        "id": "7fc64114-c029-4783-addf-e082734c212b",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:54:17.512Z"
    },
    {
        "id": "562e48af-5f69-4df6-8c07-f0ada0774dc7",
        "title": "Atomic Habits",
        "author": "James Clear",
        "genre": "fiction",
        "yearPublished": 2021,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:41:46.140Z"
    },
    {
        "id": "ad5bf34f-80c2-4ed5-892a-6df8c282c3f6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:32:37.388Z"
    },
    {
        "id": "9aeb33d1-ec14-4bf8-80e9-91867348dce8",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:22:11.069Z"
    },
    {
        "id": "ae1a0b83-ca06-45d8-a005-926c622e8ffd",
        "title": "To",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:18:41.633Z"
    },
    {
        "id": "3d604644-fe02-463a-8b27-1474ea14ab11",
        "title": "To",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:13:03.875Z"
    },
    {
        "id": "7a440f72-02ce-4d07-885b-9dda5ce763c1",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:12:57.440Z"
    },
    {
        "id": "3419f7c9-4384-4add-8b0a-124d6f91b56a",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:09:27.291Z"
    },
    {
        "id": "2d672e5d-60ea-4c85-84f4-6a5569445d69",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:06:00.188Z"
    },
    {
        "id": "f99086dd-6e53-4ed5-8889-931c7e306e60",
        "title": "Earum corrupti fugit. Doloribus voluptate autem itaque et est molestias nesciunt quo. Amet saepe provident omnis.",
        "author": "Forrest Schiller",
        "genre": "tech",
        "yearPublished": 919,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:01:15.552Z"
    },
    {
        "id": "7ec9a975-aa24-4e2f-8b34-ab0614ddd967",
        "title": "omnis deserunt non",
        "author": "Amelia Funk",
        "genre": "tech",
        "yearPublished": 626,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:01:15.090Z"
    },
    {
        "id": "235d4e65-c838-4414-8e00-588cf463c008",
        "title": "Temporibus rerum laborum aut.",
        "author": "Lillie Dooley",
        "genre": "tech",
        "yearPublished": 910,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:01:14.807Z"
    },
    {
        "id": "76d45f80-876f-4fda-a978-6a59a7e77db8",
        "title": "placeat hic commodi",
        "author": "Nellie Schinner",
        "genre": "tech",
        "yearPublished": 108,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T05:01:14.438Z"
    },
    {
        "id": "661b47eb-b183-4ed5-b9fb-45355685daba",
        "title": "Don't Let the Pigeon Drive the Bus",
        "author": "Mo Willems",
        "genre": "fiction",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:44:14.052Z"
    },
    {
        "id": "751cd304-37fc-4ffc-91e7-b9f3c4d52eb1",
        "title": "Do Epic ****",
        "author": "Ankur Warikoo",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:31:13.016Z"
    },
    {
        "id": "58c17bdc-19ab-4e3d-91fb-68d736a1193f",
        "title": "I'm Glad My Mom Died",
        "author": "Jennette McCurdy",
        "genre": "autobiography",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:30:09.115Z"
    },
    {
        "id": "8892b2f4-4976-499d-88db-3aefac7b781a",
        "title": "Do Epic ****",
        "author": "Ankur Warikoo",
        "genre": "fiction",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:26:38.385Z"
    },
    {
        "id": "3970b4a4-9958-4955-9e7e-f6a59ac30b32",
        "title": "Waypoints: My Scottish Journey",
        "author": "Sam Heughan ",
        "genre": "autobiography",
        "yearPublished": 2022,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:23:28.877Z"
    },
    {
        "id": "42f0131c-0a78-47b6-8966-b85a205da002",
        "title": "Assumenda molestias exercitationem porro aut accusantium qui et necessitatibus voluptate. Voluptate qui ducimus vero. Inventore tenetur et accusamus dolorem. Nostrum eos aut.",
        "author": "Luke Hoppe DDS",
        "genre": "tech",
        "yearPublished": 980,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:01:40.678Z"
    },
    {
        "id": "88738c34-ef0b-4e07-b30d-d0f47698d592",
        "title": "Voluptas amet consequuntur sunt tempora non commodi est.",
        "author": "Muriel Olson",
        "genre": "tech",
        "yearPublished": 881,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:01:40.553Z"
    },
    {
        "id": "b4729874-74d1-48e2-89d5-d0974e6ca4c1",
        "title": "Nam praesentium provident. A voluptas qui blanditiis est officia sed nihil quas sit.",
        "author": "Bonnie Wehner",
        "genre": "tech",
        "yearPublished": 712,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:01:40.458Z"
    },
    {
        "id": "e7af85fe-6e82-4277-adaa-70c768f2766e",
        "title": "et maiores illum",
        "author": "Belinda Maggio",
        "genre": "tech",
        "yearPublished": 459,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T04:00:30.243Z"
    },
    {
        "id": "f082cc2d-1200-40f3-8930-0dc22509fa07",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:48:20.825Z"
    },
    {
        "id": "f5727478-5f78-4b79-8669-a47b4ca2b38b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:45:48.229Z"
    },
    {
        "id": "7780ee43-4dff-4d12-bc71-aae1c3487287",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:45:26.699Z"
    },
    {
        "id": "3a44e6e2-b40f-4938-829c-d92c2ef6cee3",
        "title": "Git hub in action",
        "author": "Braise",
        "genre": "development",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:31:28.035Z"
    },
    {
        "id": "569fe9ef-9d2f-48bf-bf5d-1d839db4f7cf",
        "title": "Git hub in action",
        "author": "Braise",
        "genre": "development",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:29:54.534Z"
    },
    {
        "id": "d0903e9f-2be0-4e47-99b0-b47ce24b92c1",
        "title": "Git hub in action",
        "author": "Braise",
        "genre": "development",
        "yearPublished": 2023,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:17:48.148Z"
    },
    {
        "id": "e28a5b5b-9fb9-46d1-94c7-c0af60da5f4f",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:15:37.840Z"
    },
    {
        "id": "fe3a5158-a12a-4741-8e27-97a6a54b2fd6",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:12:04.143Z"
    },
    {
        "id": "b39e33ae-ff4b-48cc-8ce3-0326b6bba400",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:11:28.825Z"
    },
    {
        "id": "0c5a0a8c-63dd-4d84-b529-4bea21e9826b",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:10:49.037Z"
    },
    {
        "id": "7b2e75fc-66c9-4f9b-9773-07489a3f40f3",
        "title": "dolorem",
        "author": "Everett Toy",
        "genre": "tech",
        "yearPublished": 454,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:02:06.229Z"
    },
    {
        "id": "b1cc9e26-c517-4002-a060-cfdd553e4c20",
        "title": "Veniam saepe sunt. Fugiat eum sit quod impedit. Aut et vero quis iste. Aliquam quidem perferendis explicabo qui deserunt quia libero. Optio est dolorem enim asperiores aliquam inventore soluta sunt. Nihil aut quia quasi corporis id.",
        "author": "Gerardo Russel",
        "genre": "tech",
        "yearPublished": 137,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:02:06.172Z"
    },
    {
        "id": "aec9cfd2-c644-439a-bee6-40673ca3c940",
        "title": "Culpa sed mollitia aut blanditiis ut laborum velit. Excepturi dolore ipsum sapiente sed eligendi. Non nulla quia ex explicabo sit voluptas reprehenderit quisquam consequatur. Et qui et aperiam.",
        "author": "Sonja Mayer V",
        "genre": "tech",
        "yearPublished": 918,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T03:02:05.976Z"
    },
    {
        "id": "33a6f9e4-2bf1-40bf-893c-d63949e94846",
        "title": "Vel dolores sit libero sunt voluptas.",
        "author": "Marcos O'Kon",
        "genre": "tech",
        "yearPublished": 3,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T02:00:33.225Z"
    },
    {
        "id": "7d980480-459f-417b-8b7f-4ce9b6e788a5",
        "title": "Illum et velit quod officiis et libero quas est reiciendis.",
        "author": "Vicki Romaguera",
        "genre": "tech",
        "yearPublished": 794,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T02:00:33.049Z"
    },
    {
        "id": "292c671a-279d-4c22-9cd2-564d66fc91a5",
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": true,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:57:58.287Z"
    },
    {
        "id": "d9d6f361-34b5-49ef-990c-1ab76c42b2ce",
        "title": "To Kill a Mockingbird 1",
        "author": "Harper Lee",
        "genre": "fiction",
        "yearPublished": 1960,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:57:47.186Z"
    },
    {
        "id": "d5cb0067-8cee-44e0-bf48-8c35a13d41af",
        "title": "Asperiores omnis nihil ducimus omnis aliquam impedit qui. Eius et aliquid officia quaerat laudantium rerum. Sunt commodi eos ea. Dolorum sit quos vel unde ut molestiae et molestias pariatur. Minus excepturi ad occaecati enim sed ***. Id quasi et facilis.",
        "author": "Dixie Becker",
        "genre": "tech",
        "yearPublished": 450,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:00:56.838Z"
    },
    {
        "id": "183203b9-75df-4aa5-a13d-e6f7caa6fb1f",
        "title": "Velit velit voluptas rerum est eum tempora dolores.",
        "author": "Shelia Larkin",
        "genre": "tech",
        "yearPublished": 284,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:00:56.721Z"
    },
    {
        "id": "eac47363-31e8-47c1-94aa-d875d1942c38",
        "title": "Omnis eveniet vero.",
        "author": "Nick Crooks",
        "genre": "tech",
        "yearPublished": 27,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:00:56.628Z"
    },
    {
        "id": "3df10201-663e-40c3-9606-e9a465d2b019",
        "title": "Et illo natus vel. Ex ea rerum aspernatur. Voluptate dolorem quibusdam velit nulla quas. Et quia voluptatem ut et saepe. Sint sit et quibusdam aut et minima.",
        "author": "Lee Krajcik",
        "genre": "tech",
        "yearPublished": 344,
        "checkedOut": false,
        "isPermanentCollection": false,
        "createdAt": "2023-09-12T01:00:56.578Z"
    },
    {
        "id": "539f89ed-df63-469c-94ce-157e75366dec",
        "title": "Domain-Driven Design: Tackling Complexity in the Heart of Software",
        "author": "Eric Evans",
        "genre": "computers",
        "yearPublished": 2003,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "03daae04-c778-45fb-9acb-4c6d19067a9c",
        "title": "Go Design Patterns",
        "author": "Mario Castro Contreras",
        "genre": "computers",
        "yearPublished": 2017,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "85a5424d-535d-48a9-a163-8627b84662d7",
        "title": "Continuous API Management: Making the Right Decisions in an Evolving Landscape",
        "author": "Mehdi Medjaoui, Erik Wilde, Ronnie Mitra, Mike Amundsen",
        "genre": "computers",
        "yearPublished": 2018,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "6562ce4e-86c1-43f1-bbfe-3fc7a53d80a6",
        "title": "A Practical Approach to API Design",
        "author": "D. Keith Casey Jr, James Higginbotham",
        "genre": "computers",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "7c408f6f-144f-4d16-b6ab-57d749d8efe0",
        "title": "Colorless Tsukuru Tazaki and His Years of Pilgrimage",
        "author": "Haruki Murakami",
        "genre": "fiction",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "820271be-0013-4698-8639-5bf41f104ca1",
        "title": "Consolation of Philosophy",
        "author": "Boethius",
        "genre": "philosophy",
        "yearPublished": 524,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "53a37668-c99f-46f9-af00-c582924f422b",
        "title": "RESTful Web APIs: Services for a Changing World",
        "author": "Leonard Richardson, Mike Amundsen, Sam Ruby",
        "genre": "computers",
        "yearPublished": 2013,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "ab150479-b509-4ab6-af86-489047db85fd",
        "title": "The Aleph",
        "author": "Jorge Luis Borges",
        "genre": "fiction",
        "yearPublished": 1949,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "14b533eb-5ef3-422a-b037-7b6161ee7020",
        "title": "Crime and Punishment",
        "author": "Fyodor Dostoyevsky",
        "genre": "fiction",
        "yearPublished": 1866,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "50b1a8e9-78f0-4a80-b350-8fdf8fb1b8b8",
        "title": "A Thousand Splendid Suns",
        "author": "Khaled Hosseini",
        "genre": "fiction",
        "yearPublished": 2007,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "29cd820f-82f9-4b45-a7f4-0924111b5b89",
        "title": "Ficciones",
        "author": "Jorge Luis Borges",
        "genre": "fiction",
        "yearPublished": 1944,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    },
    {
        "id": "47bb8b2b-79ec-4bac-955c-af471a0e53c8",
        "title": "Beyond Violence",
        "author": "Jiddu Krishnamurti",
        "genre": "philosophy",
        "yearPublished": 1973,
        "checkedOut": false,
        "isPermanentCollection": true,
        "createdAt": "2022-03-30T00:54:52.606Z"
    }
]```

