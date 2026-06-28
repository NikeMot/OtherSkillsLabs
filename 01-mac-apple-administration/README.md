# 01 — Mac / Apple Administration

## Purpose

This folder contains labs for supporting and administering Apple devices in a Mac-focused MSP or enterprise support environment.

The labs should build evidence for a Mac Support Specialist role: 1st/2nd line macOS support, customer communication, troubleshooting, documentation, escalation, Apple device management awareness, identity platform awareness, and networking fundamentals.

## Target Role

The target role is a Mac Support Specialist position in a Mac-focused Managed Service Provider.

The role requires evidence of:

* hands-on Mac and macOS support ability
* hardware, software, and connectivity troubleshooting
* excellent customer service and technical communication
* Apple device management awareness, including Addigy and Jamf-style workflows
* identity platform awareness, including JumpCloud and Okta-style workflows
* accurate incident, resolution, and process documentation
* escalation-quality evidence for senior engineers
* networking fundamentals for Mac support scenarios
* continuous service improvement thinking

## Primary Lab Skeleton

Use `Apple Device Management` as the primary curriculum skeleton.

Each lab should cover two chapters from `Apple Device Management`:

```text
Lab 01 -> Apple Device Management chapters 1-2
Lab 02 -> Apple Device Management chapters 3-4
Lab 03 -> Apple Device Management chapters 5-6
Lab 04 -> Apple Device Management chapters 7-8
Lab 05 -> Apple Device Management chapters 9-10
Lab 06 -> Apple Device Management chapters 11-12
Lab 07 -> Apple Device Management chapters 13-14
Lab 08 -> Apple Device Management chapters 15-16
Lab 09 -> Apple Device Management chapters 17-18
Lab 10 -> Apple Device Management chapters 19-20
Lab 11 -> Apple Device Management chapters 21-22
Lab 12 -> Apple Device Management chapters 23-24 or final capstone coverage
```

If the edition being used has fewer or more chapters, keep the same rule: two chapters per lab until the book is complete, then use the remaining lab time for role-specific capstone work.

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

Hands-on Mac labs should prioritise what can be done with a local macOS account, safe local settings, command-line checks, logs, networking diagnostics, filesystem inspection, configuration-profile analysis, and documentation.

## Official Online Documentation Rule

Every Mac lab must follow `docs/official-online-documentation-standard.md`.

Books provide structure, but Apple platform behaviour changes. Official Apple documentation keeps the lab current.

Every Mac lab must include an `Official online documentation checked` section.

Use official Apple documentation first for deployment, MDM, Apple Business Manager, macOS user support, device management payloads, security settings, software update behaviour, identity integration, FileVault, networking, certificates, and supervision/enrolment behaviour.

Primary official online sources:

| Area | Official documentation |
| --- | --- |
| Apple deployment and MDM | https://support.apple.com/guide/deployment/welcome/web |
| Apple Business Manager | https://support.apple.com/guide/apple-business-manager/welcome/web |
| Mac user and support workflows | https://support.apple.com/guide/mac-help/welcome/mac |
| Apple device management API and payloads | https://developer.apple.com/documentation/devicemanagement |

## Required Supplements

Every Mac lab should supplement the Apple Device Management chapter pair with:

* `macOS Support Essentials` for practical troubleshooting, user support, and support technician workflow
* `Modern Operating Systems` for deeper operating system concepts such as processes, memory, filesystems, I/O, security boundaries, and networking concepts
* `The Practice of System and Network Administration` for how work should be executed: ticket hygiene, documentation, repeatability, escalation, change awareness, customer communication, and service improvement
* official Apple online documentation for current platform behaviour and vendor-supported guidance
* the target Mac Support Specialist job requirements: Addigy, Jamf, JumpCloud, Okta, networking fundamentals, customer service, accurate documentation, escalation, and continuous service improvement

## Topic Focus

Labs in this folder may cover:

* macOS first-line and second-line support
* local users and permissions
* FileVault
* Keychain
* Gatekeeper
* software updates
* Wi-Fi, VPN, DNS, proxy, and certificate issues
* Apple Business Manager concepts, handled conceptually unless access is available
* MDM enrolment concepts, handled conceptually unless access is available
* Addigy and Jamf concepts
* JumpCloud and Okta concepts
* configuration profiles
* app deployment concepts and non-App-Store local installation where possible
* Microsoft 365 and identity integration concepts
* support ticket documentation
* customer update messages
* escalation notes
* service improvement suggestions

## Mandatory Career Layers

Every Mac / Apple administration lab must also include:

* structured troubleshooting logic
* user-friendly communication
* manager or escalation update
* interview explanation
* personal branding output
* reflection on confidence and professionalism

## Example Lab Folder Names

```text
lab-01-apple-device-management-foundations/
lab-02-macos-support-and-identity-basics/
lab-03-device-enrolment-and-mdm-workflow/
lab-04-configuration-profiles-and-policy-control/
lab-05-filevault-gatekeeper-and-certificate-support/
lab-06-jamf-addigy-jumpcloud-okta-concepts/
lab-07-app-deployment-and-software-update-support/
lab-08-macos-network-and-connectivity-troubleshooting/
lab-09-logs-monitoring-and-escalation-evidence/
lab-10-documentation-service-improvement-and-sops/
lab-11-msp-client-support-scenario/
lab-12-mac-support-specialist-capstone/
```

## Evidence Standard

Mac support evidence should be documented clearly but safely. Do not commit serial numbers, real user names, asset tags, screenshots with private information, company data, live configuration exports, Apple Account details, iCloud details, or personal Apple service data.

Useful evidence includes support-ticket write-ups, customer updates, escalation notes, troubleshooting decision trees, network diagnostic notes, profile or MDM concept notes, OS-depth notes, official documentation checks, conceptual Apple Account or ABM workflow notes, and service improvement observations.
