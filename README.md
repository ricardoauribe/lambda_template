# Lambda Template 

AWS lambda template
This example will set connectivity to S3 to retrieve a file from a bucket, process data and then persist data into a Dynamo DB instance

## Pre Requisites

Install Docker Desktop:

- https://www.docker.com/products/docker-desktop

Steps to download and install SAM can be found here:

- https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install-mac.html

## TODO: Create connection to S3 and to DynamoDB



## TODO: Explain Roles for Usage
## TODO: Explain SAM install and usage for tests
## TODO: Create an event.json for sameple usage

To test your local event try:

```
# Invoking function with event file
$ sam local invoke "lambda name" -e event.json
```

## How to contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

The project works under the git flow framework please create your own feature branch and generate a pull request into master to be reviewed.

https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow

Please make sure to update/create tests as appropriate.
