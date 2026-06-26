# SRE Models and Applications Standard

## Purpose

This repository should not only contain notes. It should produce small models, scripts, dashboards, and applications that support SRE-style work.

The goal is to build practical artefacts that show the ability to reason with data, systems, reliability, cloud operations, and AI.

## What Counts as a Model

A model does not need to be advanced machine learning.

In this track, a model can be:

* a relational data model for tickets, alerts, incidents, services, or assets
* an SLO or error-budget calculation model
* a latency or availability model
* a data quality model
* a trend analysis model
* a simple risk-scoring model
* a rules-based triage model
* a basic ML model only when it is useful and explainable

## What Counts as an Application

An application can be small and practical.

Examples:

* ticket trend dashboard
* incident summary generator
* SLO calculator
* error-budget tracker
* service health report
* alert deduplication helper
* cloud cost summary tool
* runbook search tool
* AI-assisted ticket triage assistant
* data quality checker

## Application Rules

Every application should include:

* clear input data
* clear expected output
* safe fictional or sanitised sample data
* verification evidence
* limitations
* operational use case
* production risks
* README or usage instructions

## Data Engineering Link

The Data Engineering folder should provide the foundation for these tools:

* SQL
* relational modelling
* data quality
* pipelines
* reporting
* operational datasets
* reliability-focused analysis

`Designing Data-Intensive Applications` is a key reference for understanding why reliability, scalability, and maintainability matter when building data-backed operational systems.

## SRE Link

SREs do not need advanced maths for every role, but they do need enough maths and modelling ability to reason about:

* availability
* latency
* percentiles
* error rates
* error budgets
* capacity
* saturation
* trends
* risk
* cost
* reliability trade-offs

The Computer Science Foundations folder should support this, and the Data Engineering, AWS, GCP, and AI folders should turn it into practical tools.
