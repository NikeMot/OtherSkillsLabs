# Topic Map

## Track Name

The visible track name is `Mac and AI`.

The repository keeps the numbered folders for organisation, but the learning design has two primary pillars:

```text
01-mac-apple-administration/  -> primary Mac pillar
06-ai/                        -> primary AI pillar
```

The remaining topic folders are embedded support threads:

```text
02-computer-science-foundations/ -> CS foundation thread for AI
03-data-engineering/             -> data engineering and R thread for AI
04-aws/                          -> AWS cross-cloud thread
05-gcp/                          -> GCP cross-cloud thread
Azure                            -> cross-cloud thread documented inside labs and docs
```

Every lab also includes thinking, social skill, branding, interview technique, and personal development outputs.

---

## Preservation Rule

Changing the track name to `Mac and AI` must not reduce the learning scope.

The learner should still cover the intended outcomes from Mac administration, computer science, data engineering, R, AWS, Azure, GCP, AI engineering, and SRE or operations-style evidence.

The difference is organisation: CS, data engineering, R, and cloud now support the AI pillar instead of sitting as competing headline tracks.

---

## Official Online Documentation Rule

Every lab must follow `docs/official-online-documentation-standard.md`.

Each lab must include an `Official online documentation checked` section so implementation details stay current.

This applies to both Mac labs and AI labs.

---

## AI Cumulative Build Rule

This rule applies only to the AI section.

Every AI lab must build on previous AI labs.

The AI section should become one growing `AI Operations and Data Assistant` or equivalent cumulative project. Each AI lab should add a new capability, reuse existing artefacts, and include a regression check where relevant.

Mac labs remain separate and do not need to build into the AI project.

---

## AI Cross-Cutting Requirements

The AI section must also follow `docs/ai-cross-cutting-requirements.md`.

These requirements are embedded into the existing 48 AI labs and do not increase the lab count.

Every AI lab should include relevant evidence for:

* software engineering discipline
* MLOps / LLMOps
* AI security
* evaluation-first practice
* workflow orchestration
* data and model governance
* minimal product or interface layer

---

## 01 — Mac / Apple Administration

The Mac track uses `Apple Device Management` as the primary skeleton. Each lab covers two chapters from that book, supplemented by `macOS Support Essentials`, `Modern Operating Systems`, `The Practice of System and Network Administration`, official Apple online documentation, and the Mac-focused MSP job requirements.

Planned lab themes:

1. Apple device management foundations — Apple Device Management chapters 1-2
2. macOS support and identity basics — Apple Device Management chapters 3-4
3. Device enrolment and MDM workflow — Apple Device Management chapters 5-6
4. Configuration profiles and policy control — Apple Device Management chapters 7-8
5. FileVault, Gatekeeper, certificates, and device-protection support — Apple Device Management chapters 9-10
6. Jamf, Addigy, JumpCloud, and Okta concepts — Apple Device Management chapters 11-12
7. App deployment and software update support — Apple Device Management chapters 13-14
8. macOS network and connectivity troubleshooting — Apple Device Management chapters 15-16
9. Logs, monitoring, and escalation evidence — Apple Device Management chapters 17-18
10. Documentation, service improvement, and SOPs — Apple Device Management chapters 19-20
11. MSP client support scenario — Apple Device Management chapters 21-22
12. Mac Support Specialist capstone — Apple Device Management chapters 23-24 or final capstone coverage

Every Mac lab must include:

* Apple Device Management chapter-pair notes
* macOS Support Essentials troubleshooting supplement
* Modern Operating Systems depth note
* system and network administration execution note
* official Apple documentation check
* Mac-focused MSP job evidence: customer communication, documentation, escalation, networking, Addigy/Jamf/JumpCloud/Okta awareness, and service improvement

---

## 02 — Computer Science Foundations Thread

Computer Science Foundations remain part of the AI pillar.

They are kept through the AI labs in the same way a real CS and AI course would include algorithms, systems, data structures, maths, operating systems, and performance reasoning.

Planned CS outcomes to preserve:

1. SRE maths and reliability basics
2. Percentiles, averages, distributions, and outliers
3. Latency, throughput, error rate, and saturation
4. SLO, SLI, SLA, and error budget calculations
5. Queueing and capacity intuition
6. Big O and operational performance intuition
7. Data structures for logs, events, and alerts
8. Algorithms for searching, grouping, and deduplication
9. Operating system concepts for SRE and AI services
10. Networking and distributed systems basics
11. Probability and risk for incidents and model behaviour
12. Explaining technical trade-offs clearly

---

## 03 — Data Engineering and R Thread

Data Engineering remains part of the track as the data foundation for AI.

Data engineering should come before serious AI work because useful AI systems depend on datasets, pipelines, quality checks, storage, metadata, evaluation records, and serving layers.

Drive resources found in the R folder:

* `R for Data Science`
* `Practical Statistics for Data Scientists`
* `An Introduction to Statistical Learning with R`

R should be used for data analysis, visualisation, statistics, model comparison, and reporting where it strengthens the AI or data engineering work.

