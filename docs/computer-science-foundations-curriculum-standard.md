# Computer Science Foundations Curriculum Standard

## Purpose

This document defines how the Computer Science Foundations labs should use reference material.

The track supports junior backend, SRE, platform, and operations-adjacent roles. The focus is practical: Python, FastAPI, REST APIs, PostgreSQL, Docker, GitHub workflow, CI/CD basics, reliability, scalability, and performance.

## Whole-Chapter Rule

Use whole chapters as references.

Do not use disconnected extracts from different parts of a book without recording the chapter context.

Every lab must include a reference table that names:

* the book or documentation source
* the chapter number
* the chapter title
* why that chapter was used for the lab

No copied book text should be committed to the repository.

## Source Stack

Primary sources:

1. Computer Systems: A Programmer's Perspective
2. Modern Operating Systems
3. The Algorithm Design Manual
4. Discrete Mathematics with Applications
5. Fluent Python
6. Official documentation for FastAPI, PostgreSQL, Docker, GitHub Actions, and Supabase

## Planned Lab Sequence

| Lab | Folder name | Primary outcome |
| --- | --- | --- |
| 01 | lab-01-python-backend-foundations | Clean Python module with tests |
| 02 | lab-02-http-rest-and-fastapi-basics | Small FastAPI service |
| 03 | lab-03-postgresql-backed-api | API connected to PostgreSQL |
| 04 | lab-04-service-data-modelling | Data model for users, tickets, services, and incidents |
| 05 | lab-05-dockerised-backend-service | Dockerised local backend service |
| 06 | lab-06-github-workflow-and-ci | GitHub workflow with automated checks |
| 07 | lab-07-algorithms-for-operational-data | Searching, grouping, and deduplication for operational data |
| 08 | lab-08-operating-system-concepts-for-backend-services | Processes, memory, files, sockets, and services |
| 09 | lab-09-performance-latency-and-throughput | Latency, throughput, and bottleneck analysis |
| 10 | lab-10-sli-slo-and-error-budget-calculator | Small reliability calculator |
| 11 | lab-11-supabase-auth-storage-and-realtime-concepts | Supabase-style architecture notes |
| 12 | lab-12-backend-sre-helper-app-capstone | Small backend or SRE helper application |

## Planned Chapter Map

The exact chapter titles must be verified against the edition being used before each lab is documented.

| Lab | Book chapter references to record |
| --- | --- |
| 01 | Fluent Python chapter 1; Computer Systems: A Programmer's Perspective chapter 1 |
| 02 | Computer Systems: A Programmer's Perspective chapter 10; Modern Operating Systems networking or input-output chapter |
| 03 | Computer Systems: A Programmer's Perspective chapter 10; Modern Operating Systems file-system or input-output chapter |
| 04 | Discrete Mathematics with Applications chapter on relations; The Algorithm Design Manual chapter on data structures |
| 05 | Modern Operating Systems chapter on processes or virtualisation |
| 06 | Fluent Python chapter on functions or modules |
| 07 | The Algorithm Design Manual chapters 3 and 4 |
| 08 | Modern Operating Systems chapters on processes and memory management; Computer Systems: A Programmer's Perspective chapter on control flow or virtual memory |
| 09 | Computer Systems: A Programmer's Perspective chapter on performance optimisation; Modern Operating Systems chapter on scheduling or input-output |
| 10 | Discrete Mathematics with Applications chapter on counting or probability |
| 11 | Computer Systems: A Programmer's Perspective chapter on system input-output; Modern Operating Systems chapter on networked or distributed systems if present in the available edition |
| 12 | Select the most relevant whole chapters already used in Labs 01-11 and record them explicitly |

## Per-Lab Reference Table

Every lab must include this table:

| Source | Chapter or documentation section used | Why it was used |
| --- | --- | --- |
| Book or documentation name | Chapter number and title, or exact documentation page | Link to the lab task |

## Required Output

Each completed lab should include:

* lab summary
* target role skill mapping
* whole-chapter reference table
* implementation notes
* files created or changed
* commands run
* verification evidence
* systems depth note
* SRE relevance note
* production improvement note
* recruiter-facing summary
* seven reflection answers
