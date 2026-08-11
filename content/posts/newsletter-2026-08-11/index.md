---
date: '2026-08-11T06:59:40Z'
draft: false
title: 'Newsletter 2026-08-11'
toc: false
tags: [newsletter articles blogs]
---

Another week another round:

---

A pretty interesting deep dive into browser fingerprinting from the Web Scraping Club.
- https://substack.thewebscraping.club/p/browser-fingerprinting-deep-dive

---
Cyble has published their ransomware threat report for the first half of 2026. Germany and France are leading the statistics on cases in Europe.
- https://cyble.com/blog/ransomware-threats-in-europe-h1-2026/

---
SpecterOps has published a four-part series on WSUS, including a Ludus lab and new tooling. An important prerequisite here is that the WSUS server uses an external SQL database that is not running on the same server.
- https://specterops.io/blog/2026/08/05/turning-enterprise-update-servers-into-backdoor-factories-part-1/
- https://specterops.io/blog/2026/08/05/turning-enterprise-update-servers-into-backdoor-factories-part-2/
- https://specterops.io/blog/2026/08/05/built-a-wsus-ludus-lab/
- https://specterops.io/blog/2026/08/05/weaponizing-windows-updates-with-notwsuspicious/

---
A threat actor was observed attempting to tap into various available LLM sources in their code. The question is whether the next step will be training their own models.
- https://www.genians.co.kr/en/blog/threat_intelligence/kimsuky_ai_llm

---
Apple has closed a critical vulnerability and "incidentally" took out a second one at the same time. Affected are devices with screen sharing enabled, with around 40k of them reachable on the internet at the time of the article. So if Apple devices show up in the next engagement, it's worth looking out for CVE-2026-43760 (post auth) and CVE-2026-65400 (pre auth).
- https://blog.calif.io/p/no-country-for-old-passwords

---
Exploitpack describes GDT hijacking under VBS/HVCI, exploiting a kernel read/write vulnerability to temporarily clone the Global Descriptor Table into a free memory region and insert a crafted call gate into it. This allows an attacker to execute custom kernel commands, such as a token swap for admin privileges, via a 32-bit helper process, and then clean up all traces afterwards.
- https://www.exploitpack.com/blogs/news/gdt-table-hijacking-and-fwa

---
The article covers three Active Directory issues that in combination can lead to full domain takeover. Improper handling of invisible Unicode characters in Active Directory creates identity conflicts during name resolution on domain controllers. The KerberLoss vulnerability (CVE-2026-25177) allows attackers to disrupt the Kerberos protocol and force a downgrade to insecure authentication methods. ResetNightmare (CVE-2026-27912) then lets unprivileged users impersonate highly privileged accounts, immediately handing over full control of the entire domain.
- https://www.semperis.com/blog/identity-crisis-novel-vulnerabilities-leading-to-kerberos-downgrade-dos-and-full-domain-takeover/

---
Palo Alto's Unit42 has analyzed an npm worm that grabs every token and key it can get its hands on. Since the targeting is specifically aimed at developers and AI development tooling, it sounds a lot like we might be gearing up for the next big wave of supply chain attacks.
- https://unit42.paloaltonetworks.com/chaindrop-npm-worm-analysis/

---
Hunt.io observed an attack using a Hermes agent running in YOLO mode against Thailand's Ministry of Finance, wrote everything down and mapped it to MITRE.
- https://hunt.io/blog/thailand-ministry-finance-targeted-with-hermes-ai-agent

---
Something a bit more on the playful side to wrap things up. John/t0asts did a very thorough teardown of malware being distributed through cheats for Meccha Chameleon.
- https://t0asts.com/meccha-chameleon

---

Read you next week. 
