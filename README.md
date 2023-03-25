# udagram-udacity

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

###The project is available at
http://udagram-bucket1332023.s3-website-us-east-1.amazonaws.com/home

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

Amazon Web Services:
- S3 (udagram-frontend) was used for hosting and posts
- Elastic Beanstalk was used for the API (udagram-api) 
- RDS was used for the `PostgreSQL` database 

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd udagram/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework


## Installation

Run `npm install` to download the necessary dependencies.

## Running Udagram locally

You will need to create a `.env` file in `udagram-api` with the following variables set:
- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY
- JWT_SECRET
- POSTGRES_DB
- POSTGRES_HOST
- POSTGRES_PASSWORD
- POSTGRES_PORT
- POSTGRES_USERNAME
- PORT 
- URL

Run below commands in your terminal:
1. Navigate to `udagram-api` and run `npm run dev`
2. Navigate to `udagram-frontend` and run `npm run start`

Open `http://localhost:4200` in the browser.

