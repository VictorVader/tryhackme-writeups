# tryhackme-writeups
This repository contains detailed write-ups regarding TryHackMe challenge rooms, excellent for people aiming to study for the PT1 exam.

## Contents

### Web Application

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Recruit | [Room](https://tryhackme.com/room/recruitwebchallenge) | [Technical Walkthrough](Web%20Application/Recruit/Recruit.md) | Explores a realistic web application attack chain, combining information disclosure, Local File Inclusion, and SQL Injection to obtain administrator access. |

---

### Network

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Jump | [Room](https://tryhackme.com/room/jump) | [Technical Walkthrough](Network/Jump/Jump.md) | Explains how multiple Linux privilege escalation opportunities, including writable scripts, PATH hijacking, and sudo misconfigurations, can be chained from anonymous FTP access to root. |
| Windows Jump | [Room](https://tryhackme.com/room/windowsjump) | [Technical Walkthrough](Network/Windows%20Jump/Windows%20Jump.md) | Demonstrates a Windows privilege escalation chain that progresses from guest access to NT AUTHORITY\SYSTEM by abusing exposed credentials, writable services, and scheduled tasks. |

---

### Active Directory

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Dead Drop | [Room](https://tryhackme.com/room/dead-drop) | [Technical Walkthrough](Active%20Directory/Deaddrop/DeadDrop.md) | Demonstrates how weaknesses across a web application, mobile application, and Active Directory can be chained together to achieve full domain compromise. |

---

## Objectives

Each walkthrough aims to:

- Follow a structured penetration testing methodology.
- Explain the reasoning behind each step.
- Preserve the commands used during the assessment.
- Demonstrate realistic attack chains and privilege escalation techniques.
- Highlight remediation recommendations for identified weaknesses.
