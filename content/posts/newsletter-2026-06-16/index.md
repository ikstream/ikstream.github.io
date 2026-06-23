---
date: '2026-06-16T04:26:29Z'
draft: false
title: 'Newsletter 2026-06-16'
toc: false
tags: [newsletter articles blogs]
---

Another week with new articles.

---

Zoltan Madarassy and Alex Brown wrote another article for Elttam on what to watch out for in Go reviews.
- https://www.elttam.com/blog/golang-code-review-notes-ii

---

Matthew Green looked at the reasoning blocks in LLMs and was able to derive secrets from the systems (with a bit of luck). Additionally, neither Claude nor GPT5x seem to use system prompts in API mode.
- https://blog.cryptographyengineering.com/2026/05/29/fooling-around-with-encrypted-reasoning-blobs/

---

A comprehensive write-up of CVE-2026-23111. This is a use-after-free vulnerability caused by incorrect use of the exclamation mark.
- https://blog.exodusintel.com/2026/06/08/off-by-exploiting-a-use-after-free-in-the-linux-kernel/

---

StarLabs discovered a problem under Ubuntu. Ubuntu apparently automatically adds new accounts to the `lxd` group, which has root-like privileges, even if lxd is not installed. At the same time, the `lxd-installer` socket can be used to install lxd without root privileges as long as you're in the `lxd` group. The whole thing is classified as intentional and `wont-fix`.
- https://starlabs.sg/blog/2026/06-old-wine-in-a-new-bottle-a-decade-old-lxd-group-root-re-armed/

---

MS-SQL 2025 apparently comes with new AI features and SpecterOps wrote up what they did with them.
- https://specterops.io/blog/2026/06/10/oops-i-weaponized-the-database-abusing-ai-features-in-mssql-2025/

---

Device code phishing has seemingly increased considerably recently. LevelBlue provides an overview.
- https://www.levelblue.com/blogs/spiderlabs-blog/the-device-code-phishing-tsunami-what-were-seeing-in-the-wild

---

Nihanshu Katkar wrote a complete initial access chain for Point Wild, from the first click to the execution of the final payload. The entry point is an email attachment.
- https://www.pointwild.com/threat-intelligence/from-phishing-email-to-process-injection-inside-a-multi-stage-agent-tesla-infection-chain/

---

A Microsoft PyPi repository has also been compromised by TeamPCP.
- https://gurucul.com/blog/teampcp-compromises-microsofts-durabletask-pypi-package-to-deploy-multi-stage-credential-theft-malware/

---

The company Sygnia shows in their blog post why it makes sense not to connect critical infrastructure to the internal network if possible. Chinese TA Velvet Ant systematically spread across internal, internet-disconnected systems and networks for over 10 years. Modified standard tools were used in the process. For example, an `scp` variant was used that could disable SELinux when executed under root. OpenSSH server and PAM modules were also modified. Very much worth reading.
- https://www.sygnia.co/blog/operation-highland-velvet-ant/

---

There are already first analyses of the attack on Arch's AUR.
- https://ioctl.fail/preliminary-analysis-of-aur-malware/

---

Read you next time.

