---
title: "Blue/Green deployments using AWS CDK Pipelines and AWS CodeDeploy"
url: "https://aws.amazon.com/blogs/devops/blue-green-deployments-using-aws-cdk-pipelines-and-aws-codedeploy/"
date: "2023-10-10"
author: "Luiz Decaro"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codebuild/feed/"
---
Customers often ask for help with implementing Blue/Green deployments to Amazon Elastic Container Service (Amazon ECS) using AWS CodeDeploy . Their use cases usually involve cross-Region and cross-account deployment scenarios. These requirements are challenging enough on their own, but in addition to those, there are specific design decisions that need to be considered when using CodeDeploy.
