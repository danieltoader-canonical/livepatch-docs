---
myst:
  html_meta:
    description: "Why are there missing patches? - learn about this topic in Livepatch client."
---

 
(client-explanation-why-are-there-missing-patches)=

# Why are there missing patches?

Livepatches are only produced for [supported kernels](/livepatch/reference/supported-kernels.md), and only for CVEs that require a Linux kernel modification to fix the problem (for example, a CPU bug may not have a kernel fix). Further, livepatches do not address security problems in Ubuntu software packages, or in third-party drivers that do not ship as part of the Linux kernel (i.e. NVIDIA GPU drivers).

Livepatch is intended to provide protection from security issues in *addition* to regular kernel security updates, so be sure to read and follow the security advisories published in Ubuntu Security Notifications ([USNs](https://ubuntu.com/security/notices)) for your kernel.
