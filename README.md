# GraphQL JSONPlaceholder

[![Build Status](https://img.shields.io/travis/mastertinner/graphql-jsonplaceholder.svg?style=flat-square)](https://travis-ci.org/mastertinner/graphql-jsonplaceholder)
[![Docker Build](https://img.shields.io/docker/cloud/build/mastertinner/graphql-jsonplaceholder.svg?style=flat-square)](https://hub.docker.com/r/mastertinner/graphql-jsonplaceholder)

A sample GraphQL implementation for the [JSONPlaceholder API](https://jsonplaceholder.typicode.com/).

## Run for local development

1. Run `npm install`
1. Run `npm run start:dev`

## Compile and run in production

1. Run `npm install`
1. Run `npm run build`
1. Run `NODE_ENV=production npm start`

## Build Docker image

The image is available on [Docker Hub](https://hub.docker.com/r/mastertinner/graphql-jsonplaceholder/)

1. Run `npm run build:docker`
