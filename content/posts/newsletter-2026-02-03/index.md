---
date: '2026-02-03T18:10:41Z'
draft: false
title: 'Newsletter 2026-02-03'
toc: false
tldr: News From Week 6 
tags: [newsletter articles blogs]
---

Welcome back to the newsletter in week 6. 

---
WhiteKnightLabs writes about hollowing out Electron apps and the advantages this can bring in tightly controlled networks. Short but punchy.
-  https://whiteknightlabs.com/2026/01/20/backdooring-electron-applications/

--- 
Sean Heelan actually provides numbers and code here on what it takes using agents to develop proof-of-concept exploits that didn’t previously have any known PoCs.
- https://sean.heelan.io/2026/01/18/on-the-coming-industrialisation-of-exploit-generation-with-llms/

In that context, this one’s also worth a read, even if it’s a bit older:
- https://sean.heelan.io/2025/05/22/how-i-used-o3-to-find-cve-2025-37899-a-remote-zeroday-vulnerability-in-the-linux-kernels-smb-implementation/

--- 
ErrTraffic is a traffic distribution system specifically built for ClickFix campaigns. [Censys already took a look at it](https://censys.com/blog/errtraffic-inside-glitchfix-attack-panel), as did [others](https://www.infostealers.com/article/the-industrialization-of-clickfix-inside-errtraffic/). But I found this blog particularly interesting since it digs into the (at least partially AI‑generated) source code and discusses several flaws plus the authors’ attempts to patch them.
- https://ctrlaltintel.com/threat%20research/ErrTraffic/

---
Clawd/Molten/OpenClaw, or whatever it’s called this week, offers tons of intriguing possibilities, but also a huge attack surface. From self‑downloaded (and sometimes backdoored) skills to data leaks, memory poisoning, and even active exploitation on external systems, it seems pretty much everything’s in there.
- https://www.infostealers.com/article/the-autonomous-adversary-from-chatbot-to-criminal-enterprise/

For anyone not up to speed on what it’s about, here’s a nice recap and maybe even more has happened since i have read it:
- https://www.cnet.com/tech/services-and-software/from-clawdbot-to-moltbot-to-openclaw/

And directly related to that: a supply chain attack.
- https://www.koi.ai/blog/clawhavoc-341-malicious-clawedbot-skills-found-by-the-bot-they-were-targeting

---
Registry modifications are now well detected by many EDRs, making them tricky for persistence. Praetorian introduces a technique based on the “Mandatory User File”. If the file doesn’t exist, a low‑priv user can create it, and it get's executed at every login. The modification can also be made outside the target system to bypass API monitoring. The downside is, that the Mandatory User Profile changes might overwrite modifications made by the user.
- https://www.praetorian.com/blog/corrupting-the-hive-mind-persistence-through-forgotten-windows-internals/

---
A phishing campaign that relies on the victim copying a malicious URL including OAuth materials, but the system itself stays untouched, making detection much harder. It also used pre‑filtering for emails to prevent early exposure of the campaign. 
- https://pushsecurity.com/blog/consentfix

Pushsecurity also provides a great resource about phishing techniques:
- https://phishing-techniques.pushsecurity.com/

---
Mac users might find this one interesting. It turns out the Brew system can be configured in surprisingly insecure ways, namely skipping checksum verification and and sending data over HTTP.
- https://www.koi.ai/blog/brew-hijack-serving-malware

--- 
Read you next time

