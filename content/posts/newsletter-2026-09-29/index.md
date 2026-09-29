---
date: '2026-09-29T07:22:35Z'
draft: false
title: 'Newsletter 2026-09-29'
toc: false
tags: [newsletter articles blogs]
---

Another week, another round.

---

Greynoise has detected exploitation of ZyXEL and WordPress vulnerabilities that led to data exfiltration from several government organizations. Among other things, 17 different AMSI bypass approaches were used. Greynoise included the attackers' tools in the article, which were used to search for cleartext credentials among other things.
- https://www.greynoise.io/blog/open-season-on-kapibala-attacker-steals-government-records-wordpress-exploitation

---
SpecterOps introduces CiliumHound, a tool for visualizing Cilium network policies graphically in BloodHound.
- https://specterops.io/blog/2026/09/17/ciliumhound-graphing-kubernetes-network-policies/

---
Zscaler takes a look at Vidar, which has added virtual machine detection and custom stream ciphers for string obfuscation.
- https://www.zscaler.com/blogs/security-research/vidar-adds-virtual-machine-and-custom-stream-ciphers-string-obfuscation

---
Kaspersky's GERT (Global Emergency Response Team) observed an incident where an attacker gained domain admin equivalent rights and attached a policy at the root level. Login screens were modified and local admin accounts were disabled in the process. The attacker carried out the extortion without ransomware and without encrypting any actual data. According to Kaspersky, this type of attack is growing year over year.
- https://securelist.com/tr/payload-ransomware-via-group-policy/121335/

---
Talos claims to have found, with CLOSEDQUORUM, the first fully AI-controlled C2 implant. Multiple models are used so that if one provider is blocked, unreachable, or refuses, others can take over.
- https://blog.talosintelligence.com/the-closed-quorum-inside-the-first-reported-autonomous-ai-c2-implant/

---
And another AI-assisted attack. Unauthenticated Docker daemons were exploited to pull images from an attacker-controlled registry. Threatdown found that Hermes agents were abused and their Soul.md was overwritten. The agent then received further instructions via Telegram to exfiltrate credentials among other things.
- https://www.threatdown.com/blog/carbonato/

---
LevelBlue shows how Microsoft's Self-Service Password Reset can be used to enumerate existing users, their MFA methods, and admin accounts. Very handy for verifying and classifying found accounts. The amount of information collected depends on the tenant's configuration.
- https://www.levelblue.com/blogs/spiderlabs-blog/enumerating-users-and-mfa-via-microsofts-password-reset-portal

---
TrustedSec gives an extensive overview of the many new additions in HateCrack, this being the first of three parts.
- https://trustedsec.com/blog/whats-new-in-hate-crack-since-2-0

---
The title "Getting root on OnePlus 15 from an untrusted app, via an audio debug service and a vendor HAL" pretty much sums the article up completely. Rasmus Moorats explains in great detail how he achieved this and also provides an Android sandboxing primer along the way.
- https://blog.nns.ee/2026/09/24/oneplus-root/

---
An article I found quite interesting, covering the 8087 and the FPTAN instruction for computing tangents. The 8087 uses a combination of CORDIC and rational polynomials for this, requiring between 30 and 570 cycles, with an average of around 450. When you consider the clock speeds of the 8087, that was practically an eternity.
- http://www.righto.com/2026/09/8087-tangent-cordic.html

---
Netexec now has an MCP server, described in this article by mpgn.
- https://mpgn.fr/building-a-mcp-for-netexec/

---
Tim Perry writes for HTTP Toolkit about enforced certificate transparency under Android 17.
- https://httptoolkit.com/blog/android-17-certificate-transparency/

---
Cyllex took a look at a Lazarus recruiter email and analyzed virtually every component down to the root kit level. There are also mapping and emulation notes included.
- https://cyllex.io/blog/posts/lazarus-ring-0-cve-2026-68820.html

---

Read you next week.
