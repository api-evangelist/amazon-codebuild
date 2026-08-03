---
title: ".NET / dotnet script (CSX) execution in AWS CodeBuild not resolving IAM Role"
url: "https://stackoverflow.com/questions/79527601/net-dotnet-script-csx-execution-in-aws-codebuild-not-resolving-iam-role"
date: "2025-03-22"
author: "smk081"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
We have a AWS CodeBuild Project configured with an IAM Role with the required permissions to interact with some AWS services, in this case a DynamoDB table. We are executing a dotnet-script (CSX) file which utilizes the AWS SDKs including the DynamoDB SDK to perform a PutObject operation against a DynamoDB Table. Typically for apps and services deployed to other AWS compute services like AWS ECS/Fargate or AWS Lambda, our applications are able to just simply instantiate the SDK client(s) for the service(s) and it would follow the standard AWS credential resolution chain and we do not need to p
