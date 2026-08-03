---
title: "AWS CodeBuild + CodePipeline: \"CLIENT_ERROR Message: no matching base directory path found for dist\""
url: "https://stackoverflow.com/questions/79274775/aws-codebuild-codepipeline-client-error-message-no-matching-base-directory"
date: "2024-12-12"
author: "Desh Deepak Dhobi"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am trying to build the node app through the AWS CodeBuild service and every time its failing with the same error " CLIENT_ERROR Message: no matching base directory path found for dist " Here is the full detail of the AWS CodeBuild error message: FATAL ERROR: Ineffective mark-compacts near heap limit Allocation failed - JavaScript heap out of memory ----- Native stack trace ----- 1: 0xb84bd6 node::OOMErrorHandler(char const*, v8::OOMDetails const&) [node] 2: 0xefec30 v8::Utils::ReportOOMFailure(v8::internal::Isolate*, char const*, v8::OOMDetails const&) [node] 3: 0xefef17 v8::internal::V8::Fa
