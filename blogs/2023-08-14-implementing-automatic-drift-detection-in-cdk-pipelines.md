---
title: "Implementing automatic drift detection in CDK Pipelines using Amazon EventBridge"
url: "https://aws.amazon.com/blogs/devops/implementing-automatic-drift-detection-in-cdk-pipelines-using-amazon-eventbridge/"
date: "2023-08-14"
author: "DAMODAR SHENVI WAGLE"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codebuild/feed/"
---
The AWS Cloud Development Kit (AWS CDK) is a popular open source toolkit that allows developers to create their cloud infrastructure using high level programming languages. AWS CDK comes bundled with a construct called CDK Pipelines that makes it easy to set up continuous integration, delivery, and deployment with AWS CodePipeline . The CDK Pipelines construct does all the heavy lifting, such as setting up appropriate AWS IAM roles for deployment across regions and accounts, Amazon Simple Storage Service (Amazon S3) buckets to store build artifacts, and an AWS CodeBuild project to build, test, and deploy the app.
