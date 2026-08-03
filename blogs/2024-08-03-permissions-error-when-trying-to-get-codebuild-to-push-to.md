---
title: "Permissions error when trying to get codebuild to push to ECR AWS because it's registering as an unknown user"
url: "https://stackoverflow.com/questions/78828124/permissions-error-when-trying-to-get-codebuild-to-push-to-ecr-aws-because-its-r"
date: "2024-08-03"
author: "Jacob Sanderson"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
As the title suggests, my codebuild is not letting me fulfill my buildscript to push the docker image to ECR. It works perfectly when on my local machine, but not in codebuild. The error message is like so: denied: User: arn:aws:iam::311791021927:user/ServerlessAccount is not authorized to perform: ecr:InitiateLayerUpload on resource: arn:aws:ecr:***:014498627014:repository/squared-www because no resource-based policy allows the ecr:InitiateLayerUpload action The issue is, user 311791021927 doesn't actually exist in my IAM or anywhere, this is my buildspec.yml: version: 0.2 env: secrets-manage
