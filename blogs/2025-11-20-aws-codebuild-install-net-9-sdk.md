---
title: "AWS Codebuild - Install .NET 9 SDK"
url: "https://stackoverflow.com/questions/79825039/aws-codebuild-install-net-9-sdk"
date: "2025-11-20"
author: "Felipe Esteves"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
.NET 9 runtime isn't available (yet) for AWS Codebuild. Even after installing the SDK using the following commands, my build would still get .NET 6 instead: version: 0.2 env: shell: bash phases: install: commands: - curl -L https://dot.net/v1/dotnet-install.sh -o dotnet-install.sh - chmod +x ./dotnet-install.sh - ./dotnet-install.sh --channel 9.0 --install-dir /root/.dotnet/ - dotnet --version - dotnet --info
