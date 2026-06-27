# AI Curriculum Standard

## Purpose

This document defines how the AI labs should be designed and documented inside the `Mac and AI` track.

The AI section is a cumulative 48-lab course. It combines computer science foundations, data engineering, R, AI engineering, LLM systems, agents, observability, and cross-cloud implementation.

Mac is separate. The cumulative-build rule in this document applies only to the AI section.

## Cumulative AI Build Rule

Every AI lab must build on previous AI labs.

The AI section should not be a set of disconnected exercises. It should become one growing system that starts locally and gradually becomes a more complete AI/data/operations platform.

Each AI lab must include:

* previous lab dependencies used
* new capability added
* existing files, datasets, scripts, models, APIs, or documentation reused
* integration point with the growing project
* regression check showing previous functionality still works where relevant
* updated architecture, data-flow, or component notes where relevant

The running cumulative project can be framed as an `AI Operations and Data Assistant` built with safe fictional or generated data.

Across the 48 labs, this project should gradually gain:

* local development environment
* Python and R data analysis workflow
* SQL database
* data ingestion pipeline
* data transformation and quality checks
* dataset documentation and lineage
* ML baseline models
* model evaluation reports
* LLM prompt workflows
* embeddings and semantic search
* RAG over lab notes, tickets, or runbooks
* agent workflow simulation
* API or small application interface
* observability and evaluation logs
* local deployment
* Azure deployment or mapping
* AWS deployment or mapping
* GCP deployment or mapping
* final capstone documentation and demo evidence

## Cross-Cutting Requirements Rule

The 48 AI labs must embed the mandatory requirements in `docs/ai-cross-cutting-requirements.md`.

These requirements do not increase the lab count. They are built into the existing 48 labs.

Every AI lab should include relevant evidence for:

* software engineering discipline
* MLOps / LLMOps
* AI security
* evaluation-first practice
* workflow orchestration
* data and model governance
* minimal product or interface layer

The cross-cutting checklist should be completed where relevant:

| Cross-cutting area | Evidence in this lab |
| --- | --- |
| Software engineering discipline | Code, structure, tests, docs, or repeatable execution |
| MLOps / LLMOps | Versioning, tracking, change log, rollback, or regression check |
| AI security | Security risk, control, or mitigation |
| Evaluation-first practice | Expected output, actual output, scoring, or review |
| Workflow orchestration | Repeatable command, task runner, scheduled job, or pipeline note |
| Governance | Data dictionary, lineage, model card, risk register, or approval note |
| Product/interface layer | CLI, API, dashboard, report, or demo improvement |

## Target Job Rule

The junior AI engineer job description must shape every lab.

Every lab must include a `Target job evidence` section showing how the lab maps to at least one requirement from the target role.

The target job requirements are:

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

## Core Rule

`AI Engineering` is a major backbone for this track, but the labs are organised for learning rather than grouped by book alone.

Related topics should be learned together.

The learning order is:

1. CS and engineering foundations
2. Data engineering and R foundations
3. statistical learning and ML foundations
4. LLMs, RAG, and agents
5. production AI across local, Azure, AWS, and GCP
6. capstone

`AI Engineering` chapters should still be mapped across the course through the coverage ledger. Supporting books should be mapped to the labs where they naturally fit.

## Source Stack

Primary AI source:

1. `AI Engineering`

Supporting sources:

