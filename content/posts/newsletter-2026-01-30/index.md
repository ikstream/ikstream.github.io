---
date: '2026-01-30T19:41:32Z'
draft: false
title: 'Newsletter 2026-01-30'
toc: false
tldr: News From Week 5 
tags: [newsletter articles blogs]
---

During a week I usually read some articles on varying topics. So why not provide them here as well with a short summary in hope someone finds this usefull.


---
I can’t say I understood everything, but I always find this kind of research fascinating. In the blog, Connor McGarr managed to send a “stop trace” to ETW using an undocumented security trace flag and they provide a pretty deep dive into it.
- https://connormcgarr.github.io/securitytrace-etw-ppl/

---
Robin Bradshaw wrote about exposed secrets found in the Wix MSI installer. He starts by taking apart the installer and decompiling the included .NET DLLs. As he notes, MSI installer could make for quite an interesting target for analysis.
- https://en4rab.github.io/posts/WiX-custom-actions/


---
The next article also deals with DLLs, this time focusing on hijacking them in writable SYSTEM paths. The author sums it up perfectly:
“The combination of DLL hijacking in audiodg.exe and the ability to restart the process without a reboot results in a practical privilege escalation and persistence vector if prerequirements are met.”
- https://medium.com/@S.1.l.k.y/abusing-windows-audio-for-local-privilege-escalation-1d59440116cb


---
Depth Security takes another look at NTLM reflection, this time showing how it can still work if the June 2025 Windows Security Update (including CVE-2025-33073) hasn’t been installed. They go into the full process in plenty of detail.
- https://www.depthsecurity.com/blog/using-ntlm-reflection-to-own-active-directory/


---
This article is a bit older, but it took me some time to actually read it. 
Cloudflare noticed several BGP leaks in Venezuela just days before the U.S. attack. They do say, though, that it might just be a coincidence or the result of configuration errors.
- https://blog.cloudflare.com/bgp-route-leak-venezuela/


---
Mandiant released a massive collection of NTLMv1 hashes as rainbow tables and also explained how to use them.
- https://cloud.google.com/blog/topics/threat-intelligence/net-ntlmv1-deprecation-rainbow-tables/

If you’re curious what rainbow tables actually are and how they work, here’s a great primer:
- https://kestas.kuliukas.com/RainbowTables/


---
That's it for the first one, read you next time 

