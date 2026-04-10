# Network Fundamentals

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
How computers find and communicate with each other, and where networks break.

- **IP & MAC addresses** — IP is logical (changes), MAC is physical (hardcoded).
  ARP maps between them — and ARP spoofing exploits this to intercept traffic.
- **LAN topologies** — Star (most common, central switch), Bus (legacy, 
  one cable), Ring (loop). Star dominates modern networks.
- **OSI Model** — 7-layer framework: Physical → Data Link → Network → 
  Transport → Session → Presentation → Application. Every network attack 
  targets a specific layer.
- **Packets & Frames** — Data is broken into chunks for transmission. 
  TCP adds reliability (handshake, acknowledgment); UDP is faster but 
  unreliable (used for streaming, DNS).
- **Extending networks** — Firewalls filter traffic by rules. VPNs create 
  encrypted tunnels. Port forwarding exposes internal services externally.

**Key takeaway:** You cannot understand attacks like MITM, packet sniffing, 
or port scanning without knowing how networks fundamentally work.
