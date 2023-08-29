# AWS: API, Dynamo and Lambda

# AWS API Gateway Overview

Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests. The Amazon API Gateway is an important part of the Serverless ecosystem because it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.
The API Gateway integrate with other AWS services by:

- AWS Lambda: run Lambda functions to generate HTTP API responses.
- AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
- Amazon Cognito: provide authentication and authorization for your HTTP APIs.

# AWS API Gateway

What are the some benefits of using Amazon API Gateway?
The benefits of using Amazon API Gateway are Efficient API development, API version management, API monetization, API security, API analytics, and API developer portal. The two API types are REST APIs and WebSocket APIs.

# AWS DynamoDB Guide

DynamoDB is NoSQL database offered by Amazon Web Services (AWS). The circumstances I would recommend DynamoDB over MongoDB is when you need a database that can scale automatically and you don't want to manage your own database server.

# AWS DynamoDB

The DynamoDB works by configure key features of your table, such as its primary key, read and write capacity units, and more. After you create your table, you can manage its settings, scale its capacity, and monitor its performance metrics. The from there is goes into an export and import process. The export process is when you export data from a DynamoDB table into an Amazon S3 bucket. The import process is when you import data into a DynamoDB table from an Amazon S3 bucket.

# Dynamoose

Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose.
The key features of Dynamoose are Schema, Type Support, Validation, Querying, Callback & Promise support, and Middleware.

## Reflection

My goals after reading and reviewing the class README are understanding the following:

- Use AWS API Gateway to build a RESTful API
- Use AWS DynamoDB to build a NoSQL database
- Differences between HTTP and REST APIs at AWS
- Use AWS Lambda to trigger functions in your API

### Resources I use

Amazon API Gateway[^1], AWS API Gateway[^2], and AWS DynamoDB [^3]

[^1]: [AWS API](https://www.serverless.com/guides/amazon-api-gateway)
[^2]: [AWS API](https://aws.amazon.com/api-gateway/)
[^3]: [AWS DynamoDB](https://www.dynamodbguide.com/what-is-dynamo-db/)
