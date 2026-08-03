---
title: "Java/gradle project that builds locally doesn't build in AWS/CodeBuild/Docker"
url: "https://stackoverflow.com/questions/79594513/java-gradle-project-that-builds-locally-doesnt-build-in-aws-codebuild-docker"
date: "2025-04-26"
author: "SRJ"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
Sorry I can't post everything, there is a lot of code - hopefully this is ok System: Oracle Linux 9 Java Corretto 17 Gradle 7.6 The layout of my project is main subproject_1 subproject_2 subproject_3 subproject_4 subproject_2 depends on subproject_1 In the build.grade in project_2 I have the following dependencies { implementation project(':subproject_1') } This works fine on my dev box where I have Oracle Linux 9 running in VirtualBox. I am trying to build using AWS CodeBuild. I created a docker file which is set up just like my local box, same versions, same tools, pulls source from same rep
