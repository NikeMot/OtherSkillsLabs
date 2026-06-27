# Data Engineering Curriculum Standard

## Purpose

This document defines how the Data Engineering labs should be designed and documented.

The track targets junior data engineering roles where the evidence should show SQL, Python, data pipelines, datasets, data modelling, data quality checks, documentation, testing, monitoring, cloud platform awareness, and clear communication.

## Target Job Rule

The junior data engineering job description must shape every lab.

Every lab must include a `Target job evidence` section showing how the lab maps to at least one requirement from the target role.

The target job requirements are:

* pipeline development and maintenance
* ingestion, transformation, and curation
* building datasets and data models for analytics, reporting, AI, and data products
* delivering well-scoped backlog tasks
* SQL and Python
* version control and development workflow
* documentation and testing
* reusable patterns and components
* pipeline performance, scalability, and cost awareness
* data quality checks and validation
* governance, security, and access-control awareness
* monitoring and incident investigation
* communication with data engineers, analysts, BI developers, and data scientists
* clear progress reporting, questions, and issue communication
* increasing independence and quality over time

## Core Rule

`Fundamentals of Data Engineering` is the foundation for this track.

The first 11 labs are based on one chapter each from `Fundamentals of Data Engineering`.

After those 11 labs, the next 12 labs are drill and deepening labs. They repeat, combine, and deepen the manual skills from the first 11 labs.

The final lab is a capstone project.

Total: 24 labs.

## Manual-First AI Rule

The learner should learn and complete each data engineering task manually first.

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
4. `Data Engineering Design Patterns` — task execution patterns, pipeline patterns, data quality patterns, ingestion patterns, security patterns, and operational design choices
5. `Redefining Data Engineering with AI` — AI augmentation after the manual workflow has been completed and understood

## Whole-Chapter and Coverage Rule

Use whole chapters as references.

Every lab must record:

* the `Fundamentals of Data Engineering` chapter used, where relevant
* the augmentation chapter or section from each supporting source, where relevant
* why each source was used
* how the source shaped the task

The aim is to cover all relevant book content across the full track. Maintain a coverage ledger so that every chapter or major section from the chosen books is assigned to at least one lab.

The coverage ledger should track:

| Source | Chapter or major section | Covered in lab | Coverage status | Notes |
| --- | --- | --- | --- | --- |
| Book name | Chapter number and title | Lab number | planned / completed / needs review | How it was used |

No copied book text should be committed to the repository.

## Planned 24-Lab Sequence

