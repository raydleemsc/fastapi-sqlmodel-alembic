# FastAPI + SQLModel + Alembic

### from [TestDriven Blog of FastAPI SQLModel](https://testdriven.io/blog/fastapi-sqlmodel/)

## Clone
``` BASH
git clone -b base https://github.com/testdrivenio/fastapi-sqlmodel-alembic
cd fastapi-sqlmodel-alembic
```

## Build
``` BASH
docker-compose up -d --build
```

## Test
``` BASH
curl -X 'GET' 'http://localhost:8004/ping' -H 'accept: application/json'
```

## Response
``` JSON
{"ping":"pong!"}
```