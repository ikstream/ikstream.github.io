---
date: '2026-10-27T04:30:14Z'
draft: false
title: 'Newsletter 2026-10-27'
toc: false
tags: [newsletter articles blogs]
---

Another Week, another round. 

This time the theme seems to be threat actor writeups, with a few outliers like SpecterOps and their article on NTLM relaying despite LDAP and SMB signing.

---
Trail of Bits looked at the integrity checks of several package managers and found that some could use a few more checks to improve security. Since we have seen a lot of supply chain attacks this year, anything that reduces the attack surface is helpful.
- https://blog.trailofbits.com/2026/10/14/package-managers-have-an-integrity-problem/

---
LevelBlue took a look at Wazza and the waves of its device code phishing campaign, and found that it has been active since at least July 2026. Initial access happens through phishing emails from compromised business accounts and is geared toward things like invoices and contracts.
- https://www.levelblue.com/blogs/spiderlabs-blog/inside-wazza-a-newly-observed-device-code-phishing-kit-targeting-microsoft-365-accounts

---
Straiker looks at CyberCartel and their AI attack framework Carliy0s, which they use to go after the banking sector in South America in particular. The agents are allowed to use Burp through several integrations and MCPs, among other things. An old acquaintance, HexstrikeAI, is also in use, even though its public GitHub repo hasn't seen any love in a long time.
- https://www.straiker.ai/blog/inside-carliy0s-how-cybercartel-used-multiple-ai-models-to-attack-latin-american-banks

---
Acronis looked at one of the top ransomware groups of this year. The Gentlemen is a Russian-speaking ransomware-as-a-service (RaaS) group that has been active since mid 2025 and lets its affiliates keep up to 90% of the ransom. The analysis mainly puts the software they use under the microscope.
- https://www.acronis.com/en/tru/posts/the-gentlemen-a-closer-look-at-a-not-so-gentle-ransomware-as-a-service-operation/

---
Continuing from last week, this week we get the Windows threat and malware landscape report for Q3 from Pointwild.
- https://www.pointwild.com/threat-intelligence/q3-2026-windows-cyber-threat-malware-landscape-report/

---
Securelist discovered a new Lazarus attack wave in January and named it Operation Flashhole. It relied on spearphishing and waterholing attacks. The analysis has now been published.
- https://securelist.com/lazarus-operation-flashhole/121541/

---
Cyble examined a whole batch of new domains and found 35 sites (out of 22,306 that they classified as AI created) that leak secrets. These include OpenAI keys, DB secrets, and Stripe private keys.
- https://cyble.com/blog/secret-exposure-across-ai-built-websites/

---
Group-IB took a look at the commercial SiriusQT RAT. The mechanism used to verify licenses also came into focus.
- https://www.group-ib.com/blog/siriusqt-rat-hvnc-stealer/

---
Jev as a classifier recently came up and brought ML basics back into the discussion. Datadog checked what you can do with it and how to get Jev to misclassify things.
- https://securitylabs.datadoghq.com/articles/jev-as-a-judge-how-counterfeit-policy-steers-jev/

---
SpecterOps published an article describing how to relay foreign NTLM session information over a valid LDAP connection to switch context, even with LDAP and SMB signing active. This was fixed in the October 2026 patch, but every DC that doesn't have this patch is vulnerable.
- https://specterops.io/blog/2026/10/23/ldap-signing-bypass-ntlm-relay/

---

Read you next week.
