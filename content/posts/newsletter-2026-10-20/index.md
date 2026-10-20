---
date: '2026-10-20T06:43:05Z'
draft: false
title: 'Newsletter 2026-10-20'
toc: false
tags: [newsletter articles blogs]
---

Another Week, another round. 
Quite a few mobile-related articles sneaked into my feed this time, by coincidence.

---
Zscaler, among others, observed the use of the LLM pentesting framework ARTEX to attack South Korean targets.
- https://www.zscaler.com/blogs/security-research/threat-actor-abuses-agentic-ai-pentesting-framework-target-south-korean

---
Point Wild has presented the Android malware trend report for Q3. It looks like the landscape has evolved and more AI is being used as well.
- https://www.pointwild.com/threat-intelligence/android-q3-2026-malware-trend-report/

---
Starlabs analyzed the YuanKong Android RAT. It uses WebSockets for C2 communication, as well as certificates that stay the same across the whole family. According to Starlabs, this allows other samples to be attributed to the same family quite reliably.
- https://starlabs.sg/blog/2026/10-yuankong-rat-the-android-remote-control-service-that-stamps-its-operators-names-into-every-build/

---
Black Lantern Security found an IDOR CVE in ServiceNow. The simplicity is almost alarming.
- https://blog.blacklanternsecurity.com/p/cve-2026-79957-insecure-direct-object

---
Varik Matevosyan built a setup to learn about the new XNU kernel protections. From it he created a few exercises and shares them on his blog, using a vphone VM running iOS.
- https://varik.dev/blog/xnu/xnusp-xnu-learning-lab

In another post he also describes how he got into iOS vulnerability research.
- https://varik.dev/blog/getting-into-apple-security-bounty

---
Quentin Kaiser shows that Broadcom has been using a vulnerable WPS implementation for a long time, exposing a large number of devices to a possible RCE. Broadcom sees this as a legacy problem and is not requesting a CVE for it, but the high number of affected devices paints a rather different picture. He has published YARA rules for detection.
- https://quentinkaiser.be/security/2026/10/16/one-parser-two-bugs/

---
NVISO took a look at the Digispark as a malicious HID and carried out a forensic investigation as an example.
- https://blog.nviso.eu/2026/10/16/keystrokes-in-disguise-forensic-analysis-of-a-digispark-hid-device/

---
Anthropic managed to determine the seed of the ECDSA curve, which also clears up various myths about its origin.
- https://www.anthropic.com/research/ecdsa-curve-origins

---
Starlabs looked at more Android RATs. Japanese apps from well-known brands are faked, containing an inconspicuous dropper that then loads the actual WebSocket-based malware.
- https://starlabs.sg/blog/2026/10-two-hawks-in-a-pod-one-android-rat-behind-a-flock-of-fake-japanese-brands/

---
Matthew Alt from Voidstar Sec gives a fairly comprehensive walkthrough of how to read live trace data from an STM32, which can also be applied to other devices. As an example he used the Xbox One controller.
- https://voidstarsec.com/blog/arm-tracing-etm-itm

---
BLS looks back on the year and focuses on Microsoft's NTFS feature for creating short names of files. In combination with IIS, it keeps leading to serious security problems.
- https://blog.blacklanternsecurity.com/p/iis-shortname-enumeration-in-the

---

Read you next week.
