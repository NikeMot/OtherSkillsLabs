# 06 — AI

## Purpose

This folder contains the cumulative AI Engineering pillar inside the `Mac and AI` track.

The AI section is now a 48-lab cumulative course. Each AI lab builds on previous AI labs so that the work becomes one growing AI/data/operations system rather than disconnected exercises.

Mac is separate. The cumulative-build rule applies only to this AI section.

The labs cover CS foundations, data engineering, R and Python data preparation, statistical learning, ML, LLMs, prompt engineering, retrieval workflows, AI agents, evaluation, observability, local deployment, Azure, AWS, GCP, and small AI-enabled operations applications.

## Cumulative Build Rule

Every AI lab must build on previous AI labs.

Each AI lab must document:

* previous lab dependencies used
* new capability added
* existing files, datasets, scripts, models, APIs, or documentation reused
* integration point with the growing project
* regression check showing previous functionality still works where relevant
* updated architecture, data-flow, or component notes where relevant

The cumulative project can be framed as an `AI Operations and Data Assistant` built with safe fictional or generated data.

## Official Online Documentation Rule

Every AI lab must follow `docs/official-online-documentation-standard.md`.

Books provide depth and structure. Official online documentation keeps commands, APIs, SDKs, cloud services, security settings, pricing, deployment options, and model behaviour current.

Each AI lab must include an `Official online documentation checked` section.

Use official documentation first for Python, R, NumPy, pandas, scikit-learn, PostgreSQL, Docker, FastAPI, GitHub Actions, Streamlit, orchestration tools, OpenAI, Azure, AWS, and Google Cloud.

## Cross-Cutting Requirements

The 48-lab AI course must also include the mandatory cross-cutting requirements in `docs/ai-cross-cutting-requirements.md`.

These requirements do not add more labs. They are embedded inside the existing 48 labs.

Every AI lab should include relevant evidence for:

* software engineering discipline
* MLOps / LLMOps
* AI security
* evaluation-first practice
* workflow orchestration
* data and model governance
* minimal product or interface layer

## Target Job Rule

The junior AI engineer job description shapes every lab.

Every lab must include target job evidence for at least one of:

* Python for AI and ML workflows
* R for data analysis, statistics, visualisation, and statistical learning where useful
* NumPy, Pandas, tidyverse, and data preparation
* data cleaning and feature engineering
* model building and model evaluation
* scikit-learn, TensorFlow, PyTorch, or R statistical learning awareness
* NLP, retrieval, recommendation, or computer-vision awareness where relevant
* deployment and integration into real applications
* Git and modern development practice
* AWS, Azure, and GCP platform awareness
* communication with engineers, data scientists, product teams, and stakeholders
* safe, responsible, and well-evaluated AI behaviour

## Core Curriculum Rule

Related topics should be learned together.

The AI section follows this learning order:

```text
Labs 01-06 -> CS and engineering foundations
Labs 07-18 -> Data engineering and R before AI
Labs 19-28 -> ML and statistical learning
Labs 29-38 -> LLMs, RAG, and agents
Labs 39-46 -> Production AI across local, Azure, AWS, and GCP
Labs 47-48 -> Capstone
```

See `docs/ai-curriculum-standard.md` for the full 48-lab curriculum.

## Source Stack

Primary AI source:

* `AI Engineering`

Supporting sources:

* `Hands-On Large Language Models`
* `Prompt Engineering for LLMs`
* `An Introduction to Statistical Learning with Python`
* `An Introduction to Statistical Learning with R`
* `R for Data Science`
* `Practical Statistics for Data Scientists`
* `Fundamentals of Data Engineering`
* `Designing Data-Intensive Applications`
* `Database Internals`
* `Data Engineering Design Patterns`
* `AI Systems Performance Engineering`
* `Observability Engineering`
* `Redefining Data Engineering with AI`
* `AI Agents: The Definitive Guide`

## Official Documentation Stack

Use the online documentation standard for the full source list.

Common official online sources include:

* Python, R, NumPy, pandas, scikit-learn, PostgreSQL, Docker, FastAPI, GitHub Actions, Streamlit, Prefect, and Dagster
* OpenAI API, prompting, evals, agents, and safety documentation where OpenAI tooling is used
* Microsoft Learn for Azure Foundry, Azure Machine Learning, Azure Monitor, Key Vault, App Service, Functions, Container Apps, Blob Storage, Azure SQL, and Entra ID
* AWS documentation for Bedrock, SageMaker AI, CloudWatch, Secrets Manager, IAM, S3, Lambda, ECS, EC2, RDS, Athena, and Redshift
* Google Cloud documentation for Gemini Enterprise Agent Platform / Vertex AI evolution, Cloud Run, Cloud Monitoring, Secret Manager, IAM, Cloud Storage, Cloud Functions, Compute Engine, Cloud SQL, and BigQuery

