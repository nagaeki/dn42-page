---
title: Home
date: 2023-02-13T14:42+08:00
---

# Peering with EKI-Network

This page will provide basic information to get started on peering with EKI-Network in DN42.

Chinese version of this page will be coming sooooon.

# What is DN42?

> dn42 is a big dynamic VPN, which employs Internet technologies (BGP, whois database, DNS, etc). Participants connect to each other using network tunnels (GRE, OpenVPN, WireGuard, Tinc, IPsec) and exchange routes thanks to the Border Gateway Protocol.

Anyway, DN42 is ***fun***!

Source: [DN42 Homepage](https://dn42.eu/home)

# Peering Requirements

Though new peerings are always welcome, there are a few requirements in place to protect my own network as well as the rest of DN42.

- You must support IPv6. (Hey, it's 2023.)
- You must implement ROA checks.
- Contact information in the registry should be able to reply in a reasonable amount of time. If there ever happens to be a problem, you should be reachable to resolve it.
- Latency to your nodes should be reasonable, and connections should be made with the geographically closest node if it does not contradict the "best latency" quote. (e.g. If I have nodes in Las Vegas and New York City, and you're connecting from San Jose, you shouldn't connect to my NYC node.)

# BGP extensions

- MultiProtocol BGP: Supported and preferred. (Default: ON)
- Extended Next Hop: Supported and preferred. (Default: ON for IPv4)
- Extended Messages: Supported and preferred. (Default: ON)

