# Amazon CodeBuild

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AWS CodeBuild is a fully managed continuous integration service that compiles source code, runs tests, and produces ready-to-deploy software packages. CodeBuild scales continuously and processes multiple builds concurrently so your builds are not left waiting in a queue. It supports popular build environments for Java, Python, Node.js, Ruby, Go, Android, .NET Core, Docker, and more. CodeBuild integrates with AWS CodePipeline, GitHub, Bitbucket, and other source providers for end-to-end CI/CD workflows.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codebuild/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, CI/CD, Build, Continuous Integration, DevOps, Testing

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon CodeBuild API

The Amazon CodeBuild REST API enables programmatic management of build projects, builds, report groups, and source credentials. Create and configure build projects with custom environments, start and stop builds, retrieve build logs and artifacts, manage build batches, and configure webhooks for source providers.

**Human URL:** [https://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html)

#### Tags:

 - Amazon, AWS, CI/CD, Build, Continuous Integration

#### Properties

- [Documentation](https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html)
- [APIReference](https://docs.aws.amazon.com/codebuild/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-codebuild-openapi-original.yaml)

## Common Properties

- [GettingStarted](https://aws.amazon.com/codebuild/getting-started/)
- [Authentication](https://docs.aws.amazon.com/codebuild/latest/userguide/auth-and-access-control.html)
- [Pricing](https://aws.amazon.com/codebuild/pricing/)
- [Console](https://console.aws.amazon.com/codebuild/)
- [Portal](https://aws.amazon.com/codebuild/)
- [Documentation](https://docs.aws.amazon.com/codebuild/latest/userguide/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/)
- [FAQ](https://aws.amazon.com/codebuild/faqs/)
- [SignUp](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- [GitHubOrganization](https://github.com/aws)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-codebuild)

## Features

| Name | Description |
|------|-------------|
| Fully Managed Build Service | No need to provision, manage, or scale build servers. AWS handles all infrastructure management so you can focus on writ |
| Continuous Scaling | Automatically scales to meet peak build demand. Processes multiple builds concurrently so builds are never left waiting  |
| Pre-configured Build Environments | Out-of-the-box build environments for Java, Python, Node.js, Ruby, Go, Android, .NET Core, Docker, and more. Customize w |
| Build Batches | Run multiple related builds in parallel as a batch sharing the same source configuration and retrieve combined results f |
| Test Reports | Collect and analyze test results from unit tests, integration tests, and code coverage reports. Track test trends and id |
| Source Integration | Integrate with CodeCommit, GitHub, GitHub Enterprise, GitLab, Bitbucket, and Amazon S3 as source providers with webhook  |
| VPC Support | Run builds inside a VPC for access to private resources, configuring VPC settings including subnets and security groups  |
| Build Caching | Cache build dependencies in Amazon S3 or locally within the build environment to speed up subsequent builds and reduce b |
| Custom Build Environments | Use your own Docker images as build environments, pulling from Amazon ECR or Docker Hub for fully customized build confi |
| Pay-Per-Build Pricing | Pay only for the build minutes you consume with no upfront costs or long-term commitments for on-demand build capacity. |

## Use Cases

| Name | Description |
|------|-------------|
| Continuous Integration Pipelines | Automatically compile, test, and validate code changes on every commit to catch issues early and maintain code quality a |
| Automated Testing | Run unit tests, integration tests, and end-to-end tests as part of every build to ensure code correctness and prevent re |
| Docker Image Building | Build and push Docker container images to Amazon ECR as part of a containerized application deployment workflow. |
| Multi-Environment Build Matrix | Use build batches to test across multiple runtime versions or configurations in parallel, identifying compatibility issu |
| AWS CodePipeline Integration | Use CodeBuild as the build and test stage in an AWS CodePipeline CD pipeline for fully automated code delivery from comm |

## Integrations

| Name | Description |
|------|-------------|
| AWS CodePipeline | Add CodeBuild as build or test actions in CodePipeline deployment stages. |
| AWS CodeCommit | Use CodeCommit repositories as source for CodeBuild projects with webhook triggers. |
| GitHub | Integrate with GitHub repositories and pull request builds using webhooks. |
| GitLab | Use GitLab repositories as source for CodeBuild projects. |
| Bitbucket | Integrate with Bitbucket repositories for cloud-based CI. |
| Amazon ECR | Pull custom build environment images from ECR and push built container images. |
| Amazon S3 | Store build artifacts and cache build dependencies in S3 buckets. |
| AWS IAM | Control access to build projects and builds with fine-grained IAM permissions. |
| Amazon CloudWatch | Monitor build metrics and set alarms on build duration, failure rates, and queued builds. |
| AWS Secrets Manager | Securely inject secrets and environment variables into build environments. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codebuild-openapi-original](openapi/amazon-codebuild-openapi-original.yaml)
- [amazon-codebuild-openapi](openapi/amazon-codebuild-openapi.yml)

### JSON Schema

249 JSON Schema files generated from the OpenAPI specification.

- [amazon-codebuild-artifact-namespace-schema](json-schema/amazon-codebuild-artifact-namespace-schema.json)
- [amazon-codebuild-artifact-packaging-schema](json-schema/amazon-codebuild-artifact-packaging-schema.json)
- [amazon-codebuild-artifacts-type-schema](json-schema/amazon-codebuild-artifacts-type-schema.json)
- [amazon-codebuild-auth-type-schema](json-schema/amazon-codebuild-auth-type-schema.json)
- [amazon-codebuild-batch-delete-builds-input-schema](json-schema/amazon-codebuild-batch-delete-builds-input-schema.json)
- ...and 244 more in [json-schema/](json-schema/)

### JSON Structure

249 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codebuild-context](json-ld/amazon-codebuild-context.jsonld)

### Examples

249 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codebuild](capabilities/shared/codebuild.yaml) — 45 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeBuild CI/CD](capabilities/amazon-codebuild-cicd.yaml) | codebuild | 12 | DevOps Engineer |

## Vocabulary

- [amazon-codebuild-vocabulary](vocabulary/amazon-codebuild-vocabulary.yaml) — Unified taxonomy mapping 1 resources, 6 actions, 1 workflows, and 2 personas

## Rules

- [amazon-codebuild-spectral-rules](rules/amazon-codebuild-spectral-rules.yml) — 18 rules enforcing Amazon CodeBuild API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
