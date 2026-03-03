---
date: '2026-03-03T09:32:02Z'
draft: false
title: 'Newsletter 2026-03-03'
toc: false
tags: [newsletter articles blogs]
---

Another week with multiple very interesting articles.

--- 
Graham Helton presents an RCE in Kubernetes on his blog. It requires GET permission and WebSocket communication.
The report was closed as `Won't fix (Intended behavior)`, so it's worth keeping this in the back of your mind.
- https://grahamhelton.com/blog/nodes-proxy-rce

---
Patrick Binder introduces his tool apimspray, which uses Azure API Management (APIM) to conduct EntraID password spraying via Microsoft's own IP addresses. The whole thing is difficult to detect, but he also explains that EntraID Identity Protection can help with detection through its alerts. Besides the usual MFA everywhere, he also gives additional recommendations to better secure accounts against this attack and tool.
- https://patrickbinder.medium.com/entra-id-password-spraying-using-apim-as-ip-rotating-mechanism-3620861dd66a


---
Pretty similar to one TPM project I was involved in, just with a bit more soldering and apparently a CVE came out of it.
- https://www.cyloq.se/en/research/cve-2026-0714-tpm-sniffing-luks-keys-on-an-embedded-device

---
Discovered a bit late but still interesting. The write-up on Headphone Jacking from December last year.
- https://insinuator.net/2025/12/bluetooth-headphone-jacking-full-disclosure-of-airoha-race-vulnerabilities/

---
Lee Robinson from SpecterOps presents some tools for EntraID testing, including his recently released one. He also explains Conditional Access Policies in a pretty beginner-friendly way.
- https://specterops.io/blog/2026/02/17/stop-the-cap-making-entra-id-conditional-access-make-sense-offline/

---
I got two articles sent to me by a friend [4elta](https://github.com/4elta) that I also found pretty interesting.
Mozilla introduces the setHTML function in their blog, which is supposed to replace innerHTML among other things and includes sanitization directly to provide better protection against XSS.
- https://hacks.mozilla.org/2026/02/goodbye-innerhtml-hello-sethtml-stronger-xss-protection-in-firefox-148/


Another attack on client isolation in WPA2 and this time also WPA3 networks that don't use EAP. But since companies often enough rely on PSK, it's definitely an interesting attack. A possible fix is MacSec (IEEE 802.1AE).
- [PDF] https://www.ndss-symposium.org/wp-content/uploads/2026-f1282-paper.pdf

--- 

Read you next time

