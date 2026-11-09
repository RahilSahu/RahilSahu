# Rahil Sahu

**Penetration Tester and AppSec Engineer, building security tools, applied AI products, and systems software in the open.**

I help build secure applications by identifying risks before attackers do. By day: 4+ years of VAPT across web, mobile, API, network and thick-client applications, source-code review, cloud security validation and ISO 27001 work at TeamLease RegTech. In the open: the projects below, every one of them working software with tests, not demos.

![Profile views](https://komarev.com/ghpvc/?username=RahilSahu&color=0e75b6&style=flat)
[![GitHub followers](https://img.shields.io/github/followers/RahilSahu?style=flat&logo=github)](https://github.com/RahilSahu?tab=followers)

## Flagship projects

| Project | Domain | What it is |
| --- | --- | --- |
| [aegis-security-platform](https://github.com/RahilSahu/aegis-security-platform) | AI-powered security platform | **Aegis**: the verification layer for security findings. Ingests Nuclei, ZAP and generic scanner output, deduplicates across tools, verifies each finding with deterministic non-destructive checks, and triages with an AI that advises but never decides the verdict. CLI, API and dashboard; 60 tests including live verification against vulnerable and patched targets |
| [adaptive-llm-chatbot](https://github.com/RahilSahu/adaptive-llm-chatbot) | Applied AI / LLM engineering | **AdaptiveChat**: a document-chat product that sets its own temperature per message, with LangGraph orchestration, input and output guardrails, semantic retrieval over owner-uploaded documents (embeddings with a TF-IDF fallback), LangSmith tracing and a web UI. 48 tests, Docker packaging |
| [distributed-task-queue](https://github.com/RahilSahu/distributed-task-queue) | Systems / distributed systems | A dependency-free distributed task queue in Python: broker with leases and heartbeats, priority queues, retries with backoff, dead-letter queue, at-least-once delivery, persistence, and a worker client. Built to show how systems like Celery and SQS work inside |
| [agentforge](https://github.com/RahilSahu/agentforge) | AI agents / orchestration | A production-pattern multi-agent framework on LangGraph: supervisor routing across specialist agents, LLM-proposed tool calls validated before execution, a human-approval gate (pause and resume) for sensitive tools, guardrails on input and output, and a complete execution trace per run. 23 tests |
| [formfit](https://github.com/RahilSahu/formfit) | Consumer web / public utility | **FormFit** (live at formfit-lilac.vercel.app): fits a photo, signature or document set to the exact pixel and KB-range rules of online application forms, the rules that reject millions of exam and job uploads every year. Fits both the minimum and the maximum (under-minimum files are padded), converts to JPG, builds PDFs under a size limit, and runs entirely in the browser: zero upload, open source, offline-capable PWA. 8 tests for the fitting core |
| [cloud-misconfiguration-scanner](https://github.com/RahilSahu/cloud-misconfiguration-scanner) | Cloud security / DevSecOps | Multi-cloud misconfiguration scanner for AWS, Azure, GCP and OCI: public buckets and containers, public policies, and world-open firewall and NSG rules, with offline analysers for exported policies. 27 tests |

## Open source contributions

- **OWASP CheatSheetSeries**: invited by maintainer @mackowski to review PR #2908 (NPM Security Cheat Sheet, "Inspecting a project you did not write"); review and approval posted, two completeness findings addressed by the author.
- **Google osv-scanner**: contributor on issue #570 (CLI help documentation).
- **pypa/pip-audit**: a tested fix for the `--fix` side of duplicate requirements (#564), prepared on a fork branch; the upstream repo currently restricts interaction to prior contributors, so submission waits for that to lift.

## Security tools

### Assessment essentials

| Tool | What it does |
| --- | --- |
| [http-security-headers-checker](https://github.com/RahilSahu/http-security-headers-checker) | Checks a site for missing or weak HTTP security headers and scores it out of 100 |
| [tls-cert-inspector](https://github.com/RahilSahu/tls-cert-inspector) | Inspects TLS certificates: expiry, issuer, SANs, self-signed and old protocol problems |
| [dns-email-auth-checker](https://github.com/RahilSahu/dns-email-auth-checker) | Checks SPF, DMARC, DKIM and CAA so a domain cannot be spoofed easily |
| [port-scanner-lite](https://github.com/RahilSahu/port-scanner-lite) | Careful TCP connect scanner with banner grabbing and warnings on risky services |
| [jwt-analyzer](https://github.com/RahilSahu/jwt-analyzer) | Decodes JWTs and audits them: alg none, expiry, sensitive claims, weak HMAC secrets |
| [bulk-url-checker](https://github.com/RahilSahu/bulk-url-checker) | Checks lists of URLs for status, redirect chains and errors, writes a CSV report |
| [cors-misconfiguration-checker](https://github.com/RahilSahu/cors-misconfiguration-checker) | Probes a URL with hostile Origin headers and classifies reflection, null-origin and lookalike trust |

### File and upload testing

| Tool | What it does |
| --- | --- |
| [upload-test-payloads-generator](https://github.com/RahilSahu/upload-test-payloads-generator) | Generates a suite of harmless file-upload test cases with a manifest of expected results |
| [rlo-filename-spoofer](https://github.com/RahilSahu/rlo-filename-spoofer) | Generates and detects Right-to-Left Override filename spoofs (MITRE ATT&CK T1036.002) |
| [pdf-active-content-test-generator](https://github.com/RahilSahu/pdf-active-content-test-generator) | Builds PDFs with benign active-content markers to test upload filters, AV and DLP |
| [modern-image-upload-test-corpus](https://github.com/RahilSahu/modern-image-upload-test-corpus) | 40 harmless test files for HEIC, HEIF, AVIF, JPEG XL and WebP upload validation and parser robustness |

All tools are for authorised testing, defence and learning. Test files use harmless markers only, never working shells or exploit payloads.

## Writing

[appsec-field-notes](https://github.com/RahilSahu/appsec-field-notes): short, practical security posts written from assessment work, covering HTTP headers, file upload testing, JWT audits, email spoofing and filename spoofing, each with the commands to test it yourself. A new post lands most weeks.

## Skills and tooling

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat&logo=burp-suite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-163B69?style=flat)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

Application and API security, mobile security, network VAPT, OWASP Top 10 and API Security Top 10, SAST and SCA review, LLM application engineering (RAG, agents, guardrails), cloud security across AWS, Azure, GCP and OCI, ISO 27001 and SOC 2 evidence work, TPRM.

## GitHub stats

![Rahil's GitHub stats](https://github-readme-stats.vercel.app/api?username=RahilSahu&show_icons=true&theme=dark)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RahilSahu&layout=compact&theme=dark)

## Elsewhere

- Portfolio: https://rahilsahu.github.io
- LinkedIn: https://www.linkedin.com/in/rahilsahu
- Email: rahilsahu.jobs@gmail.com
- Based in Sagar, Madhya Pradesh, India. Open to remote roles internationally, and relocation for the right role.

## Responsible use

Everything published here is for authorised security testing, defence and learning. Only test systems you own or have explicit permission to test.