2. `Hands-On Large Language Models` — LLM concepts, embeddings, retrieval, transformers, RAG, and practical LLM workflows
3. `Prompt Engineering for LLMs` — prompt design, structured outputs, prompt evaluation, and LLM application control
4. `An Introduction to Statistical Learning with Python` — classical ML, supervised learning, model evaluation, overfitting, validation, and feature engineering
5. `An Introduction to Statistical Learning with R` — statistical learning and model practice in R
6. `R for Data Science` — tidy data, transformation, visualisation, modelling workflow, and reporting
7. `Practical Statistics for Data Scientists` — statistics, distributions, sampling, experiments, and practical statistical reasoning
8. `Fundamentals of Data Engineering` — source systems, ingestion, storage, transformation, data quality, governance, serving, and lifecycle thinking
9. `Designing Data-Intensive Applications` — reliability, scalability, maintainability, storage, replication, and distributed-system trade-offs
10. `Database Internals` — storage engines, indexes, transactions, query behaviour, and distributed data-system internals
11. `Data Engineering Design Patterns` — pipeline, ingestion, validation, quality, and operational data patterns
12. `AI Systems Performance Engineering` — performance, inference cost, scaling, deployment constraints, and operational behaviour
13. `Observability Engineering` — AI observability, evaluation, monitoring, production signals, and operational visibility
14. `Redefining Data Engineering with AI` — AI-assisted data workflows, human-in-the-loop oversight, governance, and data product thinking
15. `AI Agents: The Definitive Guide` — agent design, tools, planning, memory, orchestration, safety, and evaluation; verify file availability before lab documentation

## Whole-Chapter and Coverage Rule

Use whole chapters as references.

Every lab must record:

* the primary chapter or source section used
* the supporting chapter or major section from each additional source, where relevant
* why each source was used
* how the source shaped the task

The aim is to cover all relevant content from the chosen books across the full 48-lab course.

Maintain a coverage ledger so every chapter or major section from the chosen books is assigned to at least one lab.

The coverage ledger should track:

| Source | Chapter or major section | Covered in lab | Coverage status | Notes |
| --- | --- | --- | --- | --- |
| Book name | Chapter number and title | Lab number | planned / completed / needs review | How it was used |

No copied book text should be committed to the repository.

## Embedded Layer Rule

AI labs should preserve the learning outcomes from the wider original track.

Where relevant, each AI lab should include:

| Layer | What to include |
| --- | --- |
| CS foundation | data structures, algorithms, OS concepts, complexity, networking, probability, or reliability maths |
| Data engineering | ingestion, transformation, quality, metadata, lineage, serving layer, or data product thinking |
| R | R data wrangling, visualisation, statistics, modelling, or model comparison |
| Local | local script, notebook, database, container, API, or application evidence |
| Azure | matching Azure service or implementation option |
| AWS | matching AWS service or implementation option |
| GCP | matching GCP service or implementation option |
| SRE / operations | reliability, monitoring, incident review, limitations, or production improvement |

## Local and Multi-Cloud Rule

Every major concept should be learned locally first.

Cloud-relevant concepts must then be mapped across Azure, AWS, and GCP.

The expected pattern is:

1. local implementation
2. Azure mapping or implementation
3. AWS mapping or implementation
4. GCP mapping or implementation

Not every lab needs a full hands-on deployment to all three clouds. However, every cloud-relevant lab must include a short Azure / AWS / GCP comparison. Dedicated cloud labs must include stronger implementation evidence.

Examples:

| Lab area | Local | Azure | AWS | GCP |
| --- | --- | --- | --- | --- |
| Object storage | local filesystem / MinIO | Blob Storage | S3 | Cloud Storage |
| App hosting | local FastAPI / Docker | App Service, Functions, Container Apps | Lambda, ECS, EC2 | Cloud Run, Cloud Functions, Compute Engine |
| Managed database | local PostgreSQL / SQLite | Azure SQL Database | RDS | Cloud SQL |
| Analytics | local DuckDB / PostgreSQL | Synapse, Fabric concepts | Athena, Redshift | BigQuery |
| Secrets | local env file pattern, never committed | Key Vault | Secrets Manager, Parameter Store | Secret Manager |
| Monitoring | local logs and metrics | Azure Monitor, Log Analytics | CloudWatch | Cloud Monitoring |
| AI platform | local model/API workflow | Azure AI Foundry, Azure Machine Learning | Bedrock, SageMaker | Vertex AI |

## Planned 48-Lab Sequence

