---
title: "\"AWS CodeBuild Error: 'Unable to initialize cache download: no paths specified to be cached' in Buildspec.yml\""
url: "https://stackoverflow.com/questions/79301753/aws-codebuild-error-unable-to-initialize-cache-download-no-paths-specified-t"
date: "2024-12-22"
author: "Hellen"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
I am encountering an issue during the PRE_BUILD phase in AWS CodeBuild. My buildspec script attempts to connect to a MySQL database to verify connectivity, but the connection fails with the following error: [Container] 2024/12/22 20:03:43.966393 Phase complete: PRE_BUILD State: FAILED [Container] 2024/12/22 20:03:43.966407 Phase context status code: COMMAND_EXECUTION_ERROR Message: Error while executing command: if mysql -h "$DB_HOST" -P "$DB_PORT" -u "$DB_USERNAME" -p"$DB_PASSWORD" -e "SHOW DATABASES;"; then What I’ve Tried Verified Environment Variables: The values for $DB_HOST, $DB_PORT, $D
