# ciberseguridad-portfolio
Automated security scanner:  7 tools, AI analysis, PDF report generation

>  Source code is private. This repo contains a real scan report as a portfolio sample.


## What it does

Given a domain, DigiWeb runs a full security audit automatically:

| Tool | Purpose |
|------|---------|
| `nmap` | Port scanning & service detection |
| `nikto` | Web server vulnerability scan |
| `testssl` | SSL/TLS configuration analysis |
| `whatweb` | Technology fingerprinting |
| `sublist3r` | Subdomain enumeration |
| `curl` | HTTP headers inspection |
| `dig` | DNS records analysis |

Results are analyzed by an AI model (Groq + LLaMA) which generates:
- A **security score** (0–100)
- Specific, actionable **recommendations**
- A **professional PDF report**

---

## Sample Report
-visit repo 

Real scan of [revflowy.com](https://revflowy.com) — Score: **70/100**

---

## Tech Stack

- Python, Bash
- Groq API (LLaMA 3.3 70B)
- ReportLab (PDF generation)
- Runs locally on Linux via VirtualBox

---

## About

Built by [@Valew7](https://github.com/Valew7) as part of DigiWeb — a personal security automation project.
