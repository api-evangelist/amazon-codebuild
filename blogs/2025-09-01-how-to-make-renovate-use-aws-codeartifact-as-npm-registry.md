---
title: "How to make Renovate use AWS CodeArtifact as npm registry in AWS CodeBuild?"
url: "https://stackoverflow.com/questions/79752926/how-to-make-renovate-use-aws-codeartifact-as-npm-registry-in-aws-codebuild"
date: "2025-09-01"
author: "user22409631"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am trying to run Renovate inside AWS CodeBuild with AWS CodeCommit (source repo) and AWS CodeArtifact (private npm registry). Here is my buildspec.yml : version: 0.2 env: shell: bash git-credential-helper: yes variables: RENOVATE_PLATFORM: 'codecommit' RENOVATE_REPOSITORIES: '["repoName1", "repoName2"]' RENOVATE_CONFIG: '{"extends":["config:recommended"]}' LOG_LEVEL: 'debug' AWS_REGION: 'us-east-1' phases: build: on-failure: CONTINUE commands: - aws codeartifact login --tool npm --domain my_domain --domain-owner 111122223333 --repository my_repo - npm install -g renovate - renovate And here 
