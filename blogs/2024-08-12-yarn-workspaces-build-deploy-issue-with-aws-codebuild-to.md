---
title: "Yarn workspaces build\\deploy issue with AWS CodeBuild to ElasticBeanstalk"
url: "https://stackoverflow.com/questions/78863117/yarn-workspaces-build-deploy-issue-with-aws-codebuild-to-elasticbeanstalk"
date: "2024-08-12"
author: "Eugene Tusmenko"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I have a monorepo with frontend , backend and my-common yarn workspaces. +-- node_modules +-- package.json +-- tsconfig.json +-- buildspec.yml +-- my-common | +-- package.json | +-- tsconfig.json | +-- src | +-- index.ts +-- backend | +-- package.json | +-- tsconfig.json | +-- src | ... +-- frontend | +-- package.json | +-- tsconfig.json | +-- src | ...
