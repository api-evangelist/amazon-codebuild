---
title: "Github Actions pipeline running in AWS Codebuild hangs with waiting for runner"
url: "https://stackoverflow.com/questions/78820008/github-actions-pipeline-running-in-aws-codebuild-hangs-with-waiting-for-runner"
date: "2024-08-01"
author: "Grilla99"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
{% raw %}
I have a reusable workflow that I have created in Github Actions, it uses AWS CodeBuild as a runner i.e. jobs: docker: runs-on: codebuild-XXX-XXX-${{ github.run_id }}-${{ github.run_attempt }} The workflow runs fine on CodeBuild when I invoke it using workflow dispatch, but when I call it from another repository it hangs with waiting for runner... I have tried to add a webhook to the codebuild job for the calling repository, and added a GITHUB_TOKEN to the reusable workflow.
{% endraw %}
