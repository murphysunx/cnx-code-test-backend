# Connexion fullstack developer code test

This is the backend part of connexion fullstack developer code test, which is built with Nodejs.

You can clone this project and run `yarn install` to install this project locally.
To run it locally, run `yarn watch` and `yarn dev`.
To run unit tests of this project, run `yarn test:unit`.

Also, it's deployed on AWS lambda, so you can visit it via the following endpoints.

#Endpoints
[GET - https://ud9fscxo84.execute-api.us-east-1.amazonaws.com/latest/dealers](https://ud9fscxo84.execute-api.us-east-1.amazonaws.com/latest/dealers) for get list of dealers.
[GET - https://ud9fscxo84.execute-api.us-east-1.amazonaws.com/latest/vehicles/{bac}] for get vehicles under one dealer.