| Lab | Folder name | Foundation | Main evidence |
| --- | --- | --- | --- |
| 01 | `lab-01-data-engineering-described/` | Fundamentals chapter 1 | Role map, stakeholder map, data engineering responsibilities |
| 02 | `lab-02-data-engineering-lifecycle/` | Fundamentals chapter 2 | Data lifecycle diagram and manual pipeline plan |
| 03 | `lab-03-good-data-architecture/` | Fundamentals chapter 3 | Data architecture decision record |
| 04 | `lab-04-technology-selection-for-data-pipelines/` | Fundamentals chapter 4 | Tool choice matrix and trade-off notes |
| 05 | `lab-05-source-systems-and-operational-data/` | Fundamentals chapter 5 | Source-system inventory and sample source dataset |
| 06 | `lab-06-data-storage-layouts/` | Fundamentals chapter 6 | Storage layout, schema notes, and data organisation evidence |
| 07 | `lab-07-data-ingestion-pipeline/` | Fundamentals chapter 7 | Manual ingestion pipeline from file or API to database |
| 08 | `lab-08-query-modelling-and-transformation/` | Fundamentals chapter 8 | SQL transformation and modelled dataset |
| 09 | `lab-09-serving-data-for-analytics-and-ai/` | Fundamentals chapter 9 | Analytics-ready dataset and serving notes |
| 10 | `lab-10-data-governance-quality-and-access/` | Fundamentals chapter 10 | Data quality checks, access assumptions, and governance notes |
| 11 | `lab-11-future-of-data-engineering-and-ai-awareness/` | Fundamentals chapter 11 | Future-readiness note and AI augmentation boundary |
| 12 | `lab-12-sql-and-data-modelling-drill/` | Drill lab | Repeated SQL modelling and schema design practice |
| 13 | `lab-13-ingestion-drill/` | Drill lab | Repeat ingestion from multiple source formats |
| 14 | `lab-14-transformation-and-curation-drill/` | Drill lab | Repeat transformations and curated dataset creation |
| 15 | `lab-15-data-quality-validation-drill/` | Drill lab | Repeated data quality checks and validation report |
| 16 | `lab-16-pipeline-testing-and-automation-drill/` | Drill lab | Tests, repeatable commands, and simple automation |
| 17 | `lab-17-storage-and-database-internals-drill/` | Drill lab | Storage layout, indexes, transactions, and database behaviour notes |
| 18 | `lab-18-query-performance-and-cost-drill/` | Drill lab | Query performance, cost assumptions, and scaling notes |
| 19 | `lab-19-batch-streaming-and-cdc-drill/` | Drill lab | Batch, streaming, and change-data-capture comparison |
| 20 | `lab-20-monitoring-and-incident-drill/` | Drill lab | Broken pipeline investigation and incident evidence |
| 21 | `lab-21-governance-lineage-and-documentation-drill/` | Drill lab | Dataset documentation, lineage notes, governance notes, and stakeholder summary |
| 22 | `lab-22-data-product-and-serving-layer-drill/` | Drill lab | Data product thinking, serving contract, consumers, and quality expectations |
| 23 | `lab-23-ai-augmentation-after-manual-data-engineering/` | Drill lab | AI-assisted review after manual SQL, pipeline, quality, metadata, and documentation work |
| 24 | `lab-24-junior-data-engineering-capstone/` | Capstone project | End-to-end pipeline, quality checks, serving layer, monitoring notes, documentation, and interview evidence |

## First 11 Labs Chapter Map

The planned chapter titles should be verified against the edition being used before each lab is documented.

| Lab | Fundamentals of Data Engineering chapter |
| --- | --- |
| 01 | Chapter 1 — Data Engineering Described |
| 02 | Chapter 2 — The Data Engineering Lifecycle |
| 03 | Chapter 3 — Designing Good Data Architecture |
| 04 | Chapter 4 — Choosing Technologies Across the Data Engineering Lifecycle |
| 05 | Chapter 5 — Data Generation in Source Systems |
| 06 | Chapter 6 — Storage |
| 07 | Chapter 7 — Ingestion |
| 08 | Chapter 8 — Queries, Modeling, and Transformation |
| 09 | Chapter 9 — Serving Data for Analytics, Machine Learning, and Reverse ETL |
| 10 | Chapter 10 — Security and Privacy |
| 11 | Chapter 11 — The Future of Data Engineering |

## Augmentation Rule

Every lab should include an augmentation table where relevant.

| Augmentation source | Chapter or section used | How it changed the task |
| --- | --- | --- |
| Designing Data-Intensive Applications | Chapter or section title | Reliability, scalability, maintainability, storage, replication, consistency, or trade-off depth |
| Database Internals | Chapter or section title | Database storage, indexes, transactions, query behaviour, storage engines, or internals depth |
| Data Engineering Design Patterns | Pattern or chapter | Execution pattern chosen for the task |
| Redefining Data Engineering with AI | Chapter or section title | AI-assisted version after the manual workflow |

## Per-Lab Required Sections

Each completed Data Engineering lab should include:

* lab summary
* target job evidence
* `Fundamentals of Data Engineering` chapter used
* augmentation reference table
* coverage ledger update
* manual workflow
* AI-assisted follow-up, only after the manual workflow
* files created or changed
* commands, SQL, or Python scripts used
* data model or pipeline diagram where useful
* data quality checks
* verification evidence
* monitoring or incident consideration where relevant
* production improvement note
* stakeholder-facing summary
* recruiter-facing summary
* seven reflection answers

## Evidence Rules

Use fictional, generated, personal, or safely sanitised data only.

Do not commit copied book text, live workplace material, private records, credentials, or sensitive screenshots.
