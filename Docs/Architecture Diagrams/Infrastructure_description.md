# Udagram infrastructure

![Alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/dungbv4.jits/Documents/Learning/Udacity/lasttest/nd0067-c4-deployment-process-project-starter/Docs/Architecture%20Diagrams/Architecture_Diagram.drawio.png?version%3D1691292073500)

## AWS
### Configure credentials aws.
- AWS Access key id: `AKIAS5KNYNE3MMBMTV66`.
- AWS Secret access key: `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`.
- Aws region: `us-west-2`.
- Aws region default: `us-eat-1`.

### RDS Using Postgres
The application server using AWS RDS postgress database.

- Endpoint: `postgres2.czfwdxzcq6pt.us-east-1.rds.amazonaws.com`.
- Port: 5432.
- Postgress database: `postgres2`.
- Postgress user: `postgres`.
- Postgress password: `postgres124`.

### Elastic Beanstalk.
The application server is hosted on AWS Elastic Beanstalk. Elastic Beanstalk extracts and executes the application on an endpoint once it has been built, archived, and uploaded to an S3 bucket.
</br>
EB URL: `http://udagram-api-dev.us-west-2.elasticbeanstalk.com/`.

### S3 Bucket.
AWS S3 Bucket accesst and using to depoy the fronend application to S3 bucket. Which is made bucket is publish.
</br>
Bucket URL: `http://udagram-test01.s3-website-us-west-2.amazonaws.com/home`.
