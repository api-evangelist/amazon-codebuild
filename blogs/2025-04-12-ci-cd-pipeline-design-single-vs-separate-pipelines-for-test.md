---
title: "CI/CD pipeline design: Single vs. Separate pipelines for test/prod environments"
url: "https://stackoverflow.com/questions/79570523/ci-cd-pipeline-design-single-vs-separate-pipelines-for-test-prod-environments"
date: "2025-04-12"
author: "7ch"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I'm seeking wisdom on CI/CD pipeline design. I primarily work in infrastructure and am currently tasked with designing and building a CI/CD pipeline for the first time. While I've used Git personally, I have limited professional experience with it.(T_T) I'm building the pipeline on AWS using CodePipeline with the following basic structure: GitLab Private (branch merge) → CodeBuild → Approval → CodeDeploy My specific question: Should I create separate pipelines for test and production environments, or is a single pipeline more appropriate?
