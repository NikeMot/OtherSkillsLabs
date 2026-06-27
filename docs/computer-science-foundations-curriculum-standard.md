# Computer Science Foundations Curriculum Standard

## Purpose

This document defines how Computer Science Foundations should be used inside the `Mac and AI` track.

Computer Science Foundations are not removed. They remain an embedded foundation for the AI Engineering pillar, similar to what would be expected in a serious CS and AI course.

The focus is practical: Python, APIs, data structures, algorithms, operating systems, databases, reliability, scalability, performance, and clear technical reasoning.

## Embedded CS Rule

Every AI lab should include a CS foundation note where relevant.

The CS note should explain the underlying concept that makes the AI, data, backend, or operations task work.

Examples:

* embeddings and semantic search -> vectors, similarity, indexing, and complexity
* RAG -> retrieval, data structures, files, HTTP, APIs, and source ranking
* agents -> state, queues, planning, control flow, and failure states
* AI application integration -> processes, sockets, memory, files, and API behaviour
* AI performance -> latency, throughput, bottlenecks, cost, and scaling
* AI observability -> metrics, logs, traces, probability, and incident reasoning

## Target Job Rule

The backend and AI job descriptions should shape CS evidence.

Each CS-supported lab should show how the concept improves at least one of:

* Python backend feature work
* FastAPI endpoint implementation
* REST API design
* PostgreSQL or database integration
* clean and documented code
* Docker-based delivery awareness
* GitHub collaboration and code-quality workflow
* reliability, scalability, and performance thinking
* AI model evaluation or AI application behaviour
* clear communication with product, frontend, data, or technical stakeholders

## Whole-Chapter Rule

Use whole chapters as references.

Do not use disconnected extracts from different parts of a book without recording the chapter context.

Every CS-supported lab must include a reference table that names:

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
6. Official documentation for FastAPI, PostgreSQL, Docker, GitHub Actions, and Supabase where useful

## Preserved CS Outcomes

The original CS outcomes remain preserved:

| Outcome | CS topic | AI-track use |
| --- | --- | --- |
| 01 | Python backend foundations | AI service code, helper scripts, clean modules |
| 02 | HTTP, REST, and FastAPI basics | AI application interfaces and small APIs |
| 03 | PostgreSQL-backed API | datasets, evaluation records, metadata, and app state |
| 04 | Service data modelling | users, tickets, services, incidents, prompts, outputs, evaluations |
| 05 | Dockerised backend service | local packaging and repeatable AI app execution |
| 06 | GitHub workflow and CI | tests, checks, documentation, and code quality |
| 07 | Algorithms for operational data | searching, grouping, deduplication, retrieval, ranking |
| 08 | Operating system concepts | processes, memory, files, sockets, services, resources |
| 09 | Performance, latency, and throughput | AI serving, inference latency, bottlenecks, scaling |
| 10 | SLI, SLO, and error budgets | reliability and operational quality of AI workflows |
| 11 | Platform concepts | auth, storage, realtime, APIs, and managed services |
| 12 | Backend/SRE helper app | integrated AI-supporting operational application |

## Planned Chapter Map

The exact chapter titles must be verified against the edition being used before each lab is documented.

| Outcome | Book chapter references to record |
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
| 12 | Select the most relevant whole chapters already used in outcomes 01-11 and record them explicitly |

## Per-Lab Reference Table

Every CS-supported lab must include this table:

| Source | Chapter or documentation section used | Why it was used |
| --- | --- | --- |
| Book or documentation name | Chapter number and title, or exact documentation page | Link to the lab task |

## Required Output

Each CS-supported lab should include:

* lab summary
* target role skill mapping
* target job evidence section
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
