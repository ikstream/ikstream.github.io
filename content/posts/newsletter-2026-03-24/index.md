---
date: '2026-03-24T05:27:46Z'
draft: false
title: 'Newsletter 2026-03-24'
toc: false
tags: [newsletter articles blogs]
---

Another week another round of interesting articles I came across during the week.
Even though it's again without a specific theme, Talos made it into the list twice.

---

An approach to add agents to a C2 through indirect prompt injections. The whole thing builds on prompting and further reduces the technical requirements for attackers, which in turn could increase the number of attacks.
- https://embracethered.com/blog/posts/2026/agent-commander-your-agent-works-for-me-now/

---
Various threat actors are now apparently relying on an iOS exploit chain called DarkSword. The Google Threat Intelligence Team has a very interesting  write up on that chain.
- https://cloud.google.com/blog/topics/threat-intelligence/darksword-ios-exploit-chain/

---
Talos introduces a new tool for COM monitoring to get better insight into malware behavior without triggering any analysis evasion behavior. Also pretty interesting to see what your own malware is doing.
- https://blog.talosintelligence.com/transparent-com-instrumentation-for-malware-analysis/

---
Whenever I come across some information disclosure through status messages I am surprised, that even big players keep giving away information through their status messages. Below you can find the return values for AWS.
- https://hackingthe.cloud/aws/enumeration/detect_public_resource_exposure_via_error_messages/

---
Praetorian demonstrates in their blog how they were able to exploit an `http only` cookie in an XSS attack. An `innerHTML` block was exploited that reflects the cookies accordingly. The chain could be continued all the way to RCE.
- https://www.praetorian.com/blog/httponly-cookie-bypass-xss-ghostscript-rce/

---
nyxgeek presents the Azure SignIn Log bypasses from recent months (four in total) on the TrustedSec blog.
- https://trustedsec.com/blog/full-disclosure-a-third-and-fourth-azure-sign-in-log-bypass-found

---
Both APTs and smaller threat actors decreasingly rely on complex malware and instead more on on-board tools that can be tricky to detect.
Talos presents the Ransomware Exfiltration Framework on their blog, which should help the blue team better detect and classify LOL attacks. From my perspective, it could also help to monitor the use of PowerShell and CMD more closely. Directly disable them on endpoints where it's probably not used.
- https://blog.talosintelligence.com/everyday-tools-extraordinary-crimes-the-ransomware-exfiltration-playbook/

---
Something non-technical for a change, but a really interesting perspective on the impact of AI on CTFs.
- https://k3ng.xyz/blog/ctf-is-dead

---
KlezVirus introduces BYOUD (Bring Your Own Unwinding Data), a framework for stack spoofing that specifically manipulates the Windows unwind metadata (.pdata/.rdata) and thus doesn't touch the shadow stack and can represent a working approach against Intel's CET (Control-flow Enforcement Technology).
- https://klezvirus.github.io/posts/Byoud/

---

Read you next week
