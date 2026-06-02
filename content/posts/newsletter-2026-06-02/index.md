---
date: '2026-06-02T04:07:20Z'
draft: false
title: 'Newsletter 2026-06-02'
toc: false
tags: [newsletter articles blogs]
---

Again a lot of interesting articles, at least in my opinion.

---

Interesting approach to bridge the air-gap using audio signals to get malware onto a target system when USB ports and the like are disabled. cocomelonc kicks off in the first blog post [1] with the transmitter side and some basics. The second part [2] then deals with the receiver under Linux.
1. https://cocomelonc.github.io/malware/2026/05/24/malware-tricks-56.html
2. https://cocomelonc.github.io/malware/2026/05/26/malware-tricks-57.html

---

Something a bit different for a change. nand2mario from Small Things Retro has set about pouring the 80386 (for those old enough to remember) into an FPGA based on the original microcode. Cool project.
- https://nand2mario.github.io/posts/2026/z386/

---

Another project I didn't know about before. There's the OpenTrafficMap and matching boards that can help collect data for it. Maybe it's quite interesting to see what your own onboard unit communicates or the traffic infrastructure around you.
- https://pretalx.linuxtage.at/media/glt26/submissions/SRQ3M9/resources/C-ITS__Mit_einem_ESP32_Ampeln_2eRw7Fx.pdf
- https://www.cnx-software.com/2026/05/24/opentrafficmap-esp32-c5-c-its-receiver-board-can-help-improve-traffic-efficiency-using-802-11p-v2x-communication/
- https://www.cnx-software.com/2026/05/25/monitor-live-traffic-from-v2x-signals-with-v2x2map-open-source-android-app-and-an-esp32-c5-development-board/

---

Elastic broke down 2FA phishing as it's used in Tycoon 2FA. They also explain how they nailed down detection of the attacks. Very good deep dive.
- https://www.elastic.co/security-labs/tycoon-2fa-aitm-detection-engineering

---

Talos found multiple buffer overflow-based vulnerabilities in MediaArea's open source library MediaInfoLib. The associated four write-ups are linked in the main article.
- https://blog.talosintelligence.com/mediaarea-heap-based-buffer-overflow-vulnerabilities/

---

Paul Newton took a closer look at Device Code Lab, a device code phishing platform, and broke it down. Various techniques are being used. Among other things, the EntraID role is extracted to prioritize higher-value accounts.
- https://newtonpaul.com/blog/device-code-lab-post-exploit/

---

Anyone who feels like diving into medical standards and seeing what's been going on in DICOM over the last few years and what might still be possible should definitely check out Talos's PDF.
- [PDF] https://storage.ghost.io/c/af/a0/afa04ee3-414f-4481-8d23-7e7c146f192e/content/files/2026/05/DICOM2026-2.pdf

---

Silent Push looked at the approach of threat actor "Drivesurge". ClickFix and FakeUpdate attacks are predominantly being used here.
- https://www.silentpush.com/blog/drivesurge/

---

Calif took a closer look at FreeBSD with the help of AI and published three CVEs. The respective write-ups are linked in the article and very comprehensive.
- https://blog.calif.io/p/an-ai-audit-of-freebsd

---

I actually intended not to include supply chain attacks anymore because there are simply too many, but now RedHat got hit and that seemed important to me.
- https://www.reversinglabs.com/blog/31-red-hat-cloud-service-npm-packages-backdoored-in-72-seconds
- https://socket.dev/blog/mini-shai-hulud-campaign-hits-red-hat-cloud-services-npm-packages?utm_medium=feed

---

Andy Gill shows with his malware-less red teaming course how to operate less noticeably in customer networks. But now he's going even deeper in search of a baseline. To do this, he looks at what's being sent to MDI and MDE among other things using KQL.
- https://blog.zsec.uk/baselining-windows/

---

Read you next week!

