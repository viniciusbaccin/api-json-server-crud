# api-json-server-crud
JSON server simulando uma API para projeto Quasar CRUD

## Install

```shell
npm install json-server
```

## Usage

Create a `db.json` file

```json
{
  "posts": [
    {
      "id": "1",
      "title": "Título",
      "author": "Nome do Autor",
      "content": "Conteúdo do post"
    },
  ]
}
```

Pass it to JSON Server CLI

```shell
$ npx json-server db.json
```

Get a REST API

```shell
$ curl http://localhost:3000/posts/1
{
  "id": "1",
  "title": "Construindo Aplicações com Quasar Framework",
  "author": "Nome do Autor",
  "content": "Explore os recursos do Quasar Framework e aprenda a construir aplicações web modernas e responsivas."
},
```

Run `json-server --help` for a list of options
