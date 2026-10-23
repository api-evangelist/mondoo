---
title: "Dirty Frag: Universal Linux LPE via Page Cache Writes"
url: "https://mondoo.com/blog/dirty-frag-universal-linux-lpe-via-page-cache-writes"
date: "2026-05-07"
author: "Christoph Hartmann"
feed_url: "https://mondoo.com/blog/rss.xml"
---
Dirty Frag chains two Linux kernel page-cache write vulnerabilities in the xfrm ESP and RxRPC subsystems to achieve deterministic root privileges on every major Linux distribution. Like Copy Fail and Dirty Pipe before it, the exploit requires no race conditions and no timing windows. A patch has been merged upstream, but no distribution has shipped updated packages yet.
