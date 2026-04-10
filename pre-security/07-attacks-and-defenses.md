# Attacks and Defenses

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
A capstone overview of how real attacks are structured and how defenders 
respond — connecting everything from the previous sections.

- **CIA Triad** — Confidentiality (only authorised access), Integrity 
  (data isn't tampered with), Availability (systems stay up). Every 
  security decision maps to one of these three.
- **Common attack types:**
  - *Phishing* — Social engineering via email to steal credentials
  - *Malware* — Viruses, ransomware, trojans, spyware
  - *Man-in-the-Middle* — Intercepting traffic between two parties (exploits 
    weak ARP or DNS)
  - *SQL Injection / XSS* — Injecting malicious code via input fields
  - *DDoS* — Flooding a service to make it unavailable
- **Defense layers:**
  - Firewalls (filter traffic), IDS/IPS (detect/block anomalies), 
    antivirus, patch management, network segmentation
  - Security policies: least privilege, MFA, regular audits
- **Cryptography basics** — Symmetric (same key both ways, fast), 
  Asymmetric (public/private key pair, used in HTTPS/TLS). Hashing 
  for integrity checks (SHA-256, MD5 — MD5 now broken).

**Key takeaway:** Pre-Security complete. The foundation is in place — 
networking, web, OS, software, and attack theory. Next step: Jr Penetration 
Tester path where these concepts are applied hands-on against real targets.
