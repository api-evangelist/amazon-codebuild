---
title: "AWS CodeBuild as Github actions runner – change folder"
url: "https://stackoverflow.com/questions/78775576/aws-codebuild-as-github-actions-runner-change-folder"
date: "2024-07-21"
author: "florian norbert bepunkt"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I have a Github actions workflow that consists of two dependent jobs: Job A does change detection: Which modules in my monorepo changed. Job B is a matrix job, iterating of all changed modules (the working directories are the result of job a) and doing some CI stuff. Now I want to use AWS CodeBuild to run as a self hosted runner for GitHub actions (so I can run everything in my VPC).
