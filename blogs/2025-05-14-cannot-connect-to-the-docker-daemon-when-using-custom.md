---
title: "Cannot connect to the Docker daemon when using custom Docker image in managed AWS CodeBuild environment"
url: "https://stackoverflow.com/questions/79621282/cannot-connect-to-the-docker-daemon-when-using-custom-docker-image-in-managed-aw"
date: "2025-05-14"
author: "Mambo"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I want to use a custom Docker image in a managed AWS CodeBuild environment. Previously, I had successfully used the provided image Amazon Linux 2023 x86_64 standard:5.0, which comes with pre-installed Docker. However, using this or any other image as the base image seems like only a workaround and would either unnecessarily bloat my image or come with its own limitations.
