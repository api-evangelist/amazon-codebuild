---
title: "Why does my AWS CodeBuild project fail to create a CloudFormation stack with the error \"Template file not found\"?"
url: "https://stackoverflow.com/questions/79326492/why-does-my-aws-codebuild-project-fail-to-create-a-cloudformation-stack-with-the"
date: "2025-01-03"
author: "Lala"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am working on automating the deployment of a static website using AWS CodePipeline and CodeBuild, along with CloudFormation. However, I am encountering some issues in my buildspec.yml configuration. Failed phase message: Error while executing command: aws cloudformation validate-template --template-body s3_static_web.yml.
