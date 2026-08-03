---
title: "Source Maps Not Correctly Mapping Stack Trace in Sentry for Node js"
url: "https://stackoverflow.com/questions/78905458/source-maps-not-correctly-mapping-stack-trace-in-sentry-for-node-js"
date: "2024-08-23"
author: "Haseeb Mirza"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I'm trying to trace where errors occur in my code using Sentry. To achieve this, I'm uploading source maps to Sentry during the build stage in CodeBuild. In the post_build phase, I use these commands: sentry-cli sourcemaps inject --org numu-04 --project numu-node-api ./dist sentry-cli sourcemaps upload --org numu-04 --project numu-node-api ./dist --url-prefix '~/var/app/current/src' Build artifacts are uploaded to Sentry after the build, and the same code is uploaded to Beanstalk.
