---
title: "Nuget enforce HTTPS only traffic from AWS CodeBuild"
url: "https://stackoverflow.com/questions/78755772/nuget-enforce-https-only-traffic-from-aws-codebuild"
date: "2024-07-16"
author: "smk081"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am running an AWS CodeBuild project to build, test and publish a .NET 8 application locally (within CodeBuild) and then running it as part of an integration test. The CodeBuild project is running/deployed in my account's VPC which, includes a NAT Gateway for outbound internet traffic, because it also requires access to some private VPC resources. The Security Group on my CodeBuild project ONLY allows outbound HTTPS/ 443 to the public internet (0.0.0.0/0 ) and the build process is currently taking an extremely long time, ~ 22 minutes , on the dotnet restore --verbosity detailed step.
