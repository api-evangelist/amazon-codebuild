---
title: "Does codebuild make multiple calls to secret manager if secret names are the same?"
url: "https://stackoverflow.com/questions/79755154/does-codebuild-make-multiple-calls-to-secret-manager-if-secret-names-are-the-sam"
date: "2025-09-03"
author: "BryceLarkin"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am storing database credentials in Secret Manager as a stringified JSON. I want CodeBuild to fetch the secret and then set one of the JSON params as an environment variable. If I do this multiple times for the same secret, will it make multiple calls or just one call to Secret Manager?
