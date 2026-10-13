---
date: '2026-10-13T04:00:19Z'
draft: false
title: 'Newsletter 2026-10-13'
toc: false
tags: [newsletter articles blogs]
---

Another week, another round.

---

g3tsyst3m explains the difference between module stomping and function stomping, where shellcode is written directly into an already-loaded exported function in the target process, without loading new modules or allocating new memory. Typical detection markers like CreateRemoteThread or VirtualAllocEx can be avoided by choosing a function the target process calls regularly anyway. The whole thing is implemented as a complete BOF for Adaptix C2, including PIC shellcode from the Crystal Palace toolchain that can run position-independently anywhere.
- https://g3tsyst3m.com/process%20injection/Let's-Create-A-Function-Stomping-BOF-for-Adaptix-C2!/

---
Unit42 has uncovered an Iran-aligned campaign called Blinder Tunnel targeting critical infrastructure in Iraq. The attackers pose as recruiters from Dubai Airports' IT department and deliver a trojanized Visual Studio project as a supposed coding test. Simply opening it in the IDE is enough to trigger the infection chain. The GitHub API is abused for C2 communication, while AppDomainManager hijacking and DLL sideloading handle initial execution and ETW disabling.
- https://unit42.paloaltonetworks.com/blinder-tunnel-targets-critical-infrastructure/

---
Part 2 of TrustedSec's series on password cracking.
- https://trustedsec.com/blog/hashcatrosetta-reading-the-rosetta-stone-of-password-cracking

---
Searchlight Cyber found two vulnerabilities in Discourse. The first allows manipulation of the anonymous page cache and stored XSS injection for all anonymous visitors via a CSP bypass. The second is a TOCTOU race condition in the image upload pipeline that, through a combination of JXL/PostScript polyglot, ImageMagick, and Ghostscript, allows reading arbitrary files on the server and is a potential path to RCE.
- https://www.slcyber.io/research/a-jpeg-a-race-and-a-ghost-breaking-discourses-image-pipeline

---
Datadog took a look at Kubernetes RBAC with a particular focus on built-in principals, examining permissions that could have dangerous consequences for the cluster.
- https://securitylabs.datadoghq.com/articles/kubernetes-rbac-built-in-principals-dangerous-permissions/

---
ESET's Security Research took a closer look at the SparroWocky malware. It uses a custom PE loader with host process camouflage and API hashing. The suspected author is the TA FamousSparrow, which has primarily shifted its focus to Latin America as a target this year.
- https://www.welivesecurity.com/en/eset-research/beware-sparrowock-backdoor-bites-commands-catch/#latin-america-in-the-crosshairs

--- 

Read you next week.
