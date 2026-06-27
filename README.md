# Other Skills Labs

## Overview

The `OtherSkillsLabs` repository contains hands-on labs for professional capability areas that sit outside the main infrastructure lab programme.

The repository focuses on six technical topics:

* Mac / Apple administration
* Computer science foundations
* Data engineering
* AWS
* Google Cloud Platform
* AI / LLM engineering

Every lab also develops the non-technical leverage skills needed to progress from Service Desk into stronger infrastructure, platform, data, cloud, SRE, and AI-enabled operations roles:

* structured thinking
* social and conversation skills
* communication under pressure
* personal branding
* interview technique
* leadership from the current role
* evidence-based self-development

The aim is not just to learn tools. The aim is to create proof that technical work can be investigated, explained, documented, discussed, and converted into career evidence.

The lab series is aligned to target junior roles in backend development, data engineering, cloud engineering, AI engineering, SRE, platform, and operations-adjacent work. See `docs/target-role-alignment.md` for the role-to-lab mapping.

---

## Goals

The goals of this repository are to:

* build practical capability in Apple administration, CS foundations, data engineering, AWS, GCP, and AI
* practise production-style troubleshooting and evidence collection
* turn every lab into interview, CV, LinkedIn, and recruiter-facing proof
* improve written and verbal communication around technical work
* develop confidence through documented evidence rather than vague self-belief
* create a public portfolio of learning and professional growth

---

## Skills covered

| Area | Status | Topics |
| ---- | ------ | ------ |
| Mac / Apple Administration | Not started | macOS support, FileVault, Keychain, MDM, Apple Business Manager, profiles, certificates, enterprise troubleshooting |
| Computer Science Foundations | Not started | maths for SRE, logic, data structures, algorithms, operating systems concepts, complexity, reliability thinking |
| Data Engineering | Not started | SQL, relational modelling, data pipelines, data quality, analytics, reporting, storage concepts, data-intensive systems |
| AWS | Not started | IAM, VPC, EC2, S3, RDS, CloudWatch, Route 53, load balancing, reliability, cost awareness |
| Google Cloud Platform | Not started | IAM, VPC, Compute Engine, Cloud Storage, Cloud SQL, Cloud Monitoring, Cloud DNS, load balancing, reliability, cost awareness |
| AI / LLM Engineering | Not started | prompt engineering, ticket triage, RAG, evaluation, hallucination checks, AI-assisted operations |

---

## Repository Structure

| Path | Purpose |
| ---- | ------- |
| `docs/` | General documentation, lab standards, decisions, and evidence rules |
| `01-mac-apple-administration/` | macOS and Apple enterprise administration labs |
| `02-computer-science-foundations/` | Maths, logic, algorithms, systems concepts, and reliability foundations |
| `03-data-engineering/` | SQL, databases, data quality, pipelines, and operational data labs |
| `04-aws/` | AWS cloud administration, operations, and reliability labs |
| `05-gcp/` | Google Cloud Platform administration, operations, and reliability labs |
| `06-ai/` | AI, LLM, prompt engineering, RAG, and AI operations labs |

The numbered folders represent topic areas. Lab folders inside each topic should use lowercase, hyphenated names, for example:

```text
01-mac-apple-administration/
└── lab-01-enterprise-mac-access-issue/

02-computer-science-foundations/
└── lab-01-sre-maths-and-reliability-basics/

03-data-engineering/
└── lab-01-query-support-ticket-data/

04-aws/
└── lab-01-aws-account-and-iam-basics/

05-gcp/
└── lab-01-gcp-project-and-iam-basics/

06-ai/
└── lab-01-ai-assisted-ticket-triage/
```

---

## Lab Design Rule

Each lab has one primary technical topic:

1. Mac / Apple Administration
2. Computer Science Foundations
3. Data Engineering
4. AWS
5. Google Cloud Platform
6. AI

Every lab must also include these leverage layers:

* thinking and diagnostic reasoning
* social or conversation practice
* personal branding output
* interview answer or STAR story
* personal development reflection

A lab is only complete when the technical work and the career-leverage outputs are both documented.

---

## How to use this repository

Each lab folder should contain a lab write-up with:

* scenario
* reference material
* requirements
* constraints and assumptions
* implementation tasks
* key commands or workflows
* verification evidence
* issues encountered
* decisions made
* security and production considerations
* final outcome
* what was learned
* what would be improved in production
* references used
* completion checklist
* reflection questions

Start with the first lab in the relevant topic folder.

---

## Security and Privacy Notes

This repository must not contain:

* passwords
* API keys
* SSH private keys
* `.env` files
* cloud credentials
* company data
* private user data
* tenant identifiers
* screenshots containing sensitive account information
* copyrighted books, PDFs, or EPUBs
* confidential recruiter or interview material

All examples should use fictional data, personal lab data, or safely sanitised outputs.

---

## Current Status

Repository structure updated to support six topic areas: Mac / Apple administration, computer science foundations, data engineering, AWS, GCP, and AI.
