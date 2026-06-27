# Target Role Alignment

## Purpose

This document maps the `OtherSkillsLabs` lab series to the real junior-level roles being targeted.

The aim is to avoid random learning. Each topic should produce evidence that maps to job requirements in backend development, data engineering, cloud engineering, AI engineering, SRE, platform, and operations-adjacent roles.

## Current Target Role Families

| Lab area | Target role family | Main evidence to produce |
| --- | --- | --- |
| `01-mac-apple-administration/` | Mac / Apple support and administration | macOS troubleshooting, Apple enterprise support workflow, user communication, escalation evidence |
| `02-computer-science-foundations/` | Junior backend / SRE foundations | Python, FastAPI, REST APIs, PostgreSQL integration, GitHub workflow, Docker, reliability and performance thinking |
| `03-data-engineering/` | Junior Data Engineer | SQL, Python, pipelines, datasets, data models, data quality checks, documentation, testing, monitoring, GCP awareness |
| `04-aws/` | Junior Cloud Engineer / SRE | IAM, networking, compute, storage, monitoring, troubleshooting, backup, IaC awareness, cost and reliability evidence |
| `05-gcp/` | Junior Cloud Engineer / Data Engineer / SRE | IAM, VPC, Compute Engine, Cloud Storage, Cloud SQL, monitoring, DNS, reliability, cost and GCP data-platform awareness |
| `06-ai/` | Junior AI Engineer / AI-enabled SRE | Python, Pandas, NumPy, scikit-learn, model evaluation, data preparation, AI application integration, deployment awareness |

---

## 01 — Mac / Apple Administration

### Target outcome

The Mac / Apple administration track should prepare evidence for Apple support and endpoint administration work.

### Evidence to produce

Labs should show ability to:

* troubleshoot macOS access and application issues
* explain FileVault, Keychain, Gatekeeper, certificates, and profiles
* understand Apple Business Manager and MDM concepts
* write clear user-facing support messages
* create escalation-quality notes
* distinguish what can be tested directly from what is documentation-based until real Mac access is available

### Note

A specific Mac / Apple target job description still needs to be added for precise alignment.

---

## 02 — Computer Science Foundations

### Target role signal

The target role includes:

* implementing backend features and endpoints using Python and FastAPI
* building scalable REST APIs that integrate with PostgreSQL
* contributing to AI-powered features with LangChain or similar frameworks
* writing clean and well-documented code
* contributing to CI/CD deployment using Docker
* collaborating through GitHub and maintaining code quality
* using Supabase for authentication, storage, and real-time features
* focusing on reliability, scalability, and performance
* working with product and frontend teams to deliver user experiences

### Lab direction

This section should become a practical computer science and backend foundations track, not only theory.

It should cover:

* Python fundamentals for backend work
* FastAPI endpoint design
* REST API structure
* PostgreSQL integration
* basic authentication concepts
* API testing
* Docker packaging
* GitHub pull-request workflow
* CI/CD basics
* reliability, scalability, and performance concepts
* clean code and documentation
* collaboration-focused technical communication

### Evidence to produce

Labs should produce:

* small FastAPI services
* documented REST endpoints
* PostgreSQL-backed features
* API tests
* Dockerfiles or compose files
* GitHub workflow evidence
* simple CI checks
* README usage instructions
* reliability notes and performance assumptions

---

## 03 — Data Engineering

### Target role signal

The target role includes:

* supporting development and maintenance of data pipelines
* ingesting, transforming, and curating data from source systems
* building datasets and data models for analytics, reporting, AI, and data products
* delivering well-scoped backlog tasks
* writing maintainable SQL and Python
* using version control, documentation, and testing
* learning modern data engineering tools, frameworks, and cloud platforms
* understanding performance, scalability, and cost
* implementing data quality checks and validation
* following governance, security, and access-control standards
* supporting monitoring, incident investigation, and data issue resolution
* communicating clearly with data engineers, analysts, BI developers, and data scientists

### Lab direction

This section should be a Data Engineering for SRE and Analytics track.

It should cover:

* SQL foundations
* Python data scripts
* relational modelling
* source-to-target pipeline thinking
* CSV/API-to-database ingestion
* transformation and curation
* data validation
* data quality checks
* dataset documentation
* operational monitoring of pipelines
* incident investigation for data issues
* GCP or cloud warehouse awareness
* data product thinking
* `Designing Data-Intensive Applications` concepts: reliability, scalability, maintainability, storage, replication, consistency, and data-system trade-offs

