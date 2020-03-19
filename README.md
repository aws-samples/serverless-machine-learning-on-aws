## Serverless Machine Learning On AWS

The ```template.json``` file is an AWS CloudFormation template that builds the following serverless components:

* An [AWS CodeBuild](https://aws.amazon.com/codebuild/) project based on the ```buildspec.yaml``` file that creates AWS Lambda Layers that can be included as dependencies for any Lambda function

* A sample [AWS Lambda](https://aws.amazon.com/lambda/) function that performs object detection on image URLs

* A REST API interface using [Amazon API Gateway](https://aws.amazon.com/api-gateway/)

* A serverless front-end using [Amazon S3](https://aws.amazon.com/s3/) and [AWS CloudFront](https://aws.amazon.com/cloudfront/)

In order to complete launch the template you'll need an [AWS Account](https://signin.aws.amazon.com/signin?redirect_uri=https%3A%2F%2Fportal.aws.amazon.com%2Fbilling%2Fsignup%2Fresume&client_id=signup) with access to the services above. There are resources required by this workshop that are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier](https://aws.amazon.com/free/) page for more details.

Region| Launch
------|-----
US East (N. Virginia) | [![Launch Serverless ML in us-east-1](imgs/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=serverless-ml&templateURL=https://aws-ml-blog.s3.amazonaws.com/artifacts/serverless-machine-learning-on-aws/template.json)

## License

This library is licensed under the Apache 2.0 License. 
