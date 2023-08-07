# Udagram Pipeline

![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/dungbv4.jits/Documents/Learning/Udacity/lasttest/nd0067-c4-deployment-process-project-starter/Docs/Architecture%20Diagrams/Pipeline_Architecture_Diagram.drawio.png?version%3D1691290411819)

## Continuous Integration
### GitHub
Commit and push code to CricleCI GitHub repository.
When code push to GitHub, it activates the CricleCI.

### CricleCI
CricleCI read to file `./cricleci/config.yml`. Cricleci will perform any tasks.
#### Build
##### Frontend
- Install dependencies.
- Build the angular.
#### Backend
- Install dependencies.
- Build the node js.
### Setup ENV
- Setting Env Variables.
### Deploy
##### Frontend
- Deploy the site to AWS S3.
#### Backend
- Deploy the application to AWS Elastic Beanstalk