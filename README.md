# Amazon CodeBuild

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
