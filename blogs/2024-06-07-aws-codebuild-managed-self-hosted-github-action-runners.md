---
title: "AWS CodeBuild Managed Self-Hosted GitHub Action Runners"
url: "https://aws.amazon.com/blogs/devops/aws-codebuild-managed-self-hosted-github-action-runners/"
date: "2024-06-07"
author: "Matt Laver"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codebuild/feed/"
---
AWS CodeBuild now supports managed self-hosted GitHub Action runners, allowing you to build powerful CI/CD capabilities right beside your code and quickly implement a build, test and deploy pipeline. Last year AWS announced that customers can define their GitHub Actions steps within any phase of a CodeBuild buildspec file but with a self-hosted runner , jobs execute from GitHub Actions on GitHub.com to a system you deploy and manage. With the recent announcement that AWS CodeBuild now supports managed GitHub Action runners , AWS can take care of managing the hosting of GitHub Action self-hosted runners within CodeBuild allowing teams to run their GitHub Actions workflow jobs natively within AWS.
