# Skeleton project for Swagger
# swagger 2 doc
# https://swagger.io/docs/specification/2-0/describing-request-body/

`YAML file is located at api/swagger/swagger.yaml`

## Install swagger
```bash
 npm install -g swagger
```

## Create project
```bash
 swagger project create node-swagger
```

## Run dynamic swagger editor

```bash
 swagger project edit
```

## Controller code in Node.js

 API's business logic in Node.js.
 [controllers](./api/music.js)

```js

module.exports.getAllArtists = () => {
    res.json([{
            name: "Don",
            title: "dons"
        },
        {
            name: "Don L",
            title: "test 123"
        },
        {
            name: "Test",
            title: "no title"
        }
    ]);
}

```
