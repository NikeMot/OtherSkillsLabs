# Topic Map

## Technical Topics

This repository has six technical topic areas:

```text
01-mac-apple-administration/
02-computer-science-foundations/
03-data-engineering/
04-aws/
05-gcp/
06-ai/
```

Every lab also includes thinking, social skill, branding, interview technique, and personal development outputs.

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

## 02 — Computer Science Foundations

Planned lab themes:

1. SRE maths and reliability basics
2. Percentiles, averages, distributions, and outliers
3. Latency, throughput, error rate, and saturation
4. SLO, SLI, SLA, and error budget calculations
5. Queueing and capacity intuition
6. Big O and operational performance intuition
7. Data structures for logs, events, and alerts
8. Algorithms for searching, grouping, and deduplication
9. Operating system concepts for SRE
10. Networking and distributed systems basics
11. Probability and risk for incidents
12. Explaining technical trade-offs clearly

---

## 03 — Data Engineering

The Data Engineering track uses `Fundamentals of Data Engineering` as the foundation. The first 11 labs map to one chapter each. Labs 12-23 are drill and deepening labs. Lab 24 is the capstone.

The track is augmented with `Designing Data-Intensive Applications`, `Database Internals`, `Data Engineering Design Patterns`, and `Redefining Data Engineering with AI`.

Manual-first rule: complete the data engineering task manually first, then use the AI-focused source to learn how AI can assist after the manual method is understood.

The junior data engineering job description shapes every lab through target job evidence.

Planned lab themes:

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

Every Data Engineering lab must include:

* target job evidence
* whole-chapter reference notes
* coverage ledger update
* manual workflow
* augmentation reference notes
* AI-assisted follow-up only after the manual workflow
* data quality or verification evidence
* stakeholder-facing summary
* recruiter-facing summary

---

## 04 — AWS

Planned lab themes:

1. AWS account and IAM basics
2. VPC, subnets, route tables, and security groups
3. EC2 operational support workflow
4. S3 storage, lifecycle, and access controls
5. RDS basics and operational considerations
6. CloudWatch metrics, logs, and alarms
7. Route 53 and DNS support scenarios
8. Load balancing and health checks
9. Backup, recovery, and resilience basics
10. Cost monitoring and tagging
11. AWS incident evidence pack
12. AWS SRE mini-project

---

## 05 — Google Cloud Platform

Planned lab themes:

1. GCP project and IAM basics
2. VPC, subnet, firewall, and routing basics
3. Compute Engine operational support workflow
4. Cloud Storage access and lifecycle basics
5. Cloud SQL basics and operational considerations
6. Cloud Monitoring metrics, logs, and alerts
7. Cloud DNS support scenarios
8. Load balancing and health checks
9. Backup, recovery, and resilience basics
10. Cost monitoring and labels
11. GCP incident evidence pack
12. GCP SRE mini-project

---

## 06 — AI

The AI track uses `AI Engineering` as the backbone. One `AI Engineering` chapter should produce two labs. The course has 30 labs total, assuming 15 backbone chapters.

The track is augmented with `Hands-On Large Language Models`, `Prompt Engineering for LLMs`, `An Introduction to Statistical Learning with Python`, `AI Systems Performance Engineering`, `Observability Engineering`, `Redefining Data Engineering with AI`, and `AI Agents: The Definitive Guide`.

The junior AI engineer job description shapes every lab through target job evidence.

Planned lab themes:

1. AI engineering foundations part 1
2. AI engineering foundations part 2
3. Python data preparation for AI part 1
4. Python data preparation for AI part 2
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
02-computer-science-foundations/lab-01-sre-maths-and-reliability-basics/
03-data-engineering/lab-01-data-engineering-described/
04-aws/lab-01-aws-account-and-iam-basics/
05-gcp/lab-01-gcp-project-and-iam-basics/
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
