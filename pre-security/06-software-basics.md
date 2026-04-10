# Software Basics

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
How software is built and how computers execute it — foundation for 
understanding how software can be exploited.

- **How code runs** — Source code → compiled to machine code (C/C++) 
  or interpreted at runtime (Python, JS). Interpreted languages are easier 
  to read and modify; compiled is faster.
- **Python basics** — Variables, loops, functions, file I/O. Python is the 
  dominant language in security tooling — almost every exploit script, 
  automation tool, and CTF solution uses it.
- **JavaScript basics** — Runs in the browser. Relevant because XSS 
  (Cross-Site Scripting) injects malicious JS into pages to steal data.
- **SQL basics** — Structured Query Language for databases. 
  `SELECT * FROM users WHERE username='admin'` — SQL injection manipulates 
  these queries by injecting code into input fields.

**Key takeaway:** SQL injection and XSS are consistently in the OWASP Top 10 
most critical web vulnerabilities. Understanding the underlying languages is 
what makes those attacks make sense.
