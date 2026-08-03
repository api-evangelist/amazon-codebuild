---
title: "AWS CodeBuild Fails with YAML_FILE_ERROR When Running Python Script in buildspec.yml"
url: "https://stackoverflow.com/questions/78757198/aws-codebuild-fails-with-yaml-file-error-when-running-python-script-in-buildspec"
date: "2024-07-17"
author: "Yiffany"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I’m trying to run a Python script in AWS CodeBuild using a buildspec.yml file. The Python script is supposed to send an email using AWS SES. Here’s the relevant part of my buildspec.yml : version: 0.2 phases: install: runtime-versions: python: 3.8 commands: - pip install boto3 build: commands: - | echo "import os import boto3 from botocore.exceptions import ClientError from email.mime.multipart import MIMEMultipart from email.mime.text import MIMEText from email.mime.application import MIMEApplication SUBJECT='There are high or medium alerts..' SENDER='xxx' RECIPIENT='xxx' ATTACHMENT='$CODEBUI
