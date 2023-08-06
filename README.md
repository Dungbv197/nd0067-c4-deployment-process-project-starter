# Hosting a Full-Stack Application

---

## Description
The application get to Udacity. After build and deploy to AWS with pipeline using CricleCI.

## Project Setup
1. Clone the project: `https://github.com/udacity/nd0067-c4-deployment-process-project-starter`
2. Go into the project directory: `cd/udagram/udagram-frontend`
3. Install the dependencies: `pm install`
4. Run build FE: `npm run build`
5. Start the FE: `npm run start`
6. Open new terminal: `cd ../udagram-api`.
7. Add and setup to file `.env`
8. Install the dependencies: `npm install`
9. Start the backend: `npm run start` or `npm run prod`


## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
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


## Documentation
- Screenshots of the AWS configurations and the CircleCI are provided in. `./Docs/Screenshort/`.
- Architecture Diagrams of the AWS and the Pipeline are provided in `./Docs/Architecture Diagrams/`.
