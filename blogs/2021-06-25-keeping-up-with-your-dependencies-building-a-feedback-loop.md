---
title: "Keeping up with your dependencies: building a feedback loop for shared libraries"
url: "https://aws.amazon.com/blogs/devops/keeping-up-with-your-dependencies-building-a-feedback-loop-for-shared-libraries/"
date: "2021-06-25"
author: "Joerg Woehrle"
feed_url: "https://aws.amazon.com/blogs/devops/tag/aws-codebuild/feed/"
---
In a microservices world, it’s common to share as little as possible between services. This enables teams to work independently of each other, helps to reduce wait times and decreases coupling between services. However, it’s also a common scenario that libraries for cross-cutting-concerns (such as security or logging) are developed one time and offered to other teams for consumption.