### Evidence to produce

Labs should produce:

* SQL queries
* data models
* sample datasets
* pipeline scripts
* data quality checks
* validation reports
* schema documentation
* pipeline README files
* test outputs
* incident notes for broken data pipelines
* small SRE-supporting data applications

---

## 04 — AWS

### Target role signal

The target role includes:

* deploying, configuring, maintaining, and supporting cloud infrastructure
* monitoring availability, performance, and cost efficiency
* implementing identity, access control, encryption, and security best practices
* troubleshooting cloud issues and escalating where needed
* contributing to automation with scripting or IaC tools such as Terraform or CloudFormation
* maintaining SOPs, configurations, and architecture diagrams
* supporting application deployments
* participating in performance testing, incident resolution, and root-cause analysis
* assisting with backup, disaster recovery, and failover planning

### Lab direction

The AWS section should focus on junior cloud engineering and SRE-ready operations.

It should cover:

* IAM
* VPCs, subnets, routing, DNS, and security groups
* EC2 operational support
* S3 access and lifecycle
* RDS basics
* CloudWatch monitoring and logging
* load balancing and health checks
* backup and recovery
* cost tagging and budgets
* Terraform or CloudFormation awareness
* incident evidence packs
* operational documentation

### Evidence to produce

Labs should produce:

* architecture diagrams
* configuration notes
* monitoring screenshots or sanitised outputs
* cost-control notes
* runbooks
* incident investigation notes
* root-cause analysis notes
* backup/restore evidence
* IaC snippets where appropriate

---

## 05 — Google Cloud Platform

### Target role signal

The target role overlaps with junior cloud engineering and data engineering requirements:

* basic cloud infrastructure knowledge
* GCP project and IAM concepts
* networking fundamentals
* compute, storage, database, monitoring, and DNS basics
* cloud cost and reliability awareness
* data engineering platform awareness, ideally GCP

### Lab direction

The GCP section should support both cloud engineering and junior data engineering targets.

It should cover:

* projects and IAM
* VPCs, subnets, firewall rules, and routes
* Compute Engine
* Cloud Storage
* Cloud SQL
* Cloud Monitoring and Logging
* Cloud DNS
* load balancing concepts
* backup and recovery
* labels and cost controls
* GCP data platform awareness
* incident investigation and support notes

### Evidence to produce

Labs should produce:

* GCP project structure notes
* IAM evidence
* network diagrams
* monitoring outputs
* Cloud SQL notes
* Cloud Storage lifecycle notes
* data-platform notes
* incident evidence packs
* cost and reliability summaries

---

## 06 — AI

### Target role signal

The target role includes:

* collaborating with senior engineers and data scientists to develop ML and AI models
* data wrangling, cleaning, and feature engineering
* deploying ML pipelines and integrating them into production
* evaluating model performance and recommending improvements
* using Python, NumPy, Pandas, scikit-learn, TensorFlow, or PyTorch
* understanding ML algorithms and model evaluation
* communicating clearly and collaborating well
* exposure to NLP, computer vision, recommender systems, cloud services, Git, and modern development practices

### Lab direction

The AI section should be practical and application-focused, especially for SRE and operational use cases.

It should cover:

* Python data preparation
* Pandas and NumPy basics
* feature engineering
* simple supervised learning
* model evaluation
* NLP for tickets and incident notes
* AI-assisted ticket triage
* AI-assisted runbook search
* model limitations and failure modes
* safe deployment thinking
* integration into a small FastAPI or script-based application

### Evidence to produce

Labs should produce:

* cleaned datasets
* notebooks or scripts
* feature engineering notes
* model evaluation outputs
* confusion matrices or scoring summaries where relevant
* application integration notes
* safety and limitation notes
* recruiter-facing summaries

---

## Cross-Track Evidence Standard

Every lab should produce evidence that can be reused in applications, interviews, LinkedIn posts, and portfolio discussions.

Evidence should show:

* what was built, fixed, analysed, or proved
* why it matters operationally
* what tools or concepts were used
* how the result was verified
* what would be improved in production
* how it maps to a target role

## Reflection Rule

At the end of each lab, only the seven standard reflection questions should be asked. The answers are added to the final lab documentation.