### Phase 1 — CS and Engineering Foundations

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 01 | `lab-01-local-development-environment/` | Python, R, Git, Docker, SQL, repo layout, and first project skeleton |
| 02 | `lab-02-cs-introduction-for-ai/` | variables, types, functions, files, data structures, and reusable notes |
| 03 | `lab-03-algorithms-for-data-and-ai/` | search, grouping, sorting, deduplication, and complexity notes |
| 04 | `lab-04-http-rest-fastapi-basics/` | local FastAPI service for the growing AI project |
| 05 | `lab-05-sql-and-postgresql-foundations/` | local database for datasets, runs, prompts, outputs, and evaluations |
| 06 | `lab-06-cloud-foundations-azure-aws-gcp/` | local-to-cloud map for identity, storage, compute, networking, and monitoring |

### Phase 2 — Data Engineering and R Before AI

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 07 | `lab-07-data-engineering-lifecycle-and-source-systems/` | source-system inventory and data lifecycle for the cumulative project |
| 08 | `lab-08-local-data-ingestion-csv-json-api/` | CSV, JSON, or API ingestion into the local database |
| 09 | `lab-09-storage-design-files-tables-object-storage/` | storage layout, database tables, object-storage mapping, and trade-offs |
| 10 | `lab-10-sql-transformation-and-modelling/` | curated tables, SQL transformations, and modelled dataset |
| 11 | `lab-11-r-data-wrangling-and-visualisation/` | R/tidyverse analysis, plots, and EDA notes for the same dataset |
| 12 | `lab-12-python-and-r-dataset-comparison/` | same dataset analysed in Python and R with comparison notes |
| 13 | `lab-13-data-quality-checks-and-validation/` | validation rules, failed-record handling, and data quality report |
| 14 | `lab-14-pipeline-testing-and-repeatable-execution/` | repeatable pipeline command, tests, and regression checks |
| 15 | `lab-15-metadata-lineage-and-documentation/` | metadata table, lineage notes, data dictionary, and stakeholder summary |
| 16 | `lab-16-monitoring-and-incident-handling-for-pipelines/` | broken pipeline scenario, incident note, monitoring signal, and recovery evidence |
| 17 | `lab-17-data-product-and-serving-layer-design/` | data product contract, consumers, quality expectations, and serving design |
| 18 | `lab-18-data-engineering-review-local-azure-aws-gcp/` | review of data pipeline locally and across Azure, AWS, and GCP mappings |

### Phase 3 — ML and Statistical Learning

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 19 | `lab-19-exploratory-data-analysis-python-r/` | EDA in Python and R using the project dataset |
| 20 | `lab-20-practical-statistics-for-ai-datasets/` | distributions, sampling, uncertainty, and statistical interpretation |
| 21 | `lab-21-first-supervised-ml-model/` | baseline supervised model using the prepared dataset |
| 22 | `lab-22-feature-engineering/` | feature creation, feature documentation, and leakage checks |
| 23 | `lab-23-train-test-validation-and-metrics/` | train/test split, validation approach, and metrics |
| 24 | `lab-24-classification-and-regression-comparison/` | classification and regression comparison where appropriate |
| 25 | `lab-25-error-analysis-and-model-limitations/` | model errors, false positives/negatives, limitations, and improvement plan |
| 26 | `lab-26-model-evaluation-report-python-r/` | evaluation report using Python and R perspectives |
| 27 | `lab-27-local-model-serving-with-fastapi/` | local model-serving endpoint added to the existing API |
| 28 | `lab-28-ml-workflow-azure-ml-sagemaker-vertex-ai/` | local ML workflow mapped to Azure ML, SageMaker, and Vertex AI |

