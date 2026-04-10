# Operating Systems Basics

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
How operating systems manage hardware and users — with focus on Windows 
and Linux since they dominate in professional environments.

**Linux:**
- Everything is a file. The filesystem starts at `/` (root).
- Key directories: `/etc` (config), `/var` (logs), `/home` (user files), 
  `/tmp` (temporary — often writable, abused by attackers).
- Essential commands: `ls`, `cd`, `cat`, `grep`, `find`, `chmod`, `sudo`.
- Users and permissions: every file has owner/group/other permissions 
  (rwx). SUID bit allows running a file as its owner — a common privilege 
  escalation vector.

**Windows:**
- NTFS permissions, Active Directory for managing users in organisations.
- Registry stores system and application config — malware often persists 
  here via run keys.
- PowerShell is the modern admin tool and also heavily abused in attacks.

**Key takeaway:** Most real-world targets run Linux servers or Windows 
enterprise environments. Fluency in both CLIs is non-negotiable.
