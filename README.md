# Backend NestJS

## Run on local

```sh
# install dependencies
npm i

# copy environment variable
cp .env-example .env

# run
npm run start:dev
```

## Run with Docker

```
docker build -t test .
docker run -p 3000:3000 test
```

## Setup environment

https://labs.iximiuz.com/playgrounds/docker/

github action variable

```
DOCKER_IMAGE

DOCKER_PASSWORD

DOCKER_USERNAME
```
