---
title: "Error reporting failure to CodePipeline: JobNotFoundException: Job with id 'JobId' does not exist"
url: "https://stackoverflow.com/questions/78861974/error-reporting-failure-to-codepipeline-jobnotfoundexception-job-with-id-jobi"
date: "2024-08-12"
author: "Varshini PS"
feed_url: "https://stackoverflow.com/feeds/tag?tagnames=aws-codebuild&sort=newest"
---
screenshot 1 enter image description here I am getting error in codeBuild saying JobId not found. Below is the code i am using `putPipelineFailure(error) { return new Promise((resolve, reject) => { const jobId = process.env.CODEPIPELINE_JOB_ID; if (!jobId) { console.log("CODEPIPELINE_JOB_ID environment variable not set"); return reject(new Error("CODEPIPELINE_JOB_ID environment variable not set")); } console.log('Job ID:', jobId); const params = { jobId: jobId, failureDetails: { message: JSON.stringify(error.message), type: 'JobFailed' } }; codepipeline.putJobFailureResult(params, function(err
