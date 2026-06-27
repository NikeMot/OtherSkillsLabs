# Mac and AI Labs

## Overview

The `OtherSkillsLabs` repository now supports one visible track: `Mac and AI`.

The track has two primary pillars:

* Mac / Apple Administration
* AI Engineering

Computer Science Foundations, Data Engineering, R, AWS, Azure, and GCP are not removed. They are embedded support threads that run through the AI side of the track so the learner still covers the material originally planned across the wider programme.

The aim is not just to learn tools. The aim is to create proof that technical work can be investigated, explained, documented, discussed, and converted into career evidence.

See `docs/mac-and-ai-track-standard.md` for the full track standard.

---

## Goals

The goals of this repository are to:

* build practical capability in Mac administration and AI engineering
* keep computer science foundations inside the AI learning path
* keep data engineering inside the AI learning path through datasets, pipelines, quality checks, and data products
* add R for data analysis, statistics, visualisation, and statistical learning
* use AWS, Azure, and GCP as a cross-cloud implementation layer
* practise production-style troubleshooting and evidence collection
* turn every lab into interview, CV, LinkedIn, and recruiter-facing proof
* improve written and verbal communication around technical work
* develop confidence through documented evidence rather than vague self-belief
* create a public portfolio of learning and professional growth

---

## Skills covered

| Area | Status | Role in the track |
| ---- | ------ | ------ |
| Mac / Apple Administration | Not started | Primary pillar: macOS support, FileVault, Keychain, MDM, Apple Business Manager, profiles, certificates, enterprise troubleshooting |
| AI Engineering | Not started | Primary pillar: AI Engineering backbone, ML foundations, LLMs, RAG, agents, evaluation, observability, AI applications |
| Computer Science Foundations | Embedded | CS depth for AI: maths, logic, data structures, algorithms, operating systems, complexity, reliability thinking |
| Data Engineering | Embedded | Data foundation for AI: SQL, modelling, pipelines, data quality, metadata, lineage, serving layers, data products |
| R | Embedded | Data analysis, visualisation, statistics, statistical learning, model comparison, reporting |
| AWS | Embedded | Cross-cloud mapping and implementation option for storage, compute, databases, monitoring, identity, and AI services |
| Azure | Embedded | Cross-cloud mapping and implementation option for storage, compute, databases, monitoring, identity, and AI services |
| Google Cloud Platform | Embedded | Cross-cloud mapping and implementation option for storage, compute, databases, monitoring, identity, and AI services |

---

## Repository Structure

| Path | Purpose |
| ---- | ------- |
| `docs/` | General documentation, lab standards, decisions, and evidence rules |
| `01-mac-apple-administration/` | macOS and Apple enterprise administration labs; unchanged Mac pillar |
| `02-computer-science-foundations/` | CS foundation material kept as an embedded AI-supporting thread |
| `03-data-engineering/` | Data engineering material kept as an embedded AI-supporting thread, including R where useful |
| `04-aws/` | AWS reference and implementation material for cross-cloud mapping |
| `05-gcp/` | GCP reference and implementation material for cross-cloud mapping |
| `06-ai/` | Main AI Engineering course and AI application labs |

The numbered folders remain for organisation and evidence management. The visible track name is still `Mac and AI`.

---

## Lab Design Rule

Each lab belongs to one of the two visible pillars:

1. Mac / Apple Administration
2. AI Engineering

Mac labs follow the existing Mac curriculum and remain unchanged.

AI labs must include relevant embedded layers where useful:

* computer science foundation
* data engineering foundation
* R analysis or statistical learning
* AWS mapping or implementation option
* Azure mapping or implementation option
* GCP mapping or implementation option
* SRE or operations evidence

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
* production considerations
* final outcome
* what was learned
* what would be improved in production
* references used
* completion checklist
* reflection questions

Start with the first lab in either the Mac pillar or the AI pillar.

---

## Privacy Notes

This repository must not contain private values, company data, private user data, account identifiers, sensitive screenshots, copied book text, or confidential recruiter/interview material.

All examples should use fictional data, personal lab data, or safely sanitised outputs.

---

## Current Status

Repository structure updated to support the `Mac and AI` track while preserving the original CS, data engineering, R, AWS, Azure, GCP, SRE, and operations learning outcomes as embedded layers.