Manual-first rule: complete the data engineering or statistical task manually first, then use AI assistance after the method is understood.

---

## 04 — Multi-Cloud Thread: Local, Azure, AWS, and GCP

Every major concept should be learned locally first.

Cloud-relevant concepts should then be mapped across Azure, AWS, and GCP.

The expected learning pattern is:

```text
1. local implementation
2. Azure mapping or implementation
3. AWS mapping or implementation
4. GCP mapping or implementation
```

The learner may practise hands-on with one cloud at a time, but documentation should show how the same concept maps across all three.

| Capability | Local | Azure | AWS | GCP |
| --- | --- | --- | --- | --- |
| Object storage | filesystem / MinIO | Blob Storage | S3 | Cloud Storage |
| App hosting | local FastAPI / Docker | App Service, Functions, Container Apps | Lambda, ECS, EC2 | Cloud Run, Cloud Functions, Compute Engine |
| Managed relational database | SQLite / PostgreSQL | Azure SQL Database | RDS | Cloud SQL |
| Analytics | DuckDB / PostgreSQL | Synapse, Fabric concepts | Athena, Redshift | BigQuery |
| Secrets | local env pattern, never committed | Key Vault | Secrets Manager, Parameter Store | Secret Manager |
| Monitoring | local logs and metrics | Azure Monitor, Log Analytics | CloudWatch | Cloud Monitoring |
| Identity and access | local users / app config | Entra ID, Azure RBAC | IAM | IAM |
| AI platform | local model/API workflow | Azure AI Foundry, Azure ML | Bedrock, SageMaker | Vertex AI / Gemini Enterprise Agent Platform |

---

## 06 — AI Engineering Pillar

The AI pillar is a cumulative 48-lab course.

Related topics are grouped together for learning. The path starts with CS, then data engineering and R, then ML, then LLMs/RAG/agents, then production deployment across local, Azure, AWS, and GCP.

Planned lab themes:

1. Local development environment
2. CS introduction for AI
3. Algorithms for data and AI
4. HTTP, REST, and FastAPI basics
5. SQL and PostgreSQL foundations
6. Cloud foundations across Azure, AWS, and GCP
7. Data engineering lifecycle and source systems
8. Local data ingestion from CSV, JSON, or API
9. Storage design: files, tables, object storage
10. SQL transformation and modelling
11. R data wrangling and visualisation
12. Python and R dataset comparison
13. Data quality checks and validation
14. Pipeline testing and repeatable execution
15. Metadata, lineage, and documentation
16. Monitoring and incident handling for pipelines
17. Data product and serving layer design
18. Data engineering review across local, Azure, AWS, and GCP
19. EDA in Python and R
20. Practical statistics for AI datasets
21. First supervised ML model
22. Feature engineering
23. Train/test validation and metrics
24. Classification and regression comparison
25. Error analysis and model limitations
26. Model evaluation report in Python and R
27. Local model serving with FastAPI
28. ML workflow mapping across Azure ML, SageMaker, and Vertex AI / Gemini Enterprise Agent Platform
29. LLM foundations and safe usage
30. Prompt engineering and structured outputs
31. Prompt evaluation and failure cases
32. Embeddings and semantic search
33. Retrieval index design
34. RAG over runbooks, tickets, or lab notes
35. RAG evaluation, citations, and hallucination checks
36. AI agents: planning, tools, memory, and state
37. Agent workflow simulation with human approval
38. Agent safety, failure modes, and escalation
39. Local AI application end to end
40. Deploy AI app on Azure
41. Deploy AI app on AWS
42. Deploy AI app on GCP
43. Secrets, identity, and access control cross-cloud
44. Monitoring and observability cross-cloud
45. Performance, latency, throughput, and cost cross-cloud
46. AI governance, data handling, and incident response
47. Capstone design: architecture, data, cloud, risk, evaluation
48. Capstone build: demo, monitoring, and interview story

Every AI lab must include:

* target job evidence
* cumulative build dependency
* new capability added
* previous artefacts reused
* integration point with the growing project
* regression check where relevant
* source chapter or section used
* supporting reference notes
* official online documentation checked
* coverage ledger update
* CS foundation note where relevant
* data engineering note where relevant
* R note where relevant
* local implementation evidence where relevant
* Azure / AWS / GCP mapping or implementation evidence where relevant
* cross-cutting requirements checklist where relevant
* manual baseline where relevant
* AI-assisted follow-up where relevant
* test inputs and expected outputs
* actual outputs and evaluation result
* failure modes and limitations
* safety and data handling note
* stakeholder-facing summary
* recruiter-facing summary

---

## Naming Convention

Use lowercase, hyphenated folder names.

Examples:

```text
01-mac-apple-administration/lab-01-apple-device-management-foundations/
06-ai/lab-01-local-development-environment/
```

## Completion Standard

A lab is complete only when it includes:

* technical evidence
* reasoning and decisions
* communication output
* career leverage output
* production considerations
* official online documentation checked
* reflection questions
