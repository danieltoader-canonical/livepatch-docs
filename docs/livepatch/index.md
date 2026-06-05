---
myst:
  html_meta:
    description: "Livepatch client documentation home."
---


(client-index)=

# Client

Livepatch client is the software running on a machine, that periodically checks for the availability of new patches. Once new patches are available, they are downloaded, verified and applied to the current kernel.

## In this documentation

| | |
| ----------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| [How-to guides](/livepatch/how-to-guides/index.md) </br> Step-by-step guides covering key operations and common tasks |
| [Explanation](/livepatch/explanation/index.md) </br> Discussion and clarification of key topics | |
[Reference](/livepatch/reference/index.md) </br> Technical information - specifications, APIs, architecture |

## Getting support

Canonical customers can receive support and report issues on the Ubuntu Livepatch service, Livepatch client or Livepatch on-prem, on Canonical's [support portal](https://portal.support.canonical.com/).

The projects maintain bug trackers at

- [Livepatch client bug tracker](https://bugs.launchpad.net/canonical-livepatch-client/+filebug)
- [Livepatch on-prem bugtracker](https://bugs.launchpad.net/livepatch-onprem/+filebug)

```{toctree}
:titlesonly:
:maxdepth: 2
:glob:
:hidden:

how-to-guides/index
reference/index
explanation/index
```
