---
title: Services
date: 2023-02-13T15:47+08:00
---

As of now, the following services are provided by EKI-Network

# Recursive DNS

A recursive DNS, powered by [BIND 9](https://www.isc.org/bind/), is provided at Anycast addresses
- 172.23.181.11
- fdeb:53be:49b2:1111::1

It queries:
| Zone | Forwarder |
| --- | --- |
| neo. | 10.127.255.54; fd10:127:53:53::; |
| dn42. | 172.20.0.53; fd42:d42:d42:54::1; |
| 127.10.in-addr.arpa | 10.127.255.54; fd10:127:53:53::; |
| 7.2.1.0.0.1.d.f.ip6.arpa | 10.127.255.54; fd10:127:53:53::; |
| 10.in-addr.arpa | 172.20.0.53; fd42:d42:d42:54::1; |
| 20.172.in-addr.arpa | 172.20.0.53; fd42:d42:d42:54::1; |
| 21.172.in-addr.arpa | 172.20.0.53; fd42:d42:d42:54::1; |
| 22.172.in-addr.arpa | 172.20.0.53; fd42:d42:d42:54::1; |
| 23.172.in-addr.arpa | 172.20.0.53; fd42:d42:d42:54::1; |
| d.f.ip6.arpa | 172.20.0.53; fd42:d42:d42:54::1; |