---
title: "Predefined CloudFormation stack running as root causes \"CodeBuild is not authorized to perform: sts:AssumeRole on service role\""
url: "https://stackoverflow.com/questions/79238541/predefined-cloudformation-stack-running-as-root-causes-codebuild-is-not-authori"
date: "2024-11-29"
author: "Hem"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I'm working on deploying an AWS Telco Network and have followed the documentation in doing so along with their sample code, however on the final instantiation step I keep getting an sts:AssumeRole not authorized error. I tracked down the CloudTrail event and here's what it looks like. Any idea to go about resolving this?
