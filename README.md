# Ejecutar comandos docker

## DynamoDB Local
docker run --rm -it -p 8000:8000 amazon/dynamodb-local

## LocalStack
docker run --rm -it -p 4566:4566 -p 4571:4571 localstack/localstack
