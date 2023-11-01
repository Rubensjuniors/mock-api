## Getting started

Install JSON Server

```
npm install
```

customize the `server.json` file however you want

```json
{
  "posts": [
    { "id": 1, "title": "um titulo" }
  ],
  "comments": [
    { "id": 1, "body": "um post", "postId": 1 }
  ],
  "profile": { "name": "Otavio" }
}
```

Start mock API server

```bash
npm run json-server
```

more information in the JSON SERVER documentation
(https://github.com/typicode/json-server)