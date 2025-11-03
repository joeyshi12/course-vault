---
tags:
  - network-protocols/application-layer/dns
module: 4
lecture: 1
---

A **domain name** is an identification string that defines a realm
of administrative autonomy, authority or control within the internet

The DNS is a distributed database implemented in hierarchy of
many name servers
- Each server stores only a subset of the total DNS database (scalable)
- This hierarchy can be thought of as a search tree
- Application-layer protocol: host, routers, name servers to communicate to resolve names
- DNS servers cache [[Resource Records]]

## IP Address Search
- [[Iterative Search]]
- [[Recursive Search]]
