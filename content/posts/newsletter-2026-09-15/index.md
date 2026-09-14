---
date: '2026-09-14T23:13:26Z'
draft: false
title: 'Newsletter 2026-09-14'
toc: false
tags: [newsletter articles blogs]
---

Another week, another round.

---

A small missing check with devastating consequences. A missing signature verification led to roughly $1.1 million in crypto being stolen in total.
- https://blog.verichains.io/p/rain-hack-analysis-ed25519-signature

---
Acronis has published a very detailed analysis of a multi-stage infection chain. The final payload appears to be the SparkRAT malware, though the Acronis team stops short of direct attribution due to a lack of sufficient evidence.
- https://www.acronis.com/en/tru/posts/cambodia-focused-cluster-uses-multi-stage-infection-chain-with-localized-lures/

---
Rapid7 analyzed a curl-based RAT targeting South Korean entities and attributed it to North Korean APTs. The core components are an SSH keylogger and a backdoor placed in HA-Proxy, used to silently manipulate network traffic, intercept credentials, and inject scripts into websites.
- https://www.rapid7.com/blog/post/tr-dprk-apts-ted-backdoor-curlrat-target-south-korean-media-automotive-sectors/

---
MDSec writes about how they have approached adversarial simulations over the past two years, with a particular focus on ServiceNow, which they exploited time and again, including some surprisingly low-profile permissions.
- https://www.mdsec.co.uk/2026/08/when-it-snows-it-pours-anatomy-of-a-servicenow-red-team/

Fitting alongside that one:
- https://blog.tw1sm.io/p/cleartext-credential-recovery-in

---
Greynoise spotted an attack against a vulnerable PaperCut version and wrote up the attacker's approach and tooling. According to Greynoise, the campaign used hundreds of AI-assisted agents to compromise 440 servers across various countries in a very short time, in some cases achieving domain admin rights within minutes. Always interesting to see what kind of tooling gets used.
- https://www.greynoise.io/blog/ai-orchestrated-campaign-against-papercut-ng-mf

---
SpecterOps introduces a new tool designed to make complex OAuth workflows easier to follow during testing. Data can be imported from Burp, DevTools, or mitmproxy and is then visualized in a web GUI. Looks interesting.
- https://specterops.io/blog/2026/09/08/token-analysis-and-tracking-system-tats/

---
MatheuZ explains an approach to fileless ELF execution in his blog, using the keyring system to download the payload and place it directly in kernel memory. Source code included.
- https://matheuzsecurity.github.io/hacking/linux-kernel-fileless-exec/

---
Point Wild has put together another very goog writeup on a RAT.
- https://www.pointwild.com/threat-intelligence/asyncrat-delivered-via-autoit-full-chain-analysis/

---
TrustedSec's latest post, which will become a series, covers the different types of AWS credentials and how they can be leveraged.
- https://trustedsec.com/blog/so-you-found-aws-access-keys-part-1

---
Outflank presents new tooling for NetNTLM cracking to make the process even more efficient and faster.
- https://www.outflank.nl/blog/2026/09/08/netntlmv1-is-dead-long-live-netntlmv1/

---

Read you next week.
