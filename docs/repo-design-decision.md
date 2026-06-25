# Repository Design Decision

## Decision

Use a topic-based repository structure for `OtherSkillsLabs`.

Top-level topic folders:

```text
01-mac-apple-administration/
02-sql-databases/
03-ai/
docs/
```

## Reason

This repository is not a tool-by-tool infrastructure sequence. It is a professional capability repository built around three technical topic areas:

1. Mac / Apple Administration
2. SQL and Databases
3. AI

The folder structure therefore follows the topics of the lab programme rather than the tools used inside individual labs.

Mac / Apple administration is first because it directly supports mixed-estate enterprise support skills. SQL and databases are second because they strengthen data investigation, reporting, operational evidence, and support analysis. AI remains third as an automation and reasoning multiplier.

Cybersecurity is intentionally not included in this repository because it will be handled in the networking path instead.

## Naming Convention

Use numbered, lowercase, hyphenated folder names:

```text
01-topic-name/
02-topic-name/
03-topic-name/
```

Individual labs should also use lowercase, hyphenated names:

```text
lab-01-enterprise-mac-access-issue/
lab-01-query-support-ticket-data/
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

## Production Relevance

A clear repository structure makes it easier for hiring managers, recruiters, mentors, and future reviewers to understand the purpose of the work quickly. It also makes the evidence easier to maintain as the lab programme grows.
