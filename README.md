# DynamoDB local persistent with interface

## Usage

Obs: **Docker and docker-compose is necessary**

### Up container

Clone repo
```shell
  git clone https://github.com/ellyofreitas/dynamodb-local-persistent
```

Create a folder for the persisting data and set permissions
```shell
  mkdir data && chmod 755 data -R
```

Execute container
```shell
  docker-compose up --build --force-recreate -d
```

### Interface

The interface is provided by npm package [dynamodb-admin](https://www.npmjs.com/package/dynamodb-admin)

For usage, access [localhost:8001](http://localhost:8001)
