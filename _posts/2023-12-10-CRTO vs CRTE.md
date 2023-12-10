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
CRTE is being presented by (Altered Security) and was presented previously by (Pentester Academy). The course is designed to teach anyone how to penetrate an active directory environment using offensive PowerShell and open-source tools. As I said earlier in my previous blog about CRTE, its major selling point is in the living-off-the-land approach to Active Directory penetration testing.

### Certified Red Team Operator (CRTO) :
CRTE is being presented by (Zero Point Security). The course is designed to teach anyone how to penetrate an active directory environment using Command & Control infrastructure (C2). From my perspective, the main selling point here is the opportunity to play with Cobalt Strike, which will cost any company a couple of thousand each year.

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

>These methods are covered in both classes in a fair amount of detail, giving the learner a better understanding of what's going on and how it might be exploited to obtain additional access. But occasionally, one course might skip over a subject or only skim the surface while the other delves deeply into it.

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
