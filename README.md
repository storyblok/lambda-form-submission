# Serverless Form Submission via AWS Lambda

Simply create a Cloudformation with the cloudformation.yml template of this repository and everything will be setup for you.

<a href="https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=&amp;templateURL=https://s3.amazonaws.com/storyblok/cloudformation.yml" rel="nofollow">
	<img src="https://camo.githubusercontent.com/210bb3bfeebe0dd2b4db57ef83837273e1a51891/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f636c6f7564666f726d6174696f6e2d6578616d706c65732f636c6f7564666f726d6174696f6e2d6c61756e63682d737461636b2e706e67" data-canonical-src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png" style="max-width:100%;">
</a>

Before you beginn deploying this template you need a reCAPTCHA secret from [https://www.google.com/recaptcha/admin#list](https://www.google.com/recaptcha/admin#list) and a Storyblok account from [app.storyblok.com](http://app.storyblok.com)

## What AWS resources does this template use?

* Lambda (API Function)
* API Gateway (HTTP proxy to Lambda)
* S3 (Lambda files)
* SES (For sending email)
* CloudFormation (Infrastructure as Code)
* IAM (AWS permissions & users)