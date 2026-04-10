# Computer Fundamentals

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
What's actually inside a computer and how it handles data — necessary 
foundation before touching any low-level exploits.

- **Binary & data representation** — Everything is ultimately 0s and 1s. 
  Text uses ASCII/Unicode encoding. Understanding hex is essential for 
  reading memory dumps and shellcode.
- **CPU** — Fetches, decodes, executes instructions. Registers are tiny 
  ultra-fast storage inside the CPU. Relevant for understanding buffer 
  overflows later.
- **Memory (RAM vs storage)** — RAM is volatile, fast, temporary. 
  Storage is persistent. The distinction matters for forensics and 
  malware analysis.
- **File systems** — NTFS (Windows), ext4 (Linux). Files have permissions 
  (read/write/execute) — misconfigured permissions are a common vulnerability.
- **Cloud** — IaaS / PaaS / SaaS models. Shared responsibility: the cloud 
  provider secures the infrastructure; you secure what runs on it.

**Key takeaway:** Hardware and OS concepts underpin every low-level attack. 
Skipping this would leave gaps when reaching exploit development later.
