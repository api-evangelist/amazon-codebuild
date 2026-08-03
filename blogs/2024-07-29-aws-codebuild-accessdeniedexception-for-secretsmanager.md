---
title: "AWS CodeBuild AccessDeniedException for secretsmanager despite correct IAM policies"
url: "https://stackoverflow.com/questions/78809239/aws-codebuild-accessdeniedexception-for-secretsmanager-despite-correct-iam-polic"
date: "2024-07-29"
author: "GalB"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I'm setting up a CI/CD pipeline using AWS CodePipeline and AWS CodeBuild to deploy a Docker application running on an Elastic Beanstalk instance. The Docker credentials are stored in AWS Secrets Manager, and are initialized as environment variables within the AWS CodeBuild Resource. Despite having the necessary IAM policies in place, I'm encountering an AccessDeniedException when CodeBuild tries to access the secrets.
