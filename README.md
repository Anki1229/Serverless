# Serverless
As Kanye West said:

> We're living the future so
> the present is our past.
After that you need to add the plugin to your serverless.yml of you service.

Run the command serverless --help and verify the list of commands contain an encrypt and a decrypt command.

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway
> 

Serverless Credentials Plugin

IMPORTANT NOTE: As pointed out in the AWS documentation for storing sensible information Amazon recommends to use AWS KMS instead of environment variables like this plugin.

serverless npm version license

# Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

# Plugins

Please enter the required plugin name and version in the serverless.yml and plugins.txt .

Quick Start

   1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   2. 
   3.   Install via npm:

npm install -g serverless

    Set-up your Provider Credentials. Watch the video on setting up credentials

    Create a Service:

You can create a new service or install existing services.

# Create a new Serverless Service/Project
serverless create --template aws-nodejs --path my-service
# Change into the newly created directory
cd my-service

    Deploy a Service:

Use this when you have made changes to your Functions, Events or Resources in serverless.yml or you simply want to deploy all changes within your Service at the same time.

serverless deploy -v

    Deploy the Function:

Use this to quickly upload and overwrite your AWS Lambda code on AWS, allowing you to develop faster.

serverless deploy function -f hello

    Invoke the Function on AWS:

Invokes an AWS Lambda Function on AWS and returns logs.

serverless invoke -f hello -l

    Invoke the Function on your machine:

Invokes an AWS Lambda Function on your local machine and returns logs.

serverless invoke local -f hello -l

    Fetch the Function Logs:

Open up a separate tab in your console and stream all logs for a specific Function using this command.

serverless logs -f hello -t

    Remove the Service:

Removes all Functions, Events and Resources from your AWS account.

serverless remove

How to Install a Service:

This is a convenience method to install a pre-made Serverless Service locally by downloading the Github repo and unzipping it. Services are listed below.

serverless install -u https://github.com/your-url-to-the-serverless-service

Check out the Serverless Framework Guide for more information.
Services (V1.0)

The following are services you can instantly install and use by running serverless install --url <service-github-url>

    serverless-examples
    CRUD - CRUD service, Scala Port
    CRUD with FaunaDB - CRUD service using FaunaDB
    CRUD with S3 - CRUD service using S3
    CRUD with Flask and SQLAlchemy - Python CRUD API service with Flask, SQLAlchemy and Swagger
    GraphQL Boilerplate - GraphQL application Boilerplate service
    Authentication - Authentication boilerplate service
    Mailer - Service for sending emails
    Kinesis streams - Service to showcase Kinesis stream support
    DynamoDB streams - Service to showcase DynamoDB stream support
    Landingpage backend - Landingpage backend service to store E-Mail addresses
    Facebook Messenger Chatbot - Chatbot for the Facebook Messenger platform
    Lambda chaining - Service which chains Lambdas through SNS
    Secured API - Service which exposes an API key accessible API
    Authorizer - Service that uses API Gateway custom authorizers
    Thumbnails - Service that takes an image url and returns a 100x100 thumbnail
    Boilerplate - Opinionated boilerplate
    ES6 + Jest - ES6 + Jest Boilerplate
    PHP - Call a PHP function from your lambda
    Ruby - Call a Ruby function from your lambda
    Slack App - Slack App Boilerplate with OAuth and Bot actions
    Swift - Full-featured project template to develop Lambda functions in Swift
    Cloudwatch Alerts on Slack - Get AWS Cloudwatch alerts notifications on Slack

Note: the serverless install command will only work on V1.0 or later.
Features

    Supports Node.js, Python, Java, Go, C#, Ruby, Swift, Kotlin, PHP, Scala, & F#
    Manages the lifecycle of your serverless architecture (build, deploy, update, delete).
    Safely deploy functions, events and their required resources together via provider resource managers (e.g., AWS CloudFormation).
    Functions can be grouped ("serverless services") for easy management of code, resources & processes, across large projects & teams.
    Minimal configuration and scaffolding.
    Built-in support for multiple stages.
    Optimized for CI/CD workflows.
    Loaded with automation, optimization and best practices.
    100% Extensible: Extend or modify the Framework and its operations via Plugins.
    An ecosystem of serverless services and plugins.
    A passionate and welcoming community!

