---
date: 2023-12-10
layout: post
title:  "CRTO vs CRTE (2Cs)"
subtitle: "CRTO vs CRTE"
tags: 
  - Review 
  - Certifcates
image: >- 
  /assets/img/CRTOvsCRTE/godzilla-vs-kong.png
optimized_image: >- 
  /assets/img/CRTOvsCRTE/godzilla-vs-kong.png
category: blog
author: Karim (Coke)
paginate: true
---

## Introduction

### Certified Red Team Expert (CRTE) :
CRTE is being presented by (Altered Security) and was presented previously by (Pentester Academy). The course is designed to teach anyone how to penetrate an active directory environment using offensive PowerShell and open-source tools😁. As I said earlier in my previous blog about CRTE, its major selling point is in the living-off-the-land approach to Active Directory penetration testing.

### Certified Red Team Operator (CRTO) :
CRTE is being presented by (Zero Point Security). The course is designed to teach anyone how to penetrate an active directory environment using Command & Control infrastructure (C2)(**Cobalt Stirke**)😎. From my perspective, the main selling point here is the opportunity to play with Cobalt Strike, which will cost any company a couple of thousand each year.

## Course Content

### The Similarity between CRTE & CRTO :
* Domain Enumeration
* User Impersonation (Pass The Hash - Over Pass The Hash - Pass The Ticket)
* Lateral Movement
* Kerberos Attacks (Delegation Attacks - Kerbroasting - AsRep-Roasting)
* Group Policy
* MSSQL Server Attacks
* Domain Persistence (Golden Ticket - Silver Ticket - Diamond Ticket)
* Domain/Forest Trust Abuses
* Applocker/WDAC Bypasses
* Basics of AV/EDR Evasion

> Both courses go through these techniques in some detail, which helps the student understand what's happening and how it could be used to gain more access. But sometimes, one course might just scratch the surface of a subject while the other dives deep into it..

### The Difference between CRTE & CRTO :

The obvious difference is that one of the courses (CRTO) focuses on the utilisation of a C2 frameworks (cobalt strike) and the other focus on using extensive powershell and open source tools.But that is not the only difference between them,there are some differences in the prestend content as we can see below.

#### CRTO
* External Reconnaissance
* Intial Compromise
* Host Reconnaissance
* Process Injection
* Session Passing
* Pivoting
* Data Protection API (DPAPI)
* NTLM Relaying

> As mentioned in the course, all of the instructions may be changed to be executed directly on the target system, even if the focus is on using Cobalt Strike to carry out these techniques. In other words, using a C2 is not absolutely necessary in order to comprehend and make use of the content.

#### CRTE
* PowerShell OPSEC
* AV/EDR bypass Techniques for PowerShell and C#
* Access Control List Abuse (e.g. gMSA)
* Cross-Forest Attacks
* AD Defences and Mitigations

>The majority of this course is built around a "living-off-the-land" mentality, which involves using Microsoft's own tools against them wherever it is practical.

## Labs
Here where the fun starts🤤,

### CRTO
The labs are available online and require a subscription to Immersive Labs Cyber Ranges (SnapLabs) for the (CRTO). While not strictly required, this adds another expense to the course/exam package. You will be disappointed if you decide not to take part in the labs because this is one of the few chances you will have to use C2, especially in the event of a cobalt strike.According to my observations during the labs, they were extremely stable. However, when I attempted to take advantage of cross-forest attacks, I encountered some problems where the DC of one of the forests wasn't responding for some reason. Nevertheless, after an hour, for some reason, everything was back to normal😑.Subscription fees are £36 per month for 40 hours.

![CRTO_Lab](/assets/img/CRTOvsCRTE/CRTO_Lab.png)

### CRTE
The labs are hosted in Azure and can be accessed via VPN or RDP over Guacamole. They are accessible online and don't require a subscription. The cost you pay will cover both the course content and the labs.There is also a lab handbook that guides you through the lab material and demonstrates how to carry out the attacks; however, this frequently deviates (slightly) from what is said or shown in the videos.It's also important to note that Covenant C2 is used to guide you through the content in the CRTE manual.😉

## Exam



