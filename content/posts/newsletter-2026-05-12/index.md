---
date: '2026-05-12T04:08:41Z'
draft: false
title: 'Newsletter 2026-05-12'
toc: false
tags: [newsletter articles blogs]
---

Another Week, another round of interesting news. This time with different views on the Claude Mythos results from Mozilla and Curl

---

Citizenlab has compiled studies on telco network surveillance. Very comprehensive, but also very interesting.
- https://citizenlab.ca/research/uncovering-global-telecom-exploitation-by-covert-surveillance-actors/

---

Talos has identified a previously unknown attacker using the CloudZ RAT with a plugin "Pheno" that's used to check if the Phone Link application is being used under Windows. The goal is probably to obtain credentials and possibly also OTP codes.
- https://blog.talosintelligence.com/cloudz-pheno-infostealer/

---

An interesting article on how tools for validating images are being used to present real images as manipulated images.
- https://www.techpolicy.press/how-ai-content-detection-is-being-weaponized-in-the-iran-war/

---

Jakob Wolffhechel conducted a 9-week audit of the management stack of XenServer. This resulted in 89 (!) vulnerabilities. If I saw correctly, all with GCVEs. Some low and medium findings, but also various high and criticals. Worth taking a look, especially if you're dealing with it.
- https://shittrix.moksha.dk/

---

Qilin had an OpSec problem that Ctrl-Alt-Intel used to take a closer look at parts of current operations.
- https://ctrlaltintel.com/research/Qilin/

---

And because it's something different, today Ruby Gems and Go modules have been compromised.
- https://socket.dev/blog/malicious-ruby-gems-and-go-modules-steal-secrets-poison-ci?utm_medium=feed

---

Newton Paul went hunting for internet-facing C2 frameworks and found, among other things, an Android C2 that apparently isn't known yet.
- https://newtonpaul.com/blog/hunting-ai-generated-c2/

---

SynAcktiv was able to inject a reverse shell into the Philips Hue Bridge at Pwn2Own, and that over the Zigbee channel. Through cleverly chosen triggers, they could reliably trigger the attack.
- https://www.synacktiv.com/en/publications/make-it-blink-over-the-air-exploitation-of-the-philips-hue-bridge.html

---

Talos shows in their blog post how VOIP numbers are structured and how they're reused in scam campaigns.
- https://blog.talosintelligence.com/insights-into-the-clustering-and-reuse-of-phone-numbers-in-scam-emails/

---

Nico Dekens describes the problems that are becoming increasingly apparent for many OSINT professionals. Source verification is becoming increasingly difficult as information is being placed more deliberately and disinformation campaigns (partly with the help of AI) are becoming easier.
- https://www.dutchosintguy.com/post/evidence-poisoning-the-osint-crisis-nobody-is-ready-for

---

GitHub looked at how to monitor and make token usage more efficient in agent-based workflows.
Removing unnecessary software is once again an advantage here.
- https://github.blog/ai-and-ml/github-copilot/improving-token-efficiency-in-github-agentic-workflows/

---

Daniel Stenberg comments on the results Mythos found in curl and clarifies that it's significantly fewer than many expected/feared (depending on perspective). But also makes clear that AI-assisted bug hunting delivers significantly better results than classic scanners.
- https://daniel.haxx.se/blog/2026/05/11/mythos-finds-a-curl-vulnerability/

---

Mozilla also addresses the results and apparently has "stronger results" in Firefox 150.
To just quote this:
"Of the 271 bugs we announced for Firefox 150: 180 were sec-high, 80 were sec-moderate, and 11 were sec-low."
- https://hacks.mozilla.org/2026/05/behind-the-scenes-hardening-firefox/

--- 

Read you next week
