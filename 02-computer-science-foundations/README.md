# 02 — Computer Science Foundations

## Purpose

This folder contains labs for the maths, systems, logic, backend, and algorithmic foundations that support SRE-style work.

The goal is not abstract academic study. The goal is to understand enough computer science, backend engineering, and systems thinking to reason about reliability, performance, risk, incidents, and operational trade-offs.

This section is aligned to junior backend, SRE, platform, and operations-adjacent roles that require Python, FastAPI, REST APIs, PostgreSQL, Docker, GitHub workflow, CI/CD basics, reliability, scalability, and performance awareness.

## Whole-Chapter Rule

Use whole chapters as references, not disconnected extracts.

Every lab must record exactly which book chapters or documentation sections were used.

Use this format inside each lab:

| Source | Chapter or documentation section used | Why it was used |
| --- | --- | --- |
| Book or documentation name | Chapter number and title, or exact documentation page | Link to the lab task |

See `docs/computer-science-foundations-curriculum-standard.md` for the planned chapter map.

## Source Stack

Primary sources:

* `Computer Systems: A Programmer's Perspective`
* `Modern Operating Systems`
* `The Algorithm Design Manual`
* `Discrete Mathematics with Applications`
* `Fluent Python`
* official documentation for FastAPI, PostgreSQL, Docker, GitHub Actions, and Supabase

## Topic Focus

Labs in this folder may cover:

* Python backend foundations
* FastAPI endpoint design
* REST API structure
* PostgreSQL integration
* Docker packaging
* GitHub workflow and CI checks
* maths for SRE
* percentages, ratios, rates, and units
* averages, percentiles, distributions, and outliers
* SLI, SLO, SLA, and error-budget calculations
* probability and risk intuition
* latency, throughput, saturation, and capacity
* Big O and performance intuition
* data structures for logs, alerts, and events
* algorithms for searching, grouping, and deduplication
* operating systems concepts
* distributed systems basics

## Mandatory Career Layers

Every computer science foundations lab must also include:

* clear reasoning
* operational relevance
* plain-English explanation
* interview explanation
* recruiter-facing summary
* reflection on how the concept improves SRE judgement

## Example Lab Folder Names

```text
lab-01-python-backend-foundations/
lab-02-http-rest-and-fastapi-basics/
lab-03-postgresql-backed-api/
lab-04-service-data-modelling/
lab-05-dockerised-backend-service/
lab-06-github-workflow-and-ci/
lab-07-algorithms-for-operational-data/
lab-08-operating-system-concepts-for-backend-services/
lab-09-performance-latency-and-throughput/
lab-10-sli-slo-and-error-budget-calculator/
lab-11-supabase-auth-storage-and-realtime-concepts/
lab-12-backend-sre-helper-app-capstone/
```

## Evidence Standard

Evidence should include calculations, assumptions, examples, diagrams, small scripts, tests, API outputs, or service checks where useful.

Do not present maths or computer science as isolated theory. Connect each concept to backend behaviour, reliability, operational decisions, or job-facing evidence.
