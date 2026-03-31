---
date: '2026-03-31T04:08:01Z'
draft: false
title: 'Newsletter 2026-03-31'
toc: false
tags: [newsletter articles blogs]
---

Looks like there was a lot going on last week, which resulted in quite a few links.

---
TrustedSec has started a blog series around detection. In my view, very much worth reading.

- [https://trustedsec.com/blog/building-a-detection-foundation-part-1-the-single-source-problem](https://trustedsec.com/blog/building-a-detection-foundation-part-1-the-single-source-problem)
- [https://trustedsec.com/blog/building-a-detection-foundation-part-2-windows-security-events](https://trustedsec.com/blog/building-a-detection-foundation-part-2-windows-security-events)
- [https://trustedsec.com/blog/building-a-detection-foundation-part-3-powershell-and-script-logging](https://trustedsec.com/blog/building-a-detection-foundation-part-3-powershell-and-script-logging)
- [https://trustedsec.com/blog/building-a-detection-foundation-part-4-sysmon](https://trustedsec.com/blog/building-a-detection-foundation-part-4-sysmon)


---
Corelan is back after 7 years without an article and starts with a very comprehensive session around WinDBG and WinDBGX.

- [https://www.corelan.be/index.php/2026/03/23/debugging-windbg-windbgx-fundamentals/](https://www.corelan.be/index.php/2026/03/23/debugging-windbg-windbgx-fundamentals/)


---
Level Blue Security wrote in their blog how the Azure ServiceBus can be used for C2 communication via WebSockets.

- [https://www.levelblue.com/blogs/spiderlabs-blog/azure-servicebus-websockets-as-a-c2-channel](https://www.levelblue.com/blogs/spiderlabs-blog/azure-servicebus-websockets-as-a-c2-channel)


---
Another week, another supply chain attack. Besides the renewed Trivy vulnerability, malicious code was also placed in litellm on PyPi. It's an infostealer.

- [https://www.stepsecurity.io/blog/litellm-credential-stealer-hidden-in-pypi-wheel](https://www.stepsecurity.io/blog/litellm-credential-stealer-hidden-in-pypi-wheel)
- [https://huskyhacks.io/posts/litellm-cred-stealer/](https://huskyhacks.io/posts/litellm-cred-stealer/)

---
And since it's going so "well" right now, there's also another attack on open source tools this week.

- [https://www.stepsecurity.io/blog/teampcp-plants-wav-steganography-credential-stealer-in-telnyx-pypi-package](https://www.stepsecurity.io/blog/teampcp-plants-wav-steganography-credential-stealer-in-telnyx-pypi-package)
- [https://www.ox.security/blog/teampcps-telnyx-windows-malware-technical-analysis/](https://www.ox.security/blog/teampcps-telnyx-windows-malware-technical-analysis/)


---
SearchlightCyber presents a tool that can help with reversing Java and C# programs by directly filtering out known library dependencies.

- [https://slcyber.io/research-center/hyoketsu-solving-the-vendor-dependency-problem-in-re](https://slcyber.io/research-center/hyoketsu-solving-the-vendor-dependency-problem-in-re)


---
Interesting phishing approach in which the browser displays a fullscreen windowi, simulating a windows login screen.

- [https://certitude.consulting/blog/en/abusing-modern-browser-features-for-phishing/](https://certitude.consulting/blog/en/abusing-modern-browser-features-for-phishing/)


---
In recent weeks there was a very effective attack on the medical device manufacturer Stryker (including defibrillators). The attacker is apparently another Iranian group. Via Intune, 200,000 clients were reset to factory settings. Another good reminder to implement 2FA/MFA and the four-eyes principle in as many places as possible.

- [https://slcyber.io/blog/the-warning-signs-were-there-how-credential-leaks-and-dark-web-activity-foreshadowed-the-stryker-breach/](https://slcyber.io/blog/the-warning-signs-were-there-how-credential-leaks-and-dark-web-activity-foreshadowed-the-stryker-breach/)
- [https://www.lumos.com/blog/stryker-hack][https://www.lumos.com/blog/stryker-hack]

---
Praetorian continues with its emperors and brings Aurelian, a multi-cloud testing tool (AWS (16 modules), Azure (5 modules), and GCP (4 modules)).

- [https://www.praetorian.com/blog/aurelian-cloud-security-tool/](https://www.praetorian.com/blog/aurelian-cloud-security-tool/)

---
There isn't really much to say about this. The term Watchtowr uses here really hits the nail on the head: "Remote Code Execution as a Service"

- [https://labs.watchtowr.com/sometimes-you-can-just-feel-the-security-in-the-design-junos-os-evolved-cve-2026-21902-rce/](https://labs.watchtowr.com/sometimes-you-can-just-feel-the-security-in-the-design-junos-os-evolved-cve-2026-21902-rce/)


--- 
Since everyone else loves to bash on Electron, BishopFox took a look at Tauri. XSS to RCE write-up.

- [https://bishopfox.com/blog/beyond-electron-attacking-alternative-desktop-application-frameworks](https://bishopfox.com/blog/beyond-electron-attacking-alternative-desktop-application-frameworks)

---
An interesting WAF deep dive. Keissy BOD presents a nice structure in the article to systematically work through the WAF, including further links. If you're dealing with WAFs, worth reading.

- [https://blog.quarkslab.com/in-waf-we-should-not-trust.html](https://blog.quarkslab.com/in-waf-we-should-not-trust.html)

---

Firas Chaib took on the game with probably the most leaked military secrets and added a "test drive" mode.

- [https://www.not1cyyy.com/articles/war-thunder-bypass](https://www.not1cyyy.com/articles/war-thunder-bypass)

---

Read you next time
