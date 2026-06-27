# Mac and AI Track Standard

## Purpose

This document defines the overall shape of the track.

The visible track name is now `Mac and AI`.

The track has two primary pillars:

1. Mac / Apple Administration
2. AI Engineering

Computer Science Foundations, Data Engineering, R, and cloud are not removed. They are embedded support threads that run through the AI side of the track so the learner still covers the material originally planned across the wider programme.

## Non-Negotiable Preservation Rule

Changing the track name to `Mac and AI` must not reduce the learning scope.

The learner should still cover the intended outcomes from:

* Mac / Apple administration
* computer science foundations
* data engineering
* R for data work and statistical learning
* AWS
* Azure
* Google Cloud Platform
* AI engineering
* SRE and operations-style evidence

The difference is organisation: these become parts of a single Mac and AI track rather than separate headline tracks.

## Pillar 1 — Mac Administration

The Mac labs remain unchanged.

The Mac Administration pillar continues to use:

* `Apple Device Management` as the skeleton
* two Apple Device Management chapters per lab
* `macOS Support Essentials` as the practical troubleshooting supplement
* `Modern Operating Systems` for operating-system depth
* `The Practice of System and Network Administration` for operational execution discipline
* the Mac-focused MSP job advert for role evidence

## Pillar 2 — AI Engineering

The AI Engineering pillar uses `AI Engineering` as the backbone.

One `AI Engineering` chapter should produce two labs.

The AI course is 30 labs total, assuming 15 backbone chapters.

The AI pillar also absorbs the supporting knowledge originally held in the CS, Data Engineering, R, AWS, GCP, and cloud folders.

## Computer Science Thread

Computer Science Foundations stay in the track as a serious foundation, not as a deleted topic.

CS should appear throughout the AI labs in the same way it would appear in a real CS and AI course.

Examples:

* embeddings and semantic search should include vectors, similarity, data structures, and algorithmic complexity
* RAG should include indexing, retrieval, filesystems, HTTP, APIs, and data structures
* AI agents should include state, control flow, queues, planning, and failure states
* AI application integration should include backend APIs, processes, sockets, memory, and operating-system behaviour
* AI performance should include latency, throughput, cost, saturation, and scaling
* AI observability should include metrics, logs, traces, evaluation datasets, and incident-style reasoning

## Data Engineering Thread

Data Engineering remains in the track as the data foundation for AI.

The learner should still cover ingestion, transformation, curation, data modelling, data quality, metadata, lineage, serving layers, monitoring, and data-product thinking.

The Data Engineering material should support AI labs through:

* clean datasets
* feature tables
* evaluation datasets
* data quality checks
* metadata and lineage notes
* data product documentation
* AI-assisted data workflows after the manual workflow is understood

## R Thread

R is now part of the data and AI learning path.

Drive resources found in the R folder:

* `R for Data Science`
* `Practical Statistics for Data Scientists`
* `An Introduction to Statistical Learning with R`

Use R for:

* tidy data workflows
* exploratory data analysis
* data visualisation
* statistical thinking
* regression and classification practice
* model evaluation comparison against Python
* producing analysis reports where useful

R should not replace Python in the AI track. Python remains the primary implementation language for AI engineering, while R adds statistical depth and data-analysis range.

## Multi-Cloud Thread

AWS, Azure, and GCP are not active standalone headline tracks for now.

They become a cross-cloud implementation layer.

For every cloud-relevant concept, the learner should understand how it maps across all three platforms:

| Capability | AWS | Azure | GCP |
| --- | --- | --- | --- |
| Object storage | S3 | Blob Storage | Cloud Storage |
| Compute / app hosting | EC2, Lambda, ECS | App Service, Functions, Container Apps | Compute Engine, Cloud Run, Cloud Functions |
| Managed relational database | RDS | Azure SQL Database | Cloud SQL |
| Data warehouse / analytics | Redshift, Athena | Synapse, Fabric concepts | BigQuery |
| Secrets | Secrets Manager, Parameter Store | Key Vault | Secret Manager |
| Monitoring | CloudWatch | Azure Monitor, Log Analytics | Cloud Monitoring |
| Identity and access | IAM | Entra ID, Azure RBAC | IAM |
| AI platform | Bedrock, SageMaker | Azure AI Foundry, Azure Machine Learning | Vertex AI |

The labs may use one platform hands-on at a time, but the documentation must include a short AWS / Azure / GCP mapping where the concept is cloud-relevant.

## Required Embedded-Layer Table

Every AI lab should include this table when relevant:

| Layer | What was covered | Evidence |
| --- | --- | --- |
| CS foundation | Concept used | Note, calculation, code, or explanation |
| Data engineering | Data task used | Dataset, pipeline, quality check, or model |
| R | R analysis or statistical method used | R script, notebook, plot, or comparison |
| AWS | Equivalent service or implementation option | Mapping or lab evidence |
| Azure | Equivalent service or implementation option | Mapping or lab evidence |
| GCP | Equivalent service or implementation option | Mapping or lab evidence |
| SRE / operations | Reliability, observability, or incident thinking | Verification, monitoring note, or limitation |

## Completion Standard

A Mac and AI lab is complete only when it preserves the right scope.

For Mac labs, this means Mac support, Apple device management, troubleshooting, documentation, and job evidence.

For AI labs, this means AI Engineering plus the relevant CS, data, R, multi-cloud, and operations layers.
