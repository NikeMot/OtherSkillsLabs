# AI Curriculum Standard

## Purpose

This document defines how the AI labs should be designed and documented.

The track targets junior AI engineer, AI-enabled backend, and AI-enabled SRE or operations roles. The evidence should show Python, data preparation, model evaluation, LLM application design, retrieval workflows, prompt engineering, agent awareness, deployment thinking, monitoring, responsible use, and clear communication.

## Target Job Rule

The junior AI engineer job description must shape every lab.

Every lab must include a `Target job evidence` section showing how the lab maps to at least one requirement from the target role.

The target job requirements are:

* Python for AI and ML workflows
* NumPy, Pandas, and data preparation
* data cleaning and feature engineering
* model building and model evaluation
* scikit-learn, TensorFlow, or PyTorch awareness
* NLP, retrieval, recommendation, or computer-vision awareness where relevant
* deployment and integration into real applications
* Git and modern development practice
* cloud or platform awareness
* communication with engineers, data scientists, product teams, and stakeholders
* safe, responsible, and well-evaluated AI behaviour

## Core Rule

`AI Engineering` is the backbone for this track.

Use one `AI Engineering` chapter across two labs.

The course has 30 labs total. This assumes 15 backbone chapters from `AI Engineering`.

If the available edition has a different chapter count, preserve the rule: one backbone chapter should produce two labs, and the remaining labs should be used for capstone, review, or missing coverage.

## Source Stack

Primary backbone:

1. `AI Engineering`

Supporting sources:

2. `Hands-On Large Language Models` — LLM concepts, embeddings, retrieval, transformers, RAG, and practical LLM workflows
3. `Prompt Engineering for LLMs` — prompt design, structured outputs, prompt evaluation, and LLM application control
4. `An Introduction to Statistical Learning with Python` — classical ML, supervised learning, model evaluation, overfitting, validation, and feature engineering
5. `AI Systems Performance Engineering` — performance, inference cost, scaling, deployment constraints, and operational behaviour
6. `Observability Engineering` — AI observability, evaluation, monitoring, production signals, and operational visibility
7. `Redefining Data Engineering with AI` — AI-assisted data workflows, human-in-the-loop oversight, governance, and data product thinking
8. `AI Agents: The Definitive Guide` — agent design, tools, planning, memory, orchestration, safety, and evaluation; verify file availability before lab documentation

## Whole-Chapter and Coverage Rule

Use whole chapters as references.

Every lab must record:

* the `AI Engineering` chapter used
* the supporting chapter or major section from each additional source, where relevant
* why each source was used
* how the source shaped the task

The aim is to cover all relevant content from the chosen books across the full 30-lab course.

Maintain a coverage ledger so every chapter or major section from the chosen books is assigned to at least one lab.

The coverage ledger should track:

| Source | Chapter or major section | Covered in lab | Coverage status | Notes |
| --- | --- | --- | --- | --- |
| Book name | Chapter number and title | Lab number | planned / completed / needs review | How it was used |

No copied book text should be committed to the repository.

## Planned 30-Lab Sequence

