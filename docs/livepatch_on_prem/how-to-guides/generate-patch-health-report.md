---
myst:
  html_meta:
    description: "How to generate patch health report with Livepatch on-prem."
---

(on-prem-server-how-to-guides-generate-patch-health-report)=

# Generate patch health report

To generate a report of how many machines applied (or failed to apply) a specific patch, run:

```
livepatch-admin report patch-health <tier> <patch-version>
```
