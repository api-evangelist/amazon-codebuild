---
title: "AWS Codebuild: \"No such file or directory\""
url: "https://stackoverflow.com/questions/78902776/aws-codebuild-no-such-file-or-directory"
date: "2024-08-22"
author: "Joe"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I have an AWS Codebuild project that should build my eleventy project. When the project runs npx @11ty/eleventy I can the following error: /codebuild/output/src3281352166/src/node_modules/.bin/eleventy: line 1: ../@11ty/eleventy/cmd.js: No such file or directory This is my buildspec.yml : version: 0.2 phases: build: commands: - npm install - ls node_modules/@11ty/eleventy - npm run build npm run build will just run npx @11ty/eleventy . The ls command is just me trying to debug.
