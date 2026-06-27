# AI Cross-Cutting Requirements

## Purpose

This document defines the mandatory cross-cutting requirements for the AI section of the `Mac and AI` track.

These requirements do not increase the lab count. They must be embedded inside the existing 48 cumulative AI labs.

Mac labs remain separate and are not affected by this document.

## Requirement 1 — Software Engineering Discipline

Every AI lab should improve or preserve the quality of the cumulative codebase.

Include the relevant items as the project grows:

* clear project structure
* readable Python and R code
* meaningful file and folder names
* reusable functions or modules
* unit tests where useful
* integration tests where useful
* linting or formatting where useful
* Git workflow and commit hygiene
* dependency management
* Docker or repeatable local execution where useful
* environment-variable pattern without committing secrets
* README or usage instructions
* regression checks when previous functionality could be affected

## Requirement 2 — MLOps and LLMOps

AI work must be controlled, versioned, and testable.

Include the relevant items as the project grows:

* dataset versioning notes
* experiment tracking notes
* model versioning notes
* prompt versioning notes
* evaluation versioning notes
* model or prompt change log
* model registry concept where relevant
* rollback plan where relevant
* regression tests for prompts, retrieval, and models
* release notes for meaningful changes
* comparison between old and new behaviour

## Requirement 3 — AI Security

AI safety must include security, not just responsible-use language.

Include the relevant items as the project grows:

* prompt-injection risk
* data leakage risk
* unsafe tool-use risk
* secrets exposure risk
* over-permissioned agent risk
* PII or sensitive-data handling
* RAG source-poisoning risk
* dependency risk
* input validation
* output handling
* human approval gates
* least-privilege access thinking
* cloud identity and secrets mapping across Azure, AWS, and GCP where relevant

## Requirement 4 — Evaluation-First Practice

Every meaningful AI feature must have an evaluation method.

Include the relevant items as the project grows:

* golden dataset or test set where relevant
* expected outputs
* actual outputs
* pass/fail criteria
* manual review notes
* automated scoring where useful
* hallucination checks
* retrieval-quality checks
* model-quality checks
* prompt regression checks
* model regression checks
* drift concept where relevant
* limitations and failure cases

## Requirement 5 — Workflow Orchestration

Data and AI workflows must become repeatable.

Include the relevant items as the project grows:

* manual command first
* script-based repeatable workflow
* Makefile, task runner, or equivalent where useful
* scheduled-script concept
* cron concept where useful
* GitHub Actions workflow where useful
* pipeline orchestration concept using Prefect, Dagster, or Airflow where useful
* cloud scheduled-job mapping across Azure, AWS, and GCP where relevant
* failure and retry thinking
* logging for each workflow run

The learner does not need to master every orchestration tool. The goal is to understand how local scripts become reliable, repeatable pipelines.

## Requirement 6 — Data and Model Governance

AI systems must produce governance evidence.

Include the relevant items as the project grows:

* data dictionary
* dataset documentation
* lineage notes
* data quality report
* model card where relevant
* prompt card where relevant
* evaluation report
* risk register
* approval process
* data-retention note
* access-control note
* audit-trail concept
* stakeholder-facing summary

## Requirement 7 — Minimal Product or Interface Layer

The cumulative AI project must become usable, not just technically correct.

At minimum, the final project should expose one usable interface:

* CLI tool
* FastAPI endpoint and docs page
* Streamlit dashboard
* notebook report
* simple web UI

The interface should make the project understandable within 60 seconds.

It should show:

* what the system does
* what input it expects
* what output it produces
* how reliable the output is
* known limitations
* when a human should review the result

## Per-Lab Cross-Cutting Checklist

Each AI lab should include this checklist where relevant:

| Cross-cutting area | Evidence in this lab |
| --- | --- |
| Software engineering discipline | Code, structure, tests, docs, or repeatable execution |
| MLOps / LLMOps | Versioning, tracking, change log, rollback, or regression check |
| AI security | Security risk, control, or mitigation |
| Evaluation-first practice | Expected output, actual output, scoring, or review |
| Workflow orchestration | Repeatable command, task runner, scheduled job, or pipeline note |
| Governance | Data dictionary, lineage, model card, risk register, or approval note |
| Product/interface layer | CLI, API, dashboard, report, or demo improvement |

## Completion Rule

A completed AI lab should not merely show that something ran.

It should show that the work is understandable, repeatable, testable, safer than a naive implementation, and useful as part of the growing AI Operations and Data Assistant project.
