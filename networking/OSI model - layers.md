---
tags: network
---

# OSI Model

The **Open Systems Interconnection** (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980.

The modern internet is not based on OSI, but on the simpler [[networking/tcp-udp|TCP/IP]] model. However, the OSI model is still widely used, as it helps visualize and communicate how networks operate and helps isolate and troubleshoot networking problems.

## 7 layers of OSI

1. Physical layer: Physical structure, Coax, Fiber, Wireless, Hubs, Repeaters
2. Data Link layer: Frames, Ethernet, PPP, Switch, Bridge
3. Network layer: Packets, IP, ICMP, IPSec, IGMP
4. Transport layer: End-to-end connections, TCP, UDP
5. Session layer: Sync & send to port, API's, sockets, WinSock
6. Presentation layer: Syntax layer, SSL, SSH, IMAP, FTP, MPEG, JPEG
7. Application layer: User interaction, HTTP, FTP, IRC, SSH, DNS