# Notes Application AWS

A simple note taking app called Scratch. It is a single page application powered by a serverless API written completely in JavaScript. This is the complete source for the backend. The frontend code is located at [here](https://github.com/mcast045/serverless-stack-client).
## REQUIREMENTS
* Should allow users to signup and login to their accounts
* Users should be able to create notes with some content
* Each note can also have an uploaded file as an attachment
* Allow users to modify their note and the attachment
* Users can also delete their notes
* The app needs to be responsive
The app is deployed on the AWS Platform at [here](d3qnndceml20si.cloudfront.net)
## SUMMARY
* Configure your AWS account
* Create database using DynamoDB
* Set up S3 for file uploads
* Set up Cognito User Pools to manage user accounts
* Set up Cognito Identity Pool to secure our file uploads
* Set up the Serverless Framework to work with Lambda & API Gateway
* Write the various backend APIs
* Deploy app through the command line
