---
date: '2026-02-12T14:48:33Z'
draft: false
title: 'Newsletter 2026-02-12'
toc: false
tags: [newsletter articles blogs]
---

Back again with some interesting articles that came across my way during the last few days.

--- 
Stan Ghouls relies on spear phishing to land their targets. The writeup on initial access is very detailed. They're also recycling Mirai here.
https://securelist.com/stan-ghouls-in-uzbekistan/118738/

---

I'm not exactly sure when this article was written (or if that's just the modification date), but the author exploits a race condition to bypass protections against credential dumping.
https://otter.gitbook.io/red-teaming/articles/windows-of-opportunity-exploiting-race-conditions-in-seclogon-to-dump-lsass

---
Yarix introduces their tool Doppelganger in this article, which they use to disable PPL by leveraging a vulnerable driver and clone the lsass process to save the dump obfuscated.
https://labs.yarix.com/2025/06/doppelganger-an-advanced-lsass-dumper-with-process-cloning/

---
Also written a few days ago, but a colleague brought it up in conversation and it fits nicely into the credentials theme right now. SpecterOps presents a technique to leverage Credential Guard for credential dumping. It produces an NTLMv1 hash, even when NTLMv1 is disabled. So far, I've always needed an SPN when trying `/mode:self`, but this is a really interesting technique.
https://specterops.io/blog/2025/10/23/catching-credential-guard-off-guard/

---
A write-up on Pulsar RAT. Had to read it a few times since there was quite a bit to it. But I found it worth reading.
https://www.pointwild.com/threat-intelligence/when-malware-talks-back/

---
XLL as an initial vector was new to me. I stumbled across an article this week that made me aware of it. That one had a very AI-flavored feel to it, so I went with an article from 2022 instead.
https://blog.talosintelligence.com/xlling-in-excel-malicious-add-ins/
And a repo to go with it.
https://github.com/Octoberfest7/XLL_Phishing

--- 

Read you next time.
