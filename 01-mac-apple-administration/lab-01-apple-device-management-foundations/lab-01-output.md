# Mac Lab 01 — Apple Device Management Foundations

## Lab Summary

**Estimated time:** 60 minutes  
**Topic area:** macOS support, Apple device management concepts, baseline evidence  
**Status:** Not started / In progress / Completed

### Objective

Create a basic Mac support baseline and understand where the device would sit in a real corporate Apple management workflow.

This is a one-hour lab. The goal is not to document everything on the Mac. The goal is to learn the basic support story:

> A Mac arrives at a company or MSP. Before anyone changes it, signs into it, enrols it, or gives it to a user, support needs to understand its current local state.

---

## Scenario

You are a junior Mac Support Specialist at a Mac-focused MSP.

A client has supplied a Mac for review. A senior engineer asks for a quick first-pass baseline before any Apple Account, iCloud, Apple Business Manager, App Store, or MDM work is attempted.

Manager requirement:

> Check the Mac safely. Confirm its local state, whether it appears managed, and what security signals are visible. Do not sign into Apple services. Do not make changes. Record enough in your manual notes that a senior engineer would understand the device's starting point.

---

## Corporate Context

In a real company, this Mac could later go through:

```text
Asset record -> Apple Business Manager -> Automated Device Enrolment -> MDM -> configuration profiles -> security baseline -> user handover
```

In this lab, Apple Account, Apple Business Manager, and live MDM access are unavailable, so those parts are conceptual.

The hands-on part is local inspection only.

---

## Requirements

| ID | Requirement | Status |
| --- | --- | --- |
| R1 | Do not use Apple Account, iCloud, ABM, App Store, or live MDM | Not started |
| R2 | Capture macOS version and local user context | Not started |
| R3 | Check whether the Mac appears MDM-enrolled or has configuration profiles | Not started |
| R4 | Capture FileVault, Gatekeeper, and basic network identity | Not started |
| R5 | Write a short corporate support note in manual notes | Not started |
| R6 | Complete an official Apple documentation check | Not started |

---

## Constraints

Do not:

* sign into Apple Account or iCloud
* use Apple Business Manager or Managed Apple Accounts
* enrol the Mac into MDM
* remove management profiles
* change FileVault, Gatekeeper, updates, or security settings
* expose serial numbers, Apple Account details, iCloud details, or private data

If the Mac appears already managed, stop and record that in manual notes.

---

## One-Hour Plan

| Time | Work |
| --- | --- |
| 5 min | Read scenario and constraints |
| 10 min | Skim official Apple documentation links |
| 30 min | Run local inspection checks |
| 10 min | Write manual support notes |
| 5 min | Complete reflection questions |

---

## Official Online Documentation Checked

Use this table in manual notes.

| Source | URL | Date checked | Lab decision affected | Notes |
| --- | --- | --- | --- | --- |
| Apple Platform Deployment | https://support.apple.com/guide/deployment/welcome/web | YYYY-MM-DD | Confirms Apple deployment and management concepts | Conceptual only |
| Apple Business Manager User Guide | https://support.apple.com/guide/apple-business-manager/welcome/web | YYYY-MM-DD | Confirms ABM is organisational, not personal | No ABM access |
| Mac User Guide | https://support.apple.com/guide/mac-help/welcome/mac | YYYY-MM-DD | Confirms local Mac support areas | No Apple Account sign-in |
| Apple Device Management documentation | https://developer.apple.com/documentation/devicemanagement | YYYY-MM-DD | Confirms profile and payload concept area | Documentation review only |

---

## Tasks

### Task 1 — Create a Local Evidence Folder

Purpose: keep lab evidence separate from personal files.

```bash
mkdir -p ~/Desktop/mac-lab-01/evidence
cd ~/Desktop/mac-lab-01
```

Manual note: explain why support evidence should be organised before troubleshooting begins.

---

### Task 2 — Capture Basic System and User Context

Purpose: identify the Mac's local software state and the current local user context.

```bash
sw_vers | tee evidence/macos-version.txt
whoami | tee evidence/current-user.txt
id | tee evidence/current-user-id.txt
```

Manual note: explain the difference between a local macOS account, an Apple Account, and a Managed Apple Account.

---

### Task 3 — Check Management State

Purpose: avoid changing a Mac that may already be controlled by an organisation.

```bash
profiles status -type enrollment | tee evidence/mdm-enrollment-status.txt
system_profiler SPConfigurationProfileDataType | tee evidence/configuration-profiles.txt
```

Manual note: explain why a support engineer should check MDM enrolment and configuration profiles before making changes.

---

### Task 4 — Check Security and Network Signals

Purpose: capture quick support signals without changing anything.

```bash
fdesetup status | tee evidence/filevault-status.txt
spctl --status | tee evidence/gatekeeper-status.txt
scutil --get ComputerName | tee evidence/computer-name.txt
networksetup -listallhardwareports | tee evidence/network-hardware-ports.txt
```

Manual note: explain why FileVault, Gatekeeper, and network identity matter in corporate Mac support.

---

### Task 5 — Write the Corporate Support Note

In manual notes, write 5-8 lines answering:

```text
What did I check?
What did I avoid changing?
Does the Mac appear managed?
What would happen next in a real MSP or corporate environment?
What would I escalate to a senior engineer?
```

Use this short structure:

| Field | Note |
| --- | --- |
| Device starting point | |
| Checks completed | |
| Management status | |
| Security signals | |
| Apple Account / ABM / MDM limitation | |
| Suggested next step | |

---

## Verification Checklist

| Check | Result |
| --- | --- |
| Apple Account and iCloud were not used | Pass / Fail |
| macOS version captured | Pass / Fail |
| Local user context captured | Pass / Fail |
| MDM enrolment status checked | Pass / Fail |
| Configuration profile status checked | Pass / Fail |
| FileVault status checked | Pass / Fail |
| Gatekeeper status checked | Pass / Fail |
| Network identity checked | Pass / Fail |
| Official documentation checked | Pass / Fail |
| Corporate support note written in manual notes | Pass / Fail |

---

## Production Relevance

This lab matters because a support engineer should not begin by changing settings. In a real company, a Mac may already be owned, enrolled, restricted, or protected. A quick baseline helps avoid breaking management, exposing personal data, or removing security controls without approval.

The main professional habit is:

```text
inspect first -> document state -> understand management status -> escalate or act safely
```

---

## Completion Checklist

* [ ] I completed the checks in about one hour
* [ ] I did not use Apple Account or iCloud
* [ ] I did not change security or management settings
* [ ] I recorded manual notes privately
* [ ] I answered the reflection questions privately

---

## Reflection Questions

Answer these in manual notes.

1. What problem does a Mac baseline solve in a real MSP or corporate environment?
2. What is the difference between a local macOS account, an Apple Account, and a Managed Apple Account?
3. Why should MDM enrolment and configuration profiles be checked before making changes?
4. Why did this lab avoid Apple Account, iCloud, ABM, and live MDM?
5. Which check was most useful for understanding the Mac's support state?
6. What would be different in a real company with ABM and MDM access?
7. How would I explain this lab to a hiring manager?
