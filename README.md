## JSON-SERVER
> npm: json-server

### Schemas
`Posts`-> /schemas/posts.ts
`Users`-> /schemas/users.ts
`Todos`-> /schemas/todos.ts

### DB's
`Posts`-> /db/posts.json
`Users`-> /db/users.json
`Todos`-> /db/todos.json

### Transform json to schema
> plugin vscode: Past JSON as Code

1. Select a part of json file
```sh
{
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}
````

2. Selec from command tool > Open quicktype for JSON Schema

3. That will create a new interface schema.

### Open URI
http://localhost:3000/


### GET Data with Postman
