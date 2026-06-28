# Mac / Apple Lab Curriculum Standard

## Purpose

This document defines how the Mac / Apple Administration labs should be designed and completed.

The track targets a Mac Support Specialist role in a Mac-focused MSP environment. The labs should therefore produce evidence of practical support ability, customer communication, troubleshooting discipline, escalation quality, Apple device management awareness, identity platform awareness, and networking fundamentals.

## Source Priority

Use the following source hierarchy:

1. `Apple Device Management` — primary lab skeleton
2. `macOS Support Essentials` — practical support and troubleshooting supplement
3. official Apple online documentation — current vendor-supported behaviour
4. `Modern Operating Systems` — deeper operating-system understanding
5. `The Practice of System and Network Administration` — execution standard for operational work
6. Target Mac Support Specialist job requirements — role-specific evidence requirements

## Apple Device Management Rule

Each lab should cover two chapters from `Apple Device Management`.

```text
Lab 01 -> chapters 1-2
Lab 02 -> chapters 3-4
Lab 03 -> chapters 5-6
Lab 04 -> chapters 7-8
Lab 05 -> chapters 9-10
Lab 06 -> chapters 11-12
Lab 07 -> chapters 13-14
Lab 08 -> chapters 15-16
Lab 09 -> chapters 17-18
Lab 10 -> chapters 19-20
Lab 11 -> chapters 21-22
Lab 12 -> chapters 23-24 or final capstone coverage
```

If the edition being used has a different chapter count, keep the same rule: two chapters per lab until the book is complete. Any remaining lab time should become capstone, troubleshooting, or MSP-style scenario work.

## Apple Account Constraint

The learner is currently unable to use an Apple Account for lab work.

Do not design Mac labs that require signing in with a personal Apple Account.

Any lab task that would require Apple Account sign-in, iCloud, Find My, App Store purchasing, Apple Business Manager access, Managed Apple Accounts, automated device enrolment, or live MDM tenant enrolment must be handled as conceptual or documentation-based work only.

For those topics, acceptable evidence includes:

* official documentation review
* architecture or workflow diagram
* support scenario write-up
* decision record
* risk note
* escalation note
* comparison of Jamf, Addigy, JumpCloud, Okta, Apple Business Manager, and MDM concepts
* simulated ticket or customer-support explanation

Hands-on Mac labs should prioritise local macOS account work, safe local settings, command-line checks, logs, networking diagnostics, filesystem inspection, configuration-profile analysis, and documentation.

## Required Supplement Structure

Every Mac lab should contain these six layers:

### 1. Apple Device Management skeleton

Use the two assigned chapters to decide the technical theme of the lab.

### 2. macOS Support Essentials supplement

Add practical support content:

* user-facing troubleshooting
* macOS settings and support workflow
* local account or access checks
* app, update, network, profile, or certificate troubleshooting where relevant
* support technician explanation

### 3. Official Apple documentation check

Add an `Official online documentation checked` section using `docs/official-online-documentation-standard.md`.

Use official Apple documentation to verify current platform behaviour, especially for deployment, MDM, Apple Business Manager, macOS support, device management payloads, security settings, software updates, certificates, identity integration, and enrolment behaviour.

### 4. Modern Operating Systems depth note

Add one short operating-system depth note.

Examples:

* process behaviour
* memory and resource use
* filesystems and permissions
* I/O and storage
* networking stack concepts
* isolation and access boundaries
* OS service behaviour

The depth note should be practical, not academic. It should explain why the underlying OS concept matters when troubleshooting a Mac support issue.

### 5. System and network administration execution note

Every lab should show professional execution discipline:

* define the user impact
* gather evidence before changing anything
* document the current state
* make one controlled change at a time
* verify the result
* record the fix or next action
* escalate with useful evidence if needed
* produce a reusable note, SOP, or service improvement suggestion

### 6. Mac-focused MSP job overlay

Every lab should map back to the target role.

Include evidence for at least two of:

* customer communication
* incident documentation
* escalation note
* networking fundamentals
* Addigy awareness
* Jamf awareness
* JumpCloud awareness
* Okta awareness
* Apple Business Manager or MDM awareness, conceptual if hands-on access is unavailable
* service improvement

## Planned Lab Sequence

| Lab | Folder name | Skeleton | Job-facing purpose |
| --- | --- | --- | --- |
| 01 | `lab-01-apple-device-management-foundations/` | Apple Device Management chapters 1-2 | Establish Apple admin concepts and MSP support workflow |
| 02 | `lab-02-macos-support-and-identity-basics/` | Apple Device Management chapters 3-4 | Practise macOS support basics and identity/access thinking |
| 03 | `lab-03-device-enrolment-and-mdm-workflow/` | Apple Device Management chapters 5-6 | Understand enrolment and managed-device workflow conceptually unless live access is available |
| 04 | `lab-04-configuration-profiles-and-policy-control/` | Apple Device Management chapters 7-8 | Explain profiles, settings, restrictions, and policy evidence |
| 05 | `lab-05-filevault-gatekeeper-and-certificate-support/` | Apple Device Management chapters 9-10 | Troubleshoot device protection, app trust, and certificate-style issues |
| 06 | `lab-06-jamf-addigy-jumpcloud-okta-concepts/` | Apple Device Management chapters 11-12 | Map MDM and identity concepts to tools named in the job advert |
| 07 | `lab-07-app-deployment-and-software-update-support/` | Apple Device Management chapters 13-14 | Practise app deployment and update support thinking, conceptual where Apple service access is required |
| 08 | `lab-08-macos-network-and-connectivity-troubleshooting/` | Apple Device Management chapters 15-16 | Apply DNS, Wi-Fi, VPN, proxy, and connectivity troubleshooting |
| 09 | `lab-09-logs-monitoring-and-escalation-evidence/` | Apple Device Management chapters 17-18 | Build evidence suitable for senior-engineer escalation |
| 10 | `lab-10-documentation-service-improvement-and-sops/` | Apple Device Management chapters 19-20 | Produce process documentation and service improvement outputs |
| 11 | `lab-11-msp-client-support-scenario/` | Apple Device Management chapters 21-22 | Simulate a multi-client MSP support scenario |
| 12 | `lab-12-mac-support-specialist-capstone/` | Apple Device Management chapters 23-24 or final coverage | Build a complete Mac Support Specialist evidence pack |

## Standard Lab Output

Each completed Mac lab should include:

* lab summary
* Apple Device Management chapter pair used
* macOS Support Essentials supplement
* official online documentation checked
* Modern Operating Systems depth note
* system and network administration execution note
* Apple Account constraint note where relevant
* job-specific evidence produced
* commands, checks, or documented workflow
* support ticket summary
* customer update
* escalation note if relevant
* service improvement note if relevant
* seven reflection answers

## Evidence Rules

Do not commit:

* serial numbers
* real user names
* asset tags
* customer data
* company data
* screenshots containing private account information
* live configuration exports
* Apple Account details
* iCloud details
* credentials or secrets
* copyrighted book content

Use fictional, personal, conceptual, documentation-based, or safely sanitised data only.
