# Wild Rydes Site
This repository contains the source code for the Wild Rydes website, a serverless web application that allows users to request rides from unicorns. The website is built using HTML, CSS, JavaScript, and AWS services such as S3, Cognito, API Gateway, Lambda, and DynamoDB.
## Getting Started
To run the website locally, you will need to clone this repository and open the index.html file in your browser. You will also need to configure the AWS credentials and region in the js/config.js file.<br />
To deploy the website to AWS, you will need to use the AWS Amplify Console. You can follow the instructions in this [tutorial](https://github.com/aws-samples/aws-serverless-workshops) to set up a continuous deployment pipeline from your GitHub repository to Amplify.
## Features
The website has the following features:<br />
-User registration and authentication using Amazon Cognito<br />
-User profile management using Amazon DynamoDB<br />
-Ride request and confirmation using AWS Lambda and Amazon API Gateway<br />
-Real-time updates of unicorn location using Amazon Kinesis and Amazon SNS<br />
-Interactive map using Mapbox GL JS<br />

