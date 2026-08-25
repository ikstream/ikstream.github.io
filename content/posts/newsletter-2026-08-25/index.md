---
date: '2026-08-25T04:36:37Z'
draft: false
title: 'Newsletter 2026-08-25'
toc: false
tags: [newsletter, articles, blogs]
---

Another week, another round.

---

Mandiant presents what AVDH (Agentic Vulnerability Discovery Harness) has been doing for them and how it fits into the existing AI landscape alongside CodeMender.
- https://cloud.google.com/blog/topics/threat-intelligence/staying-ahead-of-adversarial-ai-through-agentic-source-code-review/

---
Varonis reported a vulnerability to Microsoft in Copilot Personal. Almost as interesting as the one-click data exfiltration itself is the timeline. It was reported in December 2025, and the patches were released on 18.08.2026, the same day as the article. With the time from publication to exploit getting shorter and shorter, I find that a bit of a stretch.
- https://www.varonis.com/blog/cosnitch

---
LevelBlue takes a look at Shieldbreak by nightmare eclipse.
- https://www.levelblue.com/blogs/spiderlabs-blog/cloud-sync-root-registrationshieldbreak-hunting-windows-defender-remediation-abuse-and-cloud-files-hijacking

---
After OpenAI posted several CVEs related to Artifactory, Edra went looking for a pre-auth RCE and walks us through the journey from no credentials to RCE in 5 steps.
- https://edrabb.fr/posts/full-chain-preauth-rce-jfrog-artifactory/

---
Talos has taken apart the Linux variant of the current SPECTRE malware and created a write up of the whole process in detail.
- https://blog.talosintelligence.com/uat-10147-deploys-spectre-a-cross-platform-implant-with-linux-rootkit-and-byovd-capabilities/

---
Julian Catrambone and Daniel Heinsen from SpecterOps apparently had a painful time with AWS and came to the conclusion that it made sense to write a new tool. True to SpecterOps style, the new tool is compatible with BloodHound Community Edition and goes by AWSHound. Definitely worth a try on the next AWS engagement.
- https://specterops.io/blog/2026/08/19/awshound-opensource-aws-opengraph-collector/

---
Intruder introduces their new tool gitreaper, which they used to search a large number of Git repos for secrets and were quite successful at it.
- https://www.intruder.io/research/api-keys-bank-details-disciplinary-files-what-28-000-exposed-git-repos-gave-up

---
Kaspersky has found what they describe as the first malware living exclusively in car head units, used for ad fraud and as a proxy network.
- https://securelist.com/android-head-unit-malware/121106/

---
Varonis' Hai Vaknin introduces the `usernamemixed` Azure endpoint, which through multiple return values allows enumeration of MFA-protected accounts and password spraying. Disabling legacy authentication is a solid mitigation here.
- https://www.varonis.com/blog/ws-trust-autologon-endpoint

---
Threat actor profile on Qilin including MITRE mappings of their typical tactics, put together by Gurucul.
- https://gurucul.com/blog/threat-actor-profile-qilin/

---
Jiří Vinopal from Checkpoint introduces the latest tool [BTR_CLI](https://github.com/Dump-GUY/BTR_CLI), which takes Microsoft Defender's Boot Time Removal Tool (BTR.sys) as a starting point to bypass EDR/AV and relies on Alternative Data Streams. The tool makes it possible to get a Ring-0 entry point from user mode.
- https://research.checkpoint.com/2026/btr-reforged-weaponizing-defenders-remediation-driver-as-a-kernel-operation-primitive/

---

Read you next week.
