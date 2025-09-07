# PentorSec: AI-Powered, Asynchronous Pentest & ASM Platform

<img width="1623" height="913" alt="WelcomePage" src="https://github.com/user-attachments/assets/42d0c6df-b21f-4be6-90d1-f865826190e9" />

PentorSec is a management platform designed to end “tool chaos” for modern security teams and pentesters. It consolidates scattered command-line tools on an asynchronous task architecture (FastAPI + Celery) and uses Artificial Intelligence (Gemini/Ollama) to analyze discovered vulnerabilities.

This is an “IP/Asset for Sale.” The codebase is written to enterprise-ready standards.

---

## 🎯 Core Philosophy: Eliminating the “Buy vs. Build” Cost
PentorSec is designed to eliminate the **9-12 month R&D time** required for a company to build an ASM platform from scratch.

## 🚀 Technical Architecture and Features

This is not just a wrapper; it is a scalable, enterprise-level architecture:

* **Asynchronous Backend:** Built on high-performance **FastAPI**. All scans (Nmap, Nuclei, etc.) are managed asynchronously with a **Celery** task queue and **Redis** broker. (Can handle hundreds of scans simultaneously).
* **AI-Powered Analysis:** Doesn't just list found vulnerabilities; analyzes, prioritizes, and generates report drafts using **Google Gemini** or local **Ollama** models.
* **Integrated Tool Chaining:** All industry-standard OSINT and scanning tools are integrated into a single workflow:
    * **Discovery:** Nmap, Subfinder, Amass
    * **Scanning:** Nuclei
    * **Fuzzing:** FFUF, Gobuster
* **Desktop Agent:** Extends its capabilities from external assets to **internal network security** and endpoint asset management.
* **Professional Code Quality:** The entire codebase is fully compliant with **Black, Flake8**, and **Mypy** (static type checking). This guarantees zero “technical debt” and easy maintenance.
* **Ready Infrastructure:**
    * **Database:** SQLAlchemy (ORM), Alembic (Migrations), MySQL/SQLite support.
    * **Security:** Authentication with JWT (Passlib/Bcrypt), Rate Limiting, and CORS.
    * **Payment:** LemonSqueezy integration is ready.
    * **Deployment:** Fully Dockerized.

---

## 📈 Acquisition Opportunity

This project is for sale with the entire codebase (all IP rights).

This technology stack is an excellent addition to existing DevSecOps products, Security Consulting firms, or ASM platforms.

For serious acquisition and private demo requests, please contact us at pentora59@gmail.com.
