# Web Application Security & Vulnerability Analysis

A curated collection of technical lab write-ups, vulnerability analyses, and remediation strategies focused on web application security, offensive security fundamentals, and defensive coding practices.

## Overview
This repository documents hands-on security research and vulnerability assessments conducted across simulated environments (including PortSwigger Web Security Academy). Each write-up covers:
- **Root Cause Analysis:** Examining the underlying logic or framework behavior that introduces the flaw.
- **Testing & Exploitation Methodology:** Step-by-step logic used to verify vulnerability existence and evaluate impact.
- **Defensive Remediation:** Secure coding practices (e.g., parameterized queries, robust input validation) required to patch the issue.

---

## Portfolio Index

### 1. SQL Injection (SQLi)
* [Blind SQL Injection with Conditional Responses](./sql-injection/blind-sqli-conditional-responses/README.md)
  - **Focus:** Boolean-based blind SQLi, logic verification, character extraction via conditional responses, parameterized query defense.

### 2. Authentication & Session Management
* [Username Enumeration via Response Timing & IP Rate-Limit Bypass](./Authentication/ip-header-spoofing/README.md)
  - **Focus:** Time-based side-channel analysis, HTTP `X-Forwarded-For` header spoofing, rate-limiting evasion, and password brute-forcing.

---

## Roadmap / Planned Expansion
As part of ongoing research, write-ups covering the following vulnerability domains are currently in development:
- [ ] Cross-Site Scripting (XSS) & Contextual Input Encoding
- [ ] Cross-Site Request Forgery (CSRF) & Token Defense
- [ ] Access Control & Broken Object Level Authorization (BOLA/IDOR)
