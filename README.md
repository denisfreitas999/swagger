# Curso Swagger

## Swagger Links

[Swagger Design|Build|Document](https://swagger.io/tools/open-source/)

[Swagger Editor Online](https://editor.swagger.io/)

## Baixando e utilizando o Swagger Editor com Docker
```
docker pull swaggerapi/swagger-editor
docker run -p 80:8080 -v $(PWD):/tmp -e SWAGGER_FILE=/tmp/swagger.yaml swaggerapi/swagger-editor
```

## Baixando e utilizando o Swagger UI com o Docker
```
docker pull swaggerapi/swagger-ui
docker run -p 80:8080 -e SWAGGER_JSON=/tmp/swagger.json -v ${PWD}:/tmp swaggerapi/swagger-ui
```

## Mock API

[Mock API](https://mockapi.io/)
