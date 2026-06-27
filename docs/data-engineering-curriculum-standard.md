# Data Engineering Curriculum Standard

## Purpose

This document defines how the Data Engineering material should be designed and documented inside the `Mac and AI` track.

Data Engineering is no longer a separate visible headline track. It is an embedded data foundation for AI engineering.

The learner should still cover the original Data Engineering outcomes: SQL, Python, R, data pipelines, datasets, data modelling, data quality checks, documentation, testing, monitoring, cloud platform awareness, and clear communication.

## Target Job Rule

The junior data engineering job description must still shape the data engineering thread.

Every data-heavy AI lab must include a `Target job evidence` section where relevant.

The target job requirements are:

* pipeline development and maintenance
* ingestion, transformation, and curation
* building datasets and data models for analytics, reporting, AI, and data products
* delivering well-scoped backlog tasks
* SQL, Python, and R where useful
* version control and development workflow
* documentation and testing
* reusable patterns and components
* pipeline performance, scalability, and cost awareness
* data quality checks and validation
* governance and access awareness
* monitoring and incident investigation
* communication with data engineers, analysts, BI developers, and data scientists
* clear progress reporting, questions, and issue communication
* increasing independence and quality over time

## Core Rule

`Fundamentals of Data Engineering` remains the foundation for this thread.

The first 11 data engineering outcomes are based on one chapter each from `Fundamentals of Data Engineering`.

After those 11 outcomes, the next 12 outcomes are drill and deepening outcomes. They repeat, combine, and deepen the manual skills from the first 11 outcomes.

The final data engineering outcome is a capstone-style contribution to the AI track.

Total: 24 data engineering outcomes preserved.

## R Rule

R is part of the data and AI learning path.

Drive resources found in the R folder:

* `R for Data Science`
* `Practical Statistics for Data Scientists`
* `An Introduction to Statistical Learning with R`

Use R for:

* tidy data workflows
* exploratory data analysis
* visualisation
* statistical reasoning
* regression and classification practice
* model evaluation comparison against Python
* analysis reporting

Python remains the primary implementation language for AI engineering. R adds statistical and data-analysis depth.

## Manual-First AI Rule

The learner should learn and complete each data engineering, R, or statistical task manually first.

`Redefining Data Engineering with AI` should be used only after the manual version is understood. Its role is to show how AI can assist with documentation, design review, test generation, quality checks, metadata work, explanation, workflow acceleration, and AI-era data product thinking.

AI should not replace the manual learning phase.

Each AI-assisted lab note should clearly separate:

* what was done manually
* what AI helped with afterwards
* what was verified by the learner
* what limitations or risks were found

## Source Stack

Primary source:

1. `Fundamentals of Data Engineering`

Augmentation sources:

2. `Designing Data-Intensive Applications` — reliability, scalability, maintainability, distributed systems, storage, replication, consistency, and data-system trade-offs
3. `Database Internals: A Deep Dive into How Distributed Data Systems Work` by Alex Petrov — database storage, indexing, transactions, query behaviour, storage engines, and distributed data-system internals; verify file availability before each lab write-up
4. `Data Engineering Design Patterns` — task execution patterns, pipeline patterns, data quality patterns, ingestion patterns, and operational design choices
5. `Redefining Data Engineering with AI` — AI augmentation after the manual workflow has been completed and understood
6. `R for Data Science` — tidy data, transformation, visualisation, modelling workflow, and reporting
7. `Practical Statistics for Data Scientists` — statistics, distributions, sampling, experiments, and practical statistical reasoning
8. `An Introduction to Statistical Learning with R` — statistical learning, model practice, and R-based ML foundations

## Whole-Chapter and Coverage Rule

Use whole chapters as references.

Every data-heavy lab must record:

* the `Fundamentals of Data Engineering` chapter used, where relevant
* the augmentation chapter or section from each supporting source, where relevant
* the R source chapter or section used, where relevant
* why each source was used
* how the source shaped the task

The aim is to cover all relevant book content across the full `Mac and AI` track. Maintain a coverage ledger so that every chapter or major section from the chosen books is assigned to at least one lab.

The coverage ledger should track:

| Source | Chapter or major section | Covered in lab | Coverage status | Notes |
| --- | --- | --- | --- | --- |
| Book name | Chapter number and title | Lab number | planned / completed / needs review | How it was used |

No copied book text should be committed to the repository.

## Planned 24 Data Engineering Outcomes

