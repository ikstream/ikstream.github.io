---
date: '2026-08-04T06:44:28Z'
draft: false
title: 'Newsletter 2026-08-04'
toc: false
tags: [newsletter articles blogs]
---

Another week, another round. 

---

Starting with a GitHub repo today. This is another intentionally vulnerable project, and having drones as the target makes for a nice change.
- https://github.com/nicholasaleks/Damn-Vulnerable-Drone

---
A colleague sent me an interesting article about hidden instructions in Word documents. These are later interpreted by CoPilot in Word and transferred into new documents.
- https://enklypesalt.com/posts/context-collapse-part3-ai-worming-through-word/

---
Another colleague sent me another article, covering an attack on EV charging infrastructure. There are significant security flaws in the charging stations, and according to the authors the vulnerabilities found can be applied to other manufacturers in a similar form. The blog has a variety of posts on charging infrastructure, so it's worth having a browse.
- https://www.saiflow.com/blog/the-hidden-ccs2-attack-surface-on-ev-chargers

---
Shubham Shah takes a look at the performance of current frontier models. More philosophical than technical.
- https://shubs.io/frontier-class-vulnerabilities-it-gets-worse-before-it-maybe-gets-better/

---
0xdbgman takes a technical dive into the CrowdStrike Falcon Sensor, reversing the software to get a closer look at how its detection works.
- https://0xdbgman.github.io/posts/inside-the-falcon-how-crowdstrike-catches-you/

---
Yarix looked at the increase in data leaks involving French data in Q1 2026.
- https://labs.yarix.com/2026/07/french-attack-surge-unpacking-the-drivers-behind-the-spike-in-data-leak-claims-against-french-targets/

---
Andy Gill gives an insight into Azure Web PubSub and how it can be used for C2 and living-off-the-land communication, including a PoC C2.
- https://blog.zsec.uk/brokerline-pubsubpwn/

---
We've covered ClickFix quite a few times here now, as it's currently the dominant phishing vector. JumpSec has now taken a look at a North Korean phishing kit called BlueNoroff. The kit mimics Teams or Zoom meetings, and a configuration error exposed source code that JumpSec then examined more closely.
- https://www.jumpsec.com/guides/inside-a-dprk-bluenoroff-clickfix-kit/

---
David Carliez has written a proof of concept for LPE in Windows AppResolver, allowing escalation from local admin to System. Microsoft patched it in 26200.8875 and the PoC came out of reviewing that security update.
- https://davidcarliez.github.io/blog/windows-appresolver-lpe-to-system/

---
A little less technical than usual, but an interesting problem. A flaw in the RNG led to a significant amount of crypto being drained from wallets, totaling ~~1196 addresses, 1082.65 BTC~~ 4585 addresses, 1367.05 BTC so far.
- https://blog.coinkite.com/coldcard-mk3-seed-generation-warning/
- [Twitter / X link] https://x.com/glxyresearch/status/2083181683067506899
- [Twitter / X link] https://x.com/glxyresearch/status/2083623500183421043

---
Huntress has once again delivered a deep dive into a malware sample. Set aside some time if you want to read the full article. A program disguises itself as a Claude installer for macOS. My personal take is that well-maintained package repositories would significantly reduce the risk of compromise, though supply chain attacks remain a real threat regardless.
- https://www.huntress.com/blog/macsync-stealer-rat-reverse-engineering

---
Neswin gives what I think is a very accessible look at how key components of compute systems are structured and how they work together. I'll admit I only read parts of it, but as an entry point for someone wanting to get into the topic I thought it was really good.
- https://grit8086.github.io/posts/computer-architecture/

---

Read you next week.

