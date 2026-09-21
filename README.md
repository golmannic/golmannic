# Nicolas Olcan

Cybersecurity Graduate | SOC Analyst Path | Python & Security Projects

## About Me

Applied Computing graduate specializing in Cybersecurity, with hands-on experience in IT, software development, and backend security work. Building toward blue-team / detection engineering roles through real, working projects rather than tutorials.

## Skills

**Languages & Tools**
Python · SQL · Bash / Linux · Git & GitHub · Flask · FastAPI

**Cybersecurity**
Password/credential hashing (bcrypt) · JWT & OAuth2 auth flows · Signed/expiring URL schemes · Threat-model reasoning (see project write-ups below) · Studying for Security+

**Platforms**
Linux (Pop!_OS, Arch) · Windows · Virtualization (VirtualBox / QEMU)

## Featured Projects

**[Secure HLS Video Delivery](https://github.com/golmannic/secure-hls-demo)**
Flask app issuing short-lived, asset-specific signed URLs (via `itsdangerous`) for HLS video streaming, with an Nginx `secure_link` config for production-style hotlink protection. Documents its own threat model, including what it *doesn't* stop (screen recording, determined reverse engineering) — one signing layer isn't a silver bullet.
*Key skills: backend security, content protection, token design*

**[Phishing URL Risk Scorer](https://github.com/golmannic/phishing-detector)**
Rule-based CLI tool that extracts phishing signals from a URL (raw IPs, `@` obfuscation, suspicious TLDs/keywords, URL shorteners, subdomain abuse) and produces a weighted 0–100 risk score with reasoning. Built as a foundation for a future ML-based classifier — the feature extraction is already shaped for that.
*Key skills: threat heuristics, Python, security tooling*

**Website Security Monitoring Service** *(business project)*
Recurring cybersecurity service for small businesses: uptime monitoring with automated alerts, WordPress plugin/vulnerability management, and security patching workflows on a subscription model ($50–$300/month).
*Key skills: security operations, automation, business strategy*

**[Local Manual RAG Pipeline](https://github.com/golmannic/my-rag)** *(AI engineering, not security)*
Fully local RAG pipeline (Docling + Chroma + Ollama) for parsing PDF manuals and answering questions against them, with layout-aware chunking so spec tables survive intact. No API keys, nothing leaves the machine.
*Key skills: applied AI, local-first architecture, Python*

**[JWT Auth & Scoped Access Control](https://github.com/golmannic/Authentication-Practice)**
FastAPI service implementing OAuth2 password-flow login, bcrypt password hashing, and scope-based route protection (admin vs. student access).
*Key skills: authentication, access control*

## Experience

**Junior Software Development Intern** — Educational Options Foundation AZ (2026–Present)
Supported IT and software development operations; built structured educational programs; integrated AI tools into classroom workflows.

**Sales Advisor** — Apple / Tesla
Delivered customer-focused technical solutions; built strong communication and troubleshooting skills.

## Current Focus

Building a real log-analysis / detection lab (working with actual sample logs and MITRE ATT&CK mapping — no shortcuts) to back up blue-team skills claims with working code, and preparing for Security+.