| Outcome | Folder or lab reference | Foundation | Main evidence |
| --- | --- | --- | --- |
| 01 | `data-engineering-described` | Fundamentals chapter 1 | Role map, stakeholder map, data engineering responsibilities |
| 02 | `data-engineering-lifecycle` | Fundamentals chapter 2 | Data lifecycle diagram and manual pipeline plan |
| 03 | `good-data-architecture` | Fundamentals chapter 3 | Data architecture decision record |
| 04 | `technology-selection-for-data-pipelines` | Fundamentals chapter 4 | Tool choice matrix and trade-off notes |
| 05 | `source-systems-and-operational-data` | Fundamentals chapter 5 | Source-system inventory and sample source dataset |
| 06 | `data-storage-layouts` | Fundamentals chapter 6 | Storage layout, schema notes, and data organisation evidence |
| 07 | `data-ingestion-pipeline` | Fundamentals chapter 7 | Manual ingestion pipeline from file or API to database |
| 08 | `query-modelling-and-transformation` | Fundamentals chapter 8 | SQL transformation and modelled dataset |
| 09 | `serving-data-for-analytics-and-ai` | Fundamentals chapter 9 | Analytics-ready dataset and serving notes |
| 10 | `data-governance-quality-and-access` | Fundamentals chapter 10 | Data quality checks, access assumptions, and governance notes |
| 11 | `future-of-data-engineering-and-ai-awareness` | Fundamentals chapter 11 | Future-readiness note and AI augmentation boundary |
| 12 | `sql-and-data-modelling-drill` | Drill outcome | Repeated SQL modelling and schema design practice |
| 13 | `ingestion-drill` | Drill outcome | Repeat ingestion from multiple source formats |
| 14 | `transformation-and-curation-drill` | Drill outcome | Repeat transformations and curated dataset creation |
| 15 | `data-quality-validation-drill` | Drill outcome | Repeated data quality checks and validation report |
| 16 | `pipeline-testing-and-automation-drill` | Drill outcome | Tests, repeatable commands, and simple automation |
| 17 | `storage-and-database-internals-drill` | Drill outcome | Storage layout, indexes, transactions, and database behaviour notes |
| 18 | `query-performance-and-cost-drill` | Drill outcome | Query performance, cost assumptions, and scaling notes |
| 19 | `batch-streaming-and-cdc-drill` | Drill outcome | Batch, streaming, and change-data-capture comparison |
| 20 | `monitoring-and-incident-drill` | Drill outcome | Broken pipeline investigation and incident evidence |
| 21 | `governance-lineage-and-documentation-drill` | Drill outcome | Dataset documentation, lineage notes, governance notes, and stakeholder summary |
| 22 | `data-product-and-serving-layer-drill` | Drill outcome | Data product thinking, serving contract, consumers, and quality expectations |
| 23 | `ai-augmentation-after-manual-data-engineering` | Drill outcome | AI-assisted review after manual SQL, pipeline, quality, metadata, and documentation work |
| 24 | `junior-data-engineering-capstone` | Capstone contribution | End-to-end pipeline, quality checks, serving layer, monitoring notes, documentation, and interview evidence |

## Multi-Cloud Data Mapping

Every cloud-relevant data engineering note should map the concept across AWS, Azure, and GCP.

| Capability | AWS | Azure | GCP |
| --- | --- | --- | --- |
| Object storage | S3 | Blob Storage | Cloud Storage |
| Relational database | RDS | Azure SQL Database | Cloud SQL |
| Data warehouse or analytics | Redshift, Athena | Synapse, Fabric concepts | BigQuery |
| Secrets | Secrets Manager, Parameter Store | Key Vault | Secret Manager |
| Monitoring | CloudWatch | Azure Monitor, Log Analytics | Cloud Monitoring |
| AI platform integration | Bedrock, SageMaker | Azure AI Foundry, Azure Machine Learning | Vertex AI |

## Per-Lab Required Sections

Each data-heavy AI lab should include, where relevant:

* lab summary
* target job evidence
* `Fundamentals of Data Engineering` chapter used
* R source used
* augmentation reference table
* coverage ledger update
* manual workflow
* AI-assisted follow-up, only after the manual workflow
* files created or changed
* commands, SQL, Python, or R scripts used
* data model or pipeline diagram where useful
* data quality checks
* verification evidence
* monitoring or incident consideration where relevant
* AWS / Azure / GCP mapping where relevant
* production improvement note
* stakeholder-facing summary
* recruiter-facing summary
* seven reflection answers

## Evidence Rules

Use fictional, generated, personal, or safely sanitised data only.

Do not commit copied book text, live workplace material, private records, credentials, or sensitive screenshots.
