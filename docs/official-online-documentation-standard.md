# Official Online Documentation Standard

## Purpose

This document defines how official online documentation should be used across the `Mac and AI` track.

Books provide depth and structure. Official online documentation keeps labs current.

Every lab should use the most relevant official documentation available at the time the lab is completed.

## Rule

Each lab must include an `Official online documentation checked` section.

That section should record:

| Field | What to record |
| --- | --- |
| Source | Official documentation source name |
| URL | Documentation page used |
| Version or date checked | Version number, release date, page date, or date accessed |
| Lab decision affected | What the documentation changed, confirmed, or clarified |
| Notes | Any caveats, deprecated guidance, preview features, or version differences |

Use official vendor or project documentation first. Use blogs, tutorials, YouTube, or third-party articles only as secondary support.

## When to Check Online Documentation

Check official online documentation when a lab involves:

* installation
* commands or CLI usage
* SDK usage
* API usage
* cloud services
* pricing or quotas
* deployment
* security settings
* identity and access control
* monitoring or observability
* model, prompt, or agent APIs
* orchestration tools
* package versions
* deprecated or renamed features

## Mac / Apple Official Documentation

Use these sources for Mac labs:

| Area | Official documentation |
| --- | --- |
| Apple deployment and MDM | https://support.apple.com/guide/deployment/welcome/web |
| Apple Business Manager | https://support.apple.com/guide/apple-business-manager/welcome/web |
| Mac user and support workflows | https://support.apple.com/guide/mac-help/welcome/mac |
| Apple device management API and payloads | https://developer.apple.com/documentation/devicemanagement |

## Python, R, Data, and ML Documentation

Use these sources for AI, data, R, and ML labs:

| Area | Official documentation |
| --- | --- |
| Python | https://docs.python.org/3/ |
| R manuals | https://cran.r-project.org/manuals.html |
| NumPy | https://numpy.org/doc/stable/ |
| pandas | https://pandas.pydata.org/docs/ |
| scikit-learn | https://scikit-learn.org/stable/user_guide.html |
| PostgreSQL | https://www.postgresql.org/docs/current/ |
| Docker | https://docs.docker.com/ |
| FastAPI | https://fastapi.tiangolo.com/ |
| GitHub Actions | https://docs.github.com/en/actions |
| Streamlit | https://docs.streamlit.io/ |
| Prefect | https://docs.prefect.io/ |
| Dagster | https://docs.dagster.io/ |

## OpenAI and LLM Documentation

Use official OpenAI documentation when a lab uses OpenAI models, tools, evals, prompting, safety, or agents.

| Area | Official documentation |
| --- | --- |
| OpenAI API docs | https://developers.openai.com/api/docs |
| OpenAI prompting | https://developers.openai.com/api/docs/guides/prompt-engineering |
| OpenAI evals | https://developers.openai.com/api/docs/guides/evals |
| OpenAI safety best practices | https://developers.openai.com/api/docs/guides/safety-best-practices |

If a lab uses a different model provider or local model runtime, add the official documentation for that provider or project at lab time.

## Azure Documentation

Use Microsoft Learn for Azure labs and Azure mappings.

| Area | Official documentation |
| --- | --- |
| Microsoft Foundry / Azure AI | https://learn.microsoft.com/en-us/azure/foundry/ |
| Azure Machine Learning | https://learn.microsoft.com/en-us/azure/machine-learning/ |
| Azure Monitor | https://learn.microsoft.com/en-us/azure/azure-monitor/ |
| Azure Key Vault | https://learn.microsoft.com/en-us/azure/key-vault/ |
| Azure App Service | https://learn.microsoft.com/en-us/azure/app-service/ |
| Azure Functions | https://learn.microsoft.com/en-us/azure/azure-functions/ |
| Azure Container Apps | https://learn.microsoft.com/en-us/azure/container-apps/ |
| Azure Blob Storage | https://learn.microsoft.com/en-us/azure/storage/blobs/ |
| Azure SQL Database | https://learn.microsoft.com/en-us/azure/azure-sql/database/ |
| Microsoft Entra ID | https://learn.microsoft.com/en-us/entra/identity/ |

## AWS Documentation

Use AWS documentation for AWS labs and AWS mappings.

| Area | Official documentation |
| --- | --- |
| Amazon Bedrock | https://docs.aws.amazon.com/bedrock/ |
| Amazon SageMaker AI | https://docs.aws.amazon.com/sagemaker/ |
| Amazon CloudWatch | https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/ |
| AWS Secrets Manager | https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html |
| AWS IAM | https://docs.aws.amazon.com/iam/ |
| Amazon S3 | https://docs.aws.amazon.com/s3/ |
| AWS Lambda | https://docs.aws.amazon.com/lambda/ |
| Amazon ECS | https://docs.aws.amazon.com/ecs/ |
| Amazon EC2 | https://docs.aws.amazon.com/ec2/ |
| Amazon RDS | https://docs.aws.amazon.com/rds/ |
| Amazon Athena | https://docs.aws.amazon.com/athena/ |
| Amazon Redshift | https://docs.aws.amazon.com/redshift/ |

## Google Cloud Documentation

Use Google Cloud documentation for GCP labs and GCP mappings.

| Area | Official documentation |
| --- | --- |
| Gemini Enterprise Agent Platform / Vertex AI evolution | https://docs.cloud.google.com/gemini-enterprise-agent-platform |
| Cloud Run | https://docs.cloud.google.com/run/docs |
| Cloud Monitoring | https://docs.cloud.google.com/monitoring/docs |
| Secret Manager | https://docs.cloud.google.com/secret-manager/docs |
| IAM | https://docs.cloud.google.com/iam/docs |
| Cloud Storage | https://docs.cloud.google.com/storage/docs |
| Cloud Functions | https://docs.cloud.google.com/functions/docs |
| Compute Engine | https://docs.cloud.google.com/compute/docs |
| Cloud SQL | https://docs.cloud.google.com/sql/docs |
| BigQuery | https://docs.cloud.google.com/bigquery/docs |

## Lab Documentation Requirement

Every lab write-up should include this section:

```markdown
## Official online documentation checked

| Source | URL | Version or date checked | Lab decision affected | Notes |
| --- | --- | --- | --- | --- |
| Example official doc | https://example.com/docs | Checked YYYY-MM-DD | Confirmed command/API/service behaviour | Note version, preview status, or deprecation if relevant |
```

## Version Drift Rule

If official documentation changes after a lab is completed, do not silently rewrite the lab.

Instead:

1. Add an `Update note` to the lab.
2. Record what changed.
3. Record whether the lab still works.
4. Update commands or screenshots only when necessary.
5. Keep the old evidence if it is useful historical proof.

## Priority Order

When sources disagree, follow this order:

1. Official vendor/project documentation
2. Official API or SDK reference
3. Official release notes or changelog
4. Official GitHub repository documentation
5. Book or course material
6. Third-party tutorial or blog

## Evidence Rule

Do not copy large sections of online documentation into the repository.

Summarise the specific command, service behaviour, API behaviour, or design decision that affected the lab. Link to the official documentation and record the date checked.
