# tryhackme-writeups
This repository contains detailed write-ups regarding TryHackMe challenge rooms, excellent for people aiming to study for the PT1 exam.

## Contents

### Web Application

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Recruit | [Room](https://tryhackme.com/room/recruitwebchallenge) | [Technical Walkthrough](Web%20Application/Recruit/Recruit.md) | Explores a realistic web application attack chain, combining information disclosure, Local File Inclusion, and SQL Injection to obtain administrator access. |
| Support | [Room](https://tryhackme.com/room/support) | [Technical Walkthrough](Web%20Application/Support/Support.md) | Exploits authentication and access control vulnerabilities to obtain privileged access and ultimately achieve remote code execution on the target. |

---

### Network

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Jump | [Room](https://tryhackme.com/room/jump) | [Technical Walkthrough](Network/Jump/Jump.md) | Explains how multiple Linux privilege escalation opportunities, including writable scripts, PATH hijacking, and sudo misconfigurations, can be chained from anonymous FTP access to root. |
| Windows Jump | [Room](https://tryhackme.com/room/windowsjump) | [Technical Walkthrough](Network/Windows%20Jump/Windows%20Jump.md) | Details a Windows privilege escalation chain that progresses from guest access to NT AUTHORITY\SYSTEM by abusing exposed credentials, writable services, and scheduled tasks. |
| Domino | [Room](https://tryhackme.com/room/domino) | [Technical Walkthorugh](Network/Domino/Domino.md) | Follows an attack chain combining user enumeration, credential reuse, IDOR, JWT manipulation, Remote File Inclusion, and writable root-executed scripts to progress from a low-privileged web account to full root access. |
| Silent Monitor | [Room](https://tryhackme.com/room/silent-monitor) | [Technical Walkthrough](Network/Silent%20Monitor/Silent%20Monitor.md) | Covers how SQL Injection, command injection, exposed credentials, and an insecure KeePass backup can be chained to progress from web application access to full root compromise. |
| Operation Promotion | [Room](https://tryhackme.com/room/operationpromotion) | [Technical Walkthrough](Network/Operation%20Promotion/Operation%20Promotion.md) | Explores how SQL Injection, command injection, exposed credentials, targeted password cracking, and a sudo misconfiguration can be chained to progress from unauthorised web application access to full root compromise. |

---

### Active Directory

| Room | TryHackMe | Walkthrough | Details |
|------|-----------|-------------|---------|
| Proxy | [Room](https://tryhackme.com/room/proxychallenge) | [Technical Walkthrough](Active%20Directory/Proxy/Proxy.md) | Covers how anonymous SMB access, Active Directory coercion, NetNTLMv2 credential recovery, and constrained delegation can be chained to achieve Domain Administrator access. |
| Forward | [Room](https://tryhackme.com/room/forwardchallenge) | [Technical Walkthrough](Active%20Directory/Forward/Forward.md) | Explores how insecure credential management, password reuse, and excessive Active Directory delegation can be chained through Resource-Based Constrained Delegation to obtain SYSTEM access on a Domain Controller. |
| Dead Drop | [Room](https://tryhackme.com/room/dead-drop) | [Technical Walkthrough](Active%20Directory/Deaddrop/DeadDrop.md) | Demonstrates how weaknesses across a web application, mobile application, and Active Directory can be chained together to achieve full domain compromise. |

---

## Objectives

Each walkthrough aims to:

- Follow a structured penetration testing methodology.
- Explain the reasoning behind each step.
- Preserve the commands used during the assessment.
- Demonstrate realistic attack chains and privilege escalation techniques.
- Highlight remediation recommendations for identified weaknesses.