| Lab | Folder name | Backbone | Main evidence |
| --- | --- | --- | --- |
| 01 | `lab-01-ai-engineering-foundations-part-1/` | AI Engineering chapter 1 | AI engineering role map, use-case selection, risks, and target job evidence |
| 02 | `lab-02-ai-engineering-foundations-part-2/` | AI Engineering chapter 1 | Small AI workflow design with evaluation criteria |
| 03 | `lab-03-python-data-preparation-for-ai-part-1/` | AI Engineering chapter 2 | Python, NumPy, Pandas, and data preparation evidence |
| 04 | `lab-04-python-data-preparation-for-ai-part-2/` | AI Engineering chapter 2 | Cleaned dataset, features, assumptions, and validation notes |
| 05 | `lab-05-first-ml-model-part-1/` | AI Engineering chapter 3 | Baseline supervised model and manual evaluation |
| 06 | `lab-06-first-ml-model-part-2/` | AI Engineering chapter 3 | Error analysis, feature iteration, and model limitations |
| 07 | `lab-07-model-evaluation-part-1/` | AI Engineering chapter 4 | Train/test split, metrics, baseline comparison, and evaluation notes |
| 08 | `lab-08-model-evaluation-part-2/` | AI Engineering chapter 4 | Overfitting, validation, scoring, and decision threshold notes |
| 09 | `lab-09-llm-foundations-part-1/` | AI Engineering chapter 5 | LLM concept notes and safe usage boundaries |
| 10 | `lab-10-llm-foundations-part-2/` | AI Engineering chapter 5 | LLM-based support workflow with expected and actual outputs |
| 11 | `lab-11-prompt-engineering-part-1/` | AI Engineering chapter 6 | Prompt design, task framing, and structured input/output examples |
| 12 | `lab-12-prompt-engineering-part-2/` | AI Engineering chapter 6 | Prompt evaluation, failure cases, and improvement loop |
| 13 | `lab-13-embeddings-and-semantic-search-part-1/` | AI Engineering chapter 7 | Embedding concept lab and semantic search over safe sample text |
| 14 | `lab-14-embeddings-and-semantic-search-part-2/` | AI Engineering chapter 7 | Retrieval quality checks and search failure analysis |
| 15 | `lab-15-rag-workflow-part-1/` | AI Engineering chapter 8 | RAG design over runbooks or lab notes |
| 16 | `lab-16-rag-workflow-part-2/` | AI Engineering chapter 8 | RAG evaluation, citation checking, and hallucination controls |
| 17 | `lab-17-ai-agents-part-1/` | AI Engineering chapter 9 | Agent concept, tool-use design, task boundaries, and control points |
| 18 | `lab-18-ai-agents-part-2/` | AI Engineering chapter 9 | Agent workflow simulation, failure modes, and human approval points |
| 19 | `lab-19-ai-application-integration-part-1/` | AI Engineering chapter 10 | FastAPI or script-based AI integration plan |
| 20 | `lab-20-ai-application-integration-part-2/` | AI Engineering chapter 10 | Small AI-assisted application or service with documented interface |
| 21 | `lab-21-ai-systems-performance-part-1/` | AI Engineering chapter 11 | Latency, cost, throughput, and scaling assumptions |
| 22 | `lab-22-ai-systems-performance-part-2/` | AI Engineering chapter 11 | Performance test notes and optimisation trade-offs |
| 23 | `lab-23-ai-observability-part-1/` | AI Engineering chapter 12 | Evaluation dataset, logging plan, and monitoring signals |
| 24 | `lab-24-ai-observability-part-2/` | AI Engineering chapter 12 | AI output monitoring, failure review, and operational dashboard notes |
| 25 | `lab-25-ai-safety-and-governance-part-1/` | AI Engineering chapter 13 | Risk register, data handling notes, and safe-use policy |
| 26 | `lab-26-ai-safety-and-governance-part-2/` | AI Engineering chapter 13 | Human-in-the-loop workflow and escalation criteria |
| 27 | `lab-27-ai-for-data-and-operations-part-1/` | AI Engineering chapter 14 | AI-assisted data or operations workflow after manual baseline |
| 28 | `lab-28-ai-for-data-and-operations-part-2/` | AI Engineering chapter 14 | Evaluation of AI assistance, limitations, and productivity notes |
| 29 | `lab-29-junior-ai-engineer-capstone-part-1/` | AI Engineering chapter 15 | Capstone design, dataset, evaluation plan, and architecture |
| 30 | `lab-30-junior-ai-engineer-capstone-part-2/` | AI Engineering chapter 15 | Working AI application, tests, monitoring notes, limitations, and interview evidence |

## Supporting Source Placement

Use the supporting sources across the course as follows:

| Supporting source | Main placement |
| --- | --- |
| `An Introduction to Statistical Learning with Python` | Labs 03-08 for ML foundations, features, baselines, validation, metrics, and error analysis |
| `Hands-On Large Language Models` | Labs 09-16 for LLM concepts, embeddings, semantic search, and RAG |
| `Prompt Engineering for LLMs` | Labs 11-12 and revisited in Labs 15-18 for prompts, structured outputs, and evaluation |
| `AI Agents: The Definitive Guide` | Labs 17-18 and revisited in the capstone for agentic workflows, tool use, control, memory, and safety |
| `AI Systems Performance Engineering` | Labs 21-22 and capstone performance notes |
| `Observability Engineering` | Labs 23-24 and capstone monitoring notes |
| `Redefining Data Engineering with AI` | Labs 27-28 for manual-first AI-assisted data and operations workflows |

## Manual-First Rule

Where a lab involves data preparation, model building, evaluation, retrieval, or operations workflow design, complete the manual baseline first.

AI tools may be used afterwards to assist with:

* review
* documentation
* test case generation
* comparison of approaches
* evaluation checklist creation
* explanation
* improvement ideas

AI assistance must not replace understanding, verification, or manual reasoning.

## Per-Lab Required Sections

Each completed AI lab should include:

* lab summary
* target job evidence
* `AI Engineering` chapter used
* supporting reference table
* coverage ledger update
* manual baseline where relevant
* AI-assisted follow-up where relevant
* files created or changed
* commands, scripts, notebooks, or application steps used
* test inputs and expected outputs
* actual outputs and evaluation result
* failure modes and limitations
* safety and data handling note
* production improvement note
* stakeholder-facing summary
* recruiter-facing summary
* seven reflection answers

## Evidence Rules

Use fictional, generated, personal, or safely sanitised data only.

Do not commit copied book text, live workplace material, private records, credentials, or sensitive screenshots.
