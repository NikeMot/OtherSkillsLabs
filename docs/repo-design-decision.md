# Repository Design Decision

## Decision

Use a topic-based repository structure for `OtherSkillsLabs`.

Top-level topic folders:

```text
01-mac-apple-administration/
02-computer-science-foundations/
03-data-engineering/
04-aws/
05-gcp/
06-ai/
docs/
```

## Reason

This repository is not a tool-by-tool infrastructure sequence. It is a professional capability repository built around six technical topic areas:

1. Mac / Apple Administration
2. Computer Science Foundations
3. Data Engineering
4. AWS
5. Google Cloud Platform
6. AI

The folder structure follows the intended progression toward practical SRE capability.

Mac / Apple administration is first because it directly supports mixed-estate enterprise support skills. Computer science foundations come second because SRE work benefits from reliability maths, systems thinking, algorithms, operating systems, and performance intuition. Data engineering comes third because SQL, data modelling, pipelines, and data quality are needed to build useful SRE datasets, reports, models, and helper applications. AWS and GCP follow because cloud administration and reliability are core SRE platform skills. AI remains last because it should build on the previous foundations and be used to create safe, useful SRE support tools.

Cybersecurity is intentionally not included in this repository because it will be handled in the networking path instead.

## Naming Convention

Use numbered, lowercase, hyphenated folder names:

```text
01-topic-name/
02-topic-name/
03-topic-name/
04-topic-name/
05-topic-name/
06-topic-name/
```

Individual labs should also use lowercase, hyphenated names:

```text
lab-01-enterprise-mac-access-issue/
lab-01-sre-maths-and-reliability-basics/
lab-01-query-support-ticket-data/
lab-01-aws-account-and-iam-basics/
lab-01-gcp-project-and-iam-basics/
lab-01-ai-assisted-ticket-triage/
```

## Lab Design Standard

Each lab has one primary technical topic, but must also include:

* thinking and diagnostic reasoning
* social or conversation practice
* personal branding output
* interview technique
* personal development reflection

This makes the repository useful as both a technical learning record and career evidence.

## Application-Building Standard

This track should produce small, useful models and applications that support SRE-style work.

Examples include:

* ticket trend analysis tools
* incident and alert datasets
* SLO and error-budget calculators
* reliability dashboards
* service health summary scripts
* data-backed incident reports
* AI-assisted runbook or ticket triage tools
* cloud cost and reliability summaries

These should use fictional or sanitised lab data only.

## Production Relevance

A clear repository structure makes it easier for hiring managers, recruiters, mentors, and future reviewers to understand the purpose of the work quickly. It also makes the evidence easier to maintain as the lab programme grows.
