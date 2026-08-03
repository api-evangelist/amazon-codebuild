---
title: "How can I fetch a commit message in AWS CodePipeline/CodeBuild to implement a `[skip ci]` command?"
url: "https://stackoverflow.com/questions/79581244/how-can-i-fetch-a-commit-message-in-aws-codepipeline-codebuild-to-implement-a"
date: "2025-04-18"
author: "Gabriel Tkacz"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I'm using an AWS CodePipeline with GitHub Connections as the source action to deploy a Python app to an AWS Elastic BeanStalk. I’d like to emulate GitHub Actions' [skip ci] feature by detecting a commit message prefix and exiting early if present, canceling the build stage. I found this post, but the commented solution doesn't work with GitHub connections as the source of the action.
