# Deploying Graphql Server on Heroku
This repo contains a basic Mongo Express GraphQL Node (MEGN) example code.

## Pre-requisites
- NodeJS
- Mongodb and server should be running if local

## Setup
- Clone this repo
- Run `yarn` or `npm install` from the cloned directory
- Run `yarn start` or `npm start` to start the graphql server on 3000 port by default.

## Demo
Launch [https://graphql-heroku.herokuapp.com/](https://graphql-heroku.herokuapp.com/?operationName=Users&query=query%20Users%20%7B%0A%20%20users%20%7B%0A%20%20%20%20name%0A%20%20%20%20password%0A%20%20%7D%0A%7D%0A%0Amutation%20addUser%20%7B%0A%20%20addUser(input%3A%20%7B%0A%20%20%20%20name%3A%20%22Vimal%22%2C%0A%20%20%20%20password%3A%20%22secret%22%0A%20%20%7D)%20%7B%0A%20%20%20%20name%0A%20%20%20%20password%0A%20%20%7D%0A%7D) to access the GraphiQL.