## Coverage Rule

The aim is to cover all relevant content from the chosen books across the full track while keeping implementation details current with official documentation.

Each lab must update a coverage ledger showing which chapter or major section was used, which lab covered it, and whether it is planned, completed, or needs review.

## Embedded Learning Layers

AI labs should preserve the wider learning outcomes from the original track.

Where relevant, each AI lab should include:

* CS foundation note
* data engineering note
* R note
* local implementation evidence
* Azure mapping or implementation option
* AWS mapping or implementation option
* GCP mapping or implementation option
* SRE or operations evidence

## Local and Multi-Cloud Rule

Every major concept should be learned locally first.

Cloud-relevant concepts must then be mapped across Azure, AWS, and GCP.

The expected pattern is:

```text
1. local implementation
2. Azure mapping or implementation
3. AWS mapping or implementation
4. GCP mapping or implementation
```

Not every lab needs a full deployment to all three clouds. However, every cloud-relevant lab must include a short Azure / AWS / GCP comparison. Dedicated cloud labs must include stronger implementation evidence.

## Manual-First Rule

Where a lab involves data preparation, model building, evaluation, retrieval, or operations workflow design, complete the manual baseline first.

AI tools may be used afterwards for review, documentation, test case generation, comparison, evaluation checklist creation, explanation, and improvement ideas.

AI assistance must not replace understanding, verification, or manual reasoning.

## Topic Focus

Labs in this folder may cover:

* local development environment
* Python, NumPy, Pandas, R, and tidyverse for AI data preparation
* CS foundations for AI systems
* SQL, PostgreSQL, and data modelling
* data ingestion, transformation, quality, metadata, and lineage
* R visualisation, statistics, and reporting
* supervised ML models
* model evaluation and error analysis
* R and Python model comparison
* LLM foundations
* prompt engineering and structured outputs
* retrieval-augmented generation
* embeddings and semantic search
* AI agents and tool-use boundaries
* evaluation datasets
* hallucination checks
* AI observability and monitoring
* AI systems performance and cost thinking
* local, Azure, AWS, and GCP implementation patterns
* safe deployment thinking
* small AI-enabled backend or SRE helper applications

## Planned Lab Sequence

```text
01 local development environment
02 CS introduction for AI
03 algorithms for data and AI
04 HTTP, REST, and FastAPI basics
05 SQL and PostgreSQL foundations
06 cloud foundations across Azure, AWS, and GCP
07 data engineering lifecycle and source systems
08 local data ingestion from CSV, JSON, or API
09 storage design: files, tables, object storage
10 SQL transformation and modelling
11 R data wrangling and visualisation
12 Python and R dataset comparison
13 data quality checks and validation
14 pipeline testing and repeatable execution
15 metadata, lineage, and documentation
16 monitoring and incident handling for pipelines
17 data product and serving layer design
18 data engineering review across local, Azure, AWS, and GCP
19 EDA in Python and R
20 practical statistics for AI datasets
21 first supervised ML model
22 feature engineering
23 train/test validation and metrics
24 classification and regression comparison
25 error analysis and model limitations
26 model evaluation report in Python and R
27 local model serving with FastAPI
28 ML workflow mapping across Azure ML, SageMaker, and Vertex AI
29 LLM foundations and safe usage
30 prompt engineering and structured outputs
31 prompt evaluation and failure cases
32 embeddings and semantic search
33 retrieval index design
34 RAG over runbooks, tickets, or lab notes
35 RAG evaluation, citations, and hallucination checks
36 AI agents: planning, tools, memory, and state
37 agent workflow simulation with human approval
38 agent safety, failure modes, and escalation
39 local AI application end to end
40 deploy AI app on Azure
41 deploy AI app on AWS
42 deploy AI app on GCP
43 secrets, identity, and access control cross-cloud
44 monitoring and observability cross-cloud
45 performance, latency, throughput, and cost cross-cloud
46 AI governance, data handling, and incident response
47 capstone design: architecture, data, cloud, risk, evaluation
48 capstone build: demo, monitoring, and interview story
```

## Mandatory Career Layers

Every AI lab must also include:

* target job evidence
* failure-mode thinking
* clear explanation of AI limitations
* safe communication to managers or peers
* recruiter-facing summary
* interview explanation
* personal reflection on responsible use

## Evidence Standard

AI evidence should include safe test inputs, expected outputs, actual outputs, pass/fail criteria, evaluation results, failure cases, official online documentation checked, and limitations.

Use fictional, generated, personal, or safely sanitised data only.
