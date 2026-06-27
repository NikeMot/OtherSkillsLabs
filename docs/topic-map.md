# Topic Map

## Track Name

The visible track name is now `Mac and AI`.

The repository still keeps the numbered folders for organisation, but the learning design is no longer six separate headline tracks.

The track has two primary pillars:

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

## 01 — Mac / Apple Administration

The Mac track uses `Apple Device Management` as the primary skeleton. Each lab covers two chapters from that book, supplemented by `macOS Support Essentials`, `Modern Operating Systems`, `The Practice of System and Network Administration`, and the Mac-focused MSP job requirements.

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
* Mac-focused MSP job evidence: customer communication, documentation, escalation, networking, Addigy/Jamf/JumpCloud/Okta awareness, and service improvement

---

## 02 — Computer Science Foundations Thread

Computer Science Foundations remain part of the track.

They are kept through the AI pillar in the same way a real CS and AI course would include algorithms, systems, data structures, maths, operating systems, and performance reasoning.

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

CS should appear inside AI labs through:

* vectors, similarity, indexing, and search
* data structures and complexity
* HTTP, APIs, sockets, files, and processes
* memory, latency, throughput, and scaling
* state machines, queues, control flow, and failure states
* probability, evaluation, risk, and reliability thinking

---

## 03 — Data Engineering and R Thread

Data Engineering remains part of the track as the data foundation for AI.

The Data Engineering track uses `Fundamentals of Data Engineering` as the foundation. The first 11 labs map to one chapter each. Labs 12-23 are drill and deepening labs. Lab 24 is the capstone.

The track is augmented with `Designing Data-Intensive Applications`, `Database Internals`, `Data Engineering Design Patterns`, `Redefining Data Engineering with AI`, and R resources.

Drive resources found in the R folder:

* `R for Data Science`
* `Practical Statistics for Data Scientists`
* `An Introduction to Statistical Learning with R`

R should be used for data analysis, visualisation, statistics, model comparison, and reporting where it strengthens the AI or data engineering work.

Manual-first rule: complete the data engineering or statistical task manually first, then use AI assistance after the method is understood.

Planned data and R outcomes to preserve:

1. Data engineering described — Fundamentals of Data Engineering chapter 1
2. Data engineering lifecycle — Fundamentals of Data Engineering chapter 2
3. Good data architecture — Fundamentals of Data Engineering chapter 3
4. Technology selection for data pipelines — Fundamentals of Data Engineering chapter 4
5. Source systems and operational data — Fundamentals of Data Engineering chapter 5
6. Data storage layouts — Fundamentals of Data Engineering chapter 6
7. Data ingestion pipeline — Fundamentals of Data Engineering chapter 7
8. Query, modelling, and transformation — Fundamentals of Data Engineering chapter 8
9. Serving data for analytics and AI — Fundamentals of Data Engineering chapter 9
10. Data governance, quality, and access — Fundamentals of Data Engineering chapter 10
11. Future of data engineering and AI awareness — Fundamentals of Data Engineering chapter 11
12. SQL and data modelling drill
13. Ingestion drill
14. Transformation and curation drill
15. Data quality validation drill
16. Pipeline testing and automation drill
17. Storage and database internals drill
18. Query performance and cost drill
19. Batch, streaming, and CDC drill
20. Monitoring and incident drill
21. Governance, lineage, and documentation drill
22. Data product and serving layer drill
23. AI augmentation after manual data engineering
24. Junior data engineering capstone

---

## 04 — Multi-Cloud Thread: AWS, Azure, and GCP

AWS, Azure, and GCP are not active standalone headline tracks for now.

They become a cross-cloud implementation layer used throughout the AI track.

For every cloud-relevant concept, the lab should include an AWS / Azure / GCP mapping.

| Capability | AWS | Azure | GCP |
| --- | --- | --- | --- |
| Object storage | S3 | Blob Storage | Cloud Storage |
| Compute or app hosting | EC2, Lambda, ECS | App Service, Functions, Container Apps | Compute Engine, Cloud Run, Cloud Functions |
| Managed relational database | RDS | Azure SQL Database | Cloud SQL |
| Analytics | Redshift, Athena | Synapse, Fabric concepts | BigQuery |
| Secrets | Secrets Manager, Parameter Store | Key Vault | Secret Manager |
| Monitoring | CloudWatch | Azure Monitor, Log Analytics | Cloud Monitoring |
| Identity and access | IAM | Entra ID, Azure RBAC | IAM |
| AI platform | Bedrock, SageMaker | Azure AI Foundry, Azure Machine Learning | Vertex AI |

The learner may practise hands-on with one cloud at a time, but the documentation should show how the same concept maps across all three.

---

## 06 — AI Engineering Pillar

The AI track uses `AI Engineering` as the backbone. One `AI Engineering` chapter should produce two labs. The course has 30 labs total, assuming 15 backbone chapters.

The track is augmented with `Hands-On Large Language Models`, `Prompt Engineering for LLMs`, `An Introduction to Statistical Learning with Python`, `An Introduction to Statistical Learning with R`, `Practical Statistics for Data Scientists`, `R for Data Science`, `AI Systems Performance Engineering`, `Observability Engineering`, `Redefining Data Engineering with AI`, and `AI Agents: The Definitive Guide`.

The junior AI engineer job description shapes every lab through target job evidence.

Planned lab themes:

1. AI engineering foundations part 1
2. AI engineering foundations part 2
3. Python and R data preparation for AI part 1
4. Python and R data preparation for AI part 2
5. First ML model part 1
6. First ML model part 2
7. Model evaluation part 1
8. Model evaluation part 2
9. LLM foundations part 1
10. LLM foundations part 2
11. Prompt engineering part 1
12. Prompt engineering part 2
13. Embeddings and semantic search part 1
14. Embeddings and semantic search part 2
15. RAG workflow part 1
16. RAG workflow part 2
17. AI agents part 1
18. AI agents part 2
19. AI application integration part 1
20. AI application integration part 2
21. AI systems performance part 1
22. AI systems performance part 2
23. AI observability part 1
24. AI observability part 2
25. AI safety and governance part 1
26. AI safety and governance part 2
27. AI for data and operations part 1
28. AI for data and operations part 2
29. Junior AI engineer capstone part 1
30. Junior AI engineer capstone part 2

Every AI lab must include:

* target job evidence
* AI Engineering chapter reference
* supporting reference notes
* coverage ledger update
* CS foundation note where relevant
* data engineering note where relevant
* R note where relevant
* AWS / Azure / GCP mapping where relevant
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
06-ai/lab-01-ai-engineering-foundations-part-1/
```

## Completion Standard

A lab is complete only when it includes:

* technical evidence
* reasoning and decisions
* communication output
* career leverage output
* production considerations
* reflection questions
