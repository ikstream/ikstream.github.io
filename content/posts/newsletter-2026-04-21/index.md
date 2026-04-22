---
date: '2026-04-21T10:05:50Z'
draft: false
title: 'Newsletter 2026-04-21'
toc: false
tags: [newsletter articles blogs]
---

Another week another round.

---
Level Blue addresses a phishing vector that only became interesting thanks to the wider adoption of MFA. Attackers try to get the victim or helpdesk to deactivate or reset the second factor.
- https://www.levelblue.com/blogs/spiderlabs-blog/why-attackers-are-bypassing-phishing-emails-and-targeting-identity-instead

--- 
Calif unleashed Codex on a TV with a compromised browser to see how Codex performs in such scenarios and can turn an existing shell into a root shell. I think it’s a good insight into the current state of things and it aligns with what I’ve seen so far.
- https://blog.calif.io/p/codex-hacked-a-samsung-tv

--- 
Adobe is always creative in finding out if software is installed. Might also be quite practical in other situations.
- https://www.osnews.com/story/144737/adobe-secretly-modifies-your-hosts-file-for-the-stupidest-reason/

---
A pretty nice cheat sheet for AI tests. Even though a lot changes quickly, you can recycle various things.
- https://itsbroken.ai/cheatsheet/

---
Securelist analyzes malware that specializes in banking data from targets in South America.
- https://securelist.com/janelarat-financial-threat-in-latin-america/119332/

---
A summary article on the three recently emerged GPU attacks. The author covers the various attacks affecting GPUs as well as the consequences for servers with shared GPU usage. In this case, the entire system can be compromised.
- https://blog.barrack.ai/gddrhammer-geforge-gpu-rowhammer-gddr6/

---
MITRE has released a new framework for fraud-related incidents. The deviations from other attacks are apparently significant enough to provide a more precise framework (MITRE Fight Fraud Framework™ (F3)).
- https://ctid.mitre.org/fraud#/

---
TrustedSec subjected smaller self-hosted models to a very specific benchmark. Certain Juice Shop elements came under scrutiny with 100 runs each, constant prompts and tooling. The results look very good in the narrow scope to support testing in certain areas. However, enough write-ups exist for Juice Shop to skew the results.
- https://trustedsec.com/blog/benchmarking-self-hosted-llms-for-offensive-security

---
Nils Emmerich writes about a recent pentest where, in addition to XSS and information disclosure, command injection in security cameras also came to light.
- https://insinuator.net/2026/04/disclosure-command-injection-in-geutebruck-cameras/

---
Talos took a closer look at the PowMix botnet’s approach and broke it down. They go deeper into the AMSI bypass method and C2 communication.
- https://blog.talosintelligence.com/powmix-botnet-targets-czech-workforce/

---
eBPF offers various interesting use cases. GitHub covers some of them and how it’s being used in the company.
- https://github.blog/engineering/infrastructure/how-github-uses-ebpf-to-improve-deployment-safety/

---
Palo Alto’s Unit42 goes deep into CVE-2023-33538 because they detected exploitation attempts. The CVE is already a bit older, but the article is worth reading. They also show that the public PoC doesn’t work in their test environment.
- https://origin-unit42.paloaltonetworks.com/exploitation-of-cve-2023-33538/

---
OxSecurity identified a problem in MCP that Anthropic sees more as a feature. Input is essentially processed unchecked, or rather the validation is left to the respective implementation. As expected, not many have sufficiently filtered user input.
- https://www.ox.security/blog/the-mother-of-all-ai-supply-chains-technical-deep-dive/

---
NIST is deprioritizing data enrichment of various CVEs (all those not appearing in KEV, in critical infrastructure, or US government-used software). Without CPE and without rating, CVEs aren’t really that useful anymore. Probably need to start collecting CVE data from different sources. Both the original report and an assessment.
- https://www.nist.gov/news-events/news/2026/04/nist-updates-nvd-operations-address-record-cve-growth
- https://socket.dev/blog/nist-officially-stops-enriching-most-cves

---

Read you next week.
