---
tags:
  - network-protocols/application-layer
---

## Border Gate Protocol
- Inter-AS routing protocol

In an AS, each router is either a **gateway router** or an **internal router**.
Pairs of routers exchange routing info over a [[TCP]] connection on port 179. This is called a **BGP connection**.
- **eBGP connection**: connects gateway routers in different ASs
- **iBGP connection**: connects routers within the same AS
- To propagate reachability information in BGP,  both iBGP and eBGP are used