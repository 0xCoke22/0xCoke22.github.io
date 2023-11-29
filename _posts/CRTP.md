---
date: 2023-11-29
layout: post
title: Certified Red Team Professional (CRTP) Review
subtitle: 'CRTP Cerifcate Reveiw'
description: >-
  Altered Security's Certified Red Team Professional (CRTP) is a beginner friendly hands-on red team certification. It is one of the most popular beginner Red Team certification. 
image: >-
  /assets/img/uploads/CRTP.png
optimized_image: >-
  /assets/img/uploads/CRTP.png
category: blog
tags:
  - Review
  - Certifcates
  - Blog
author: Karim (Coke)
paginate: true
---

## Introduction
As a red teamer or as a penetration tester in general you're guaranteed to encounter active directory (AD). Almost every major organization uses Active Directory to manage the authentication and authorization of servers and workstations in their environment.

Active Directory (AD) can be considered a complex product, and managing it securely becomes increasingly difficult at a larger scale for this reason, AD is so interesting from an offensive perspective, you can take over an entire organization by just abusing simple misconfigurations and believe me when i tell you that taking over an organization will give an adrenaline rush and feeling of power that you gonna love it 😅

## Course

The course describes itself as a "**Beginner Friendly**" course, supported by a lab environment and well explained videos,these videos are divided to three parts (Offensive Contnet,Defensive Content,Labs Walkthrough) totaling in 14 hours of video material😓.

The course outline of the following:

#### Offensive Side:
* Domain Enumeration
* Local Privilege Escalation
* Lateral Movement
* Domain Persistence
* Domain Privilege Escalation
* Cross-Forest Attacks
* Forest Persistence

#### Defensive Side:
* Defenses — Monitoring
* Defenses and bypass — Architecture and Work Culture Changes
* Defenses and Bypass — Deception
* Defenses and Bypass — PowerShell

One thing you might notice is that the section on defense and detection is single-ended😥. This is an interesting feature, but it's not the course's primary selling point. This course will help you comprehend the "red" mindset, potential configuration vulnerabilities, and, to some extent, how to monitor and identify attacks on these faults if you're a blue team member trying to hone your AD defensive skills. The course materials alone should be sufficient for the majority of blue team members, though, as the exam is entirely focused on red.


## Labs
In my own opnion the lab enviroment was the best thing in the course. Overall,it’s the most stable and accessible lab environment I’ve seen so far.Every user has two options to access the labs either through VPN or through RDP access over Guacamole.The lab mimics a real world enterprise environment and the users need to rely on misconfigurations and feature abuse to challenge the lab.The architecture of the lab can be viewed below.
![CRTP_Lab](/assets/img/uploads/CRTP_Lab.png)

During solving the labs,you will use a lot of PowerShell-based tools but the as the content creator recommends and as I also recommend run through the labs a second time using Cobalt Strike or any C2 you like which will confront you with a whole range of new challenges and learnings. Due to the accessibility of the labs, it provides a great environment to test new tools and techniques as you discover them.

## Exam
I consider the CRTP certification exam is not one to underestimate but it's not hard also,you start the exam by having a low-privileged foothold on a machine and you need to esclate your privilges on that machine then you need to compromise other five machines and these machines are spreaded over multiple domains.you will have 24 hour to complete the exam and another 48 hour to wirte the report and submitting it.


> You need to compromise all the five machines to pass the exam and don't worry every thing you need to pass the exam is within the course material.

### Prepration Tips
* Pick right timing to start the exam
* Be comfortable wth the labs
* Create your own cheat sheet
