# Mac Lab 02 — macOS Support and Identity Basics

## Lab Summary

**Estimated time:** 60 minutes  
**Topic area:** macOS local accounts, support triage, identity boundaries  
**Status:** Not started / In progress / Completed

### Objective

Understand how local macOS accounts fit into corporate Mac support and how to inspect account context without using Apple Account, iCloud, Apple Business Manager, or live MDM access.

This is a one-hour lab. The goal is to learn the support story:

> A user cannot complete a task on a Mac. Before changing permissions or escalating, support needs to understand what account context the user is operating in.

---

## Scenario

You are a junior Mac Support Specialist at a Mac-focused MSP.

A user reports that they cannot complete an admin-style action on a Mac. They are unsure whether they are using a local Mac account, an Apple Account, or a company-managed identity.

A senior engineer asks you to inspect the local account context and explain what you can and cannot prove without Apple Account, Apple Business Manager, or MDM access.

Manager requirement:

> Check the current local account context safely. Identify whether the logged-in local account appears to have admin privileges. Explain the difference between local account permissions and corporate identity. Do not create users, reset passwords, change permissions, or sign into Apple services.

---

## Corporate Context

In a real company, Mac identity may involve several layers:

```text
Local macOS account -> Apple Account or Managed Apple Account -> company identity provider -> MDM policy -> app and resource access
```

A user may think they have “one account”, but support needs to separate different identity layers:

* the account used to log into macOS
* the Apple Account used for Apple services
* the Managed Apple Account controlled by an organisation
* the identity provider account used for work apps
* the local admin or standard permissions on the Mac
* the MDM policies that may restrict or grant behaviour

This lab focuses only on the local macOS layer and conceptual identity mapping.

---

## Requirements

| ID | Requirement | Status |
| --- | --- | --- |
| R1 | Do not sign into Apple Account, iCloud, ABM, or MDM | Not started |
| R2 | Identify the current local macOS user | Not started |
| R3 | Check current user ID, groups, and admin membership | Not started |
| R4 | Inspect the local user directory record safely | Not started |
| R5 | Explain the difference between local permissions and corporate identity | Not started |
| R6 | Write a short support triage note in manual notes | Not started |

---

## Constraints

Do not:

* create a new user
* delete a user
* reset a password
* change admin membership
* sign into Apple Account or iCloud
* use Apple Business Manager or MDM
* expose real names, Apple Account details, iCloud details, serial numbers, or private data

This is inspection only.

---

## One-Hour Plan

| Time | Work |
| --- | --- |
| 5 min | Read scenario and constraints |
| 10 min | Skim official Apple documentation |
| 30 min | Run local identity checks |
| 10 min | Write support triage note |
| 5 min | Answer reflection questions privately |

---

## Official Online Documentation Checked

Use this table in manual notes.

| Source | URL | Date checked | Lab decision affected | Notes |
| --- | --- | --- | --- | --- |
| Mac User Guide | https://support.apple.com/guide/mac-help/welcome/mac | YYYY-MM-DD | Confirms user and local Mac support concepts | No Apple Account sign-in |
| Apple Platform Deployment | https://support.apple.com/guide/deployment/welcome/web | YYYY-MM-DD | Confirms corporate identity and account concepts | Conceptual only |
| Apple Business Manager User Guide | https://support.apple.com/guide/apple-business-manager/welcome/web | YYYY-MM-DD | Confirms Managed Apple Account and organisation context | No ABM access |

---

## Tasks

### Task 1 — Create the Lab Evidence Folder

Purpose: keep the identity inspection separate from personal files.

```bash
mkdir -p ~/Desktop/mac-lab-02/evidence
cd ~/Desktop/mac-lab-02
```

Manual note: explain why identity evidence should be handled carefully.

---

### Task 2 — Identify the Current Local User

Purpose: confirm the local macOS account context before assuming anything about Apple services or corporate identity.

```bash
whoami | tee evidence/current-user.txt
id | tee evidence/current-user-id.txt
groups | tee evidence/current-user-groups.txt
```

Manual note: explain what these commands prove and what they do not prove.

---

### Task 3 — Check Admin Membership Safely

Purpose: understand whether the current local account appears to have local admin rights.

```bash
dseditgroup -o checkmember -m "$(whoami)" admin | tee evidence/admin-membership-check.txt
```

Manual note: explain why local admin membership matters when a user cannot install software, change settings, or perform privileged actions.

---

### Task 4 — Inspect the Local Directory Record

Purpose: inspect the local account record without changing it.

```bash
dscl . -read /Users/$(whoami) UniqueID PrimaryGroupID NFSHomeDirectory UserShell | tee evidence/local-user-record.txt
```

Manual note: explain why the home directory, shell, UID, and primary group are local operating-system details, not proof of Apple Account or company identity.

---

### Task 5 — Write the Support Triage Note

In manual notes, write 5-8 lines answering:

```text
What local account is active?
Does the account appear to be a local admin?
What can I prove locally?
What can I not prove without Apple Account, ABM, IdP, or MDM access?
What would I escalate to a senior engineer?
```

Use this short structure:

| Field | Note |
| --- | --- |
| User issue | |
| Local account observed | |
| Admin membership result | |
| Local evidence collected | |
| Identity limits | |
| Suggested next step | |

---

## Verification Checklist

| Check | Result |
| --- | --- |
| Apple Account and iCloud were not used | Pass / Fail |
| Current local user identified | Pass / Fail |
| User ID and groups captured | Pass / Fail |
| Admin membership checked | Pass / Fail |
| Local directory record inspected | Pass / Fail |
| No user or permission changes made | Pass / Fail |
| Official documentation checked | Pass / Fail |
| Support triage note written in manual notes | Pass / Fail |

---

## Production Relevance

This lab matters because user access problems are often misdiagnosed. A user may say “my Apple login is broken” or “I need admin access”, but support must separate local macOS permissions from Apple services, company identity, MDM policy, and application access.

The main professional habit is:

```text
identify the account layer -> inspect before changing -> explain limits -> escalate with useful context
```

---

## Completion Checklist

* [ ] I completed the checks in about one hour
* [ ] I did not use Apple Account or iCloud
* [ ] I did not create, delete, or modify users
* [ ] I did not change permissions or admin membership
* [ ] I recorded manual notes privately
* [ ] I answered the reflection questions privately

---

## Reflection Questions

Answer these in manual notes.

1. What problem does local account inspection solve in Mac support?
2. What is the difference between local admin rights and corporate identity access?
3. Why is an Apple Account not the same as a local macOS account?
4. What did the admin membership check prove?
5. What could not be proved without ABM, MDM, IdP, or Apple Account access?
6. Why should support avoid changing user permissions casually?
7. How would I explain this lab to a hiring manager?
