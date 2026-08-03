---
title: "How to prevent AWS CodePipeline from Deploying Service in ECS When Image Hasn't Changed?"
url: "https://stackoverflow.com/questions/78819428/how-to-prevent-aws-codepipeline-from-deploying-service-in-ecs-when-image-hasnt"
date: "2024-08-01"
author: "Ziaf Nadeem"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
AWS CodePipeline Deploys Unchanged Images in ECS I am deploying multiple services using AWS CodePipeline and CodeBuild. The pipeline has been set up using AWS Copilot with the following commands: copilot init pipeline copilot pipeline deploy Below is a snippet of my pipeline manifest file: name: ****** version: 1 source: provider: GitHub properties: branch: ******* repository: *********** connection_name: ******** stages: - name: *********** deployments: - service1 - service2 - service3: depends_on: [service1, service2] Buildspec.yaml # Buildspec runs in the build stage of your pipeline. versi