### Phase 4 — LLMs, RAG, and Agents

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 29 | `lab-29-llm-foundations-and-safe-usage/` | LLM basics, task boundaries, safe-use notes, and project use case |
| 30 | `lab-30-prompt-engineering-and-structured-outputs/` | prompt templates, structured outputs, and versioned prompt records |
| 31 | `lab-31-prompt-evaluation-and-failure-cases/` | prompt tests, expected outputs, actual outputs, and failure analysis |
| 32 | `lab-32-embeddings-and-semantic-search/` | embeddings and local semantic search over safe project documents |
| 33 | `lab-33-retrieval-index-design/` | indexing strategy, chunking notes, metadata, and retrieval tests |
| 34 | `lab-34-rag-over-runbooks-tickets-or-lab-notes/` | RAG workflow added to the cumulative project |
| 35 | `lab-35-rag-evaluation-citations-and-hallucination-checks/` | citation checks, retrieval quality, hallucination controls, and evaluation notes |
| 36 | `lab-36-ai-agents-planning-tools-memory-state/` | agent design with tools, memory, state, and boundaries |
| 37 | `lab-37-agent-workflow-simulation-human-approval/` | agent workflow simulation with human approval gates |
| 38 | `lab-38-agent-safety-failure-modes-and-escalation/` | agent failure modes, escalation criteria, and safety review |

### Phase 5 — Production AI Across Local, Azure, AWS, and GCP

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 39 | `lab-39-local-ai-application-end-to-end/` | local end-to-end AI/data application using previous components |
| 40 | `lab-40-deploy-ai-app-on-azure/` | Azure deployment or detailed Azure implementation evidence |
| 41 | `lab-41-deploy-ai-app-on-aws/` | AWS deployment or detailed AWS implementation evidence |
| 42 | `lab-42-deploy-ai-app-on-gcp/` | GCP deployment or detailed GCP implementation evidence |
| 43 | `lab-43-secrets-identity-and-access-control-cross-cloud/` | local, Azure, AWS, and GCP secrets and identity comparison |
| 44 | `lab-44-monitoring-and-observability-cross-cloud/` | local logs plus Azure Monitor, CloudWatch, and Cloud Monitoring mapping |
| 45 | `lab-45-performance-latency-throughput-and-cost-cross-cloud/` | performance and cost review across local and cloud options |
| 46 | `lab-46-ai-governance-data-handling-and-incident-response/` | governance, data handling, incident process, and production readiness |

### Phase 6 — Capstone

| Lab | Folder name | Main evidence |
| --- | --- | --- |
| 47 | `lab-47-capstone-design-architecture-data-cloud-risk-evaluation/` | architecture, dataset, cloud plan, risk register, and evaluation plan |
| 48 | `lab-48-capstone-build-demo-monitoring-and-interview-story/` | working AI/data app, tests, monitoring notes, demo evidence, and interview story |

## Manual-First Rule

Where a lab involves data preparation, model building, evaluation, retrieval, or operations workflow design, complete the manual baseline first.

AI tools may be used afterwards to assist with review, documentation, test case generation, comparison of approaches, evaluation checklist creation, explanation, and improvement ideas.

AI assistance must not replace understanding, verification, or manual reasoning.

## Per-Lab Required Sections

Each completed AI lab should include:

* lab summary
* target job evidence
* cumulative build dependency
* new capability added
* previous artefacts reused
* integration point with the growing project
* regression check where relevant
* source chapter or section used
* supporting reference table
* coverage ledger update
* embedded-layer table where relevant
* cross-cutting requirements checklist where relevant
* local implementation evidence where relevant
* Azure / AWS / GCP mapping or implementation evidence where relevant
* manual baseline where relevant
* AI-assisted follow-up where relevant
* files created or changed
* commands, scripts, notebooks, or application steps used
* test inputs and expected outputs
* actual outputs and evaluation result
* failure modes and limitations
* safety and data handling note
* production improvement note
* stakeholder-facing summary
* recruiter-facing summary
* seven reflection answers

## Evidence Rules

Use fictional, generated, personal, or safely sanitised data only.

Do not commit copied book text, live workplace material, private records, credentials, or sensitive screenshots.
