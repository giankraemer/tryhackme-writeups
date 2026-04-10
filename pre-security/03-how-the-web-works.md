# How the Web Works

**Path:** Pre-Security | **Completed:** April 2026

## What I learned
The underlying mechanics of every website — what actually happens between 
typing a URL and seeing a page.

- **DNS** — Translates domain names to IP addresses. Hierarchy: root → 
  TLD (.com, .ch) → authoritative nameserver. Records: A (IPv4), AAAA (IPv6), 
  MX (mail), CNAME (alias).
- **HTTP/S** — The request-response protocol of the web. Methods: GET 
  (retrieve), POST (send data), PUT (update), DELETE. Status codes: 
  200 OK, 301 redirect, 404 not found, 500 server error.
- **Cookies** — Small files stored in the browser to maintain state (logins, 
  preferences). Critical for security — session hijacking steals cookies 
  to impersonate users.
- **How pages load** — Browser sends DNS lookup → gets IP → sends HTTP 
  request → server responds with HTML/CSS/JS → browser renders it.

**Key takeaway:** Web attacks (XSS, CSRF, session hijacking) all exploit 
these exact mechanics. Understanding the normal flow is what lets you 
spot abnormal ones.
