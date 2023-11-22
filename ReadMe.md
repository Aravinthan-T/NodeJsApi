# Node.js API on AWS Lambda

## Overview

This repository contains the source code and deployment instructions for a Node.js-based API deployed on AWS Lambda. The API is built using [Express.js](https://expressjs.com/) and is designed to run serverless in the AWS environment.

## Prerequisites

Before deploying the API, ensure you have the following:

- [Node.js](https://nodejs.org/) installed on your local machine.
- [AWS CLI](https://aws.amazon.com/cli/) configured with necessary credentials.
- [AWS SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) for local testing (optional).

## Project Structure

- **index.js:** Main file containing the Node.js application code.
- **node_modules/:** Node.js dependencies folder.
- **deployment-package.zip:** Packaged deployment file for AWS Lambda.

Set Up AWS API Gateway:
In the AWS Lambda console, go to the "Add triggers" section and choose "API Gateway."
Configure the API Gateway settings and deploy the API.

Test Locally (Optional):
Use the AWS SAM CLI or other local testing tools to test the Lambda function locally before deploying.

Configure API Gateway (Optional):
If needed, set up AWS API Gateway to expose your Lambda function as an API.
