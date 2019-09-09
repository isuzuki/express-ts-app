# Overview
Express and TypeScript app

## Prerequisites
| Software | Install |
| --- | --- |
| yarn | https://yarnpkg.com/en/docs/install |


## Run
### local
```sh
yarn dev
```

### openapi generate
```sh
 docker run --rm -v {$PWD}:/local openapitools/openapi-generator-cli generate -i /local/openapi.yml -g nodejs-express-server -o /local/out/
```