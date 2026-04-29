---
date: '2026-04-29T18:04:50Z'
draft: false
title: 'Newsletter 2026-04-29'
toc: false
tags: [newsletter articles blogs]
---

Another week, another round of interesting news.

---


Lazarus comes around the corner with a new malware variant for Macs and has ported a known variant from Go to Python using AI.
The entry point is Telegram messages containing fake Teams, Meets, or Zoom invitations.
- https://any.run/cybersecurity-blog/lazarus-macos-malware-mach-o-man/

---

Talos sees strong growth in the adoption of Macs in the enterprise world. So far, Living off the Land tools seem to be less documented. They want to address this in their post. Certainly doesn't hurt to be broadly positioned.
- https://blog.talosintelligence.com/bad-apples-weaponizing-native-macos-primitives-for-movement-and-execution/

---

And since we're already on the topic of Mac problems, Calif published another entry in the MAD Bugs series. They developed a Mac N-day PoC with simple prompts for a current system. They documented the process in an entertaining way.
- https://blog.calif.io/p/mad-bugs-an-apple-kernel-bug-brought

---

Because I didn't have any last week, this week there are several supply chain attacks again. This time the Bitwarden CLI tool on npm got hit. Also PGServe. Both target credentials though.
- https://www.stepsecurity.io/blog/bitwarden-cli-hijacked-on-npm-bun-staged-credential-stealer-targets-developers-github-actions-and-ai-tools
- https://www.ox.security/blog/shai-hulud-bitwarden-cli-supply-chain-attack/
- https://www.stepsecurity.io/blog/pgserve-compromised-on-npm-malicious-versions-harvest-credentials

---

And since it's boring to only look at npm, there are also three compromised versions of the xinference PyPi package.
- https://www.stepsecurity.io/blog/teampcp-injects-two-stage-credential-stealer-into-xinference-pypi-package

---

JumpSec analyzes the ALBIRIOX (Android) malware, which is sold as Malware-as-a-Service (MaaS). It's almost scary how cheap the whole thing is ($1300-$1450 depending on version) and makes it clear why there's a feeling that attacks are increasing.
The malware offers various functions like "real-time screen surveillance, live keylogging, credential phishing HTML overlays, device PIN capture, notification/SMS interception, and full remote device control/filesystem access". And all this besides the actual function as a crypto drainer and fraud platform.
- https://www.jumpsec.com/guides/albirox-malware-analysis/

---

Ctrl-Alt-Intel builds a bridge between supply chain attacks and attacks on TPLink and ASUS routers.
- https://ctrlaltintel.com/research/ProxyPCP/

---

Mandiant analyses the approach of UNC6692. This TA uses social engineering to distribute custom malware. Mandiant also takes a closer look at the malware.
- https://cloud.google.com/blog/topics/threat-intelligence/unc6692-social-engineering-custom-malware/

---

Bellingcat looked at Rednote as a source for OSINT and worked out some information.
- https://www.bellingcat.com/resources/2026/04/20/xiaohongshu-rednote-open-source-guide/

---

Coerced authentication through XXE for ESC8 is a creative combination.
- https://www.klogixsecurity.com/scorpion-labs-blog/a-new-twist-on-an-old-trick-xxe-to-ntlm

---

Orange Cyberdefense documented how they built a C2 channel over Teams.
- https://blog.scrt.ch/2026/04/21/from-a-regular-red-team-exercise-to-developing-a-custom-c2-channel-over-ms-teams/

---

Securelist presents an abuse of interprocess communication for privilege escalation. Windows RPC calls are used. According to Securelist, this is a new path. I wasn't familiar with it.
- https://securelist.com/phantomrpc-rpc-vulnerability/119428/

---

Point Wild takes a look at the Vidar malware, which has now evolved into a whole framework. They break down the approach incorporating other sources.
- https://www.pointwild.com/threat-intelligence/inside-vidar-2026-from-infection-to-memory-execution-via-jpeg-and-txt-payloads/

---

Trail of Bits engaged with Google's zero knowledge proof for quantum circuits and suggested some improvements.
Anyone interested in quantum computing and crypto concepts might find this exciting. I had to google several times and wouldn't claim to have understood everything, but I found it interesting.
- https://blog.trailofbits.com/2026/04/17/we-beat-googles-zero-knowledge-proof-of-quantum-cryptanalysis/

---

Read you next week

