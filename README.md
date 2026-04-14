# 🚀 DevSecOps Multi-Tier Application Pipeline

This repository demonstrates a **production-level DevSecOps pipeline** for a multi-tier application architecture, integrating security at every stage of the CI/CD lifecycle.

---

## 📌 Project Overview

This project showcases how to build, scan, and deploy a **multi-tier application** consisting of:

- 🌐 **Frontend** – User interface (HTML)
- ⚙️ **Backend** – Python-based application (Flask + Gunicorn)
- 🤖 **Ollama** – AI/LLM service integration
- 🐳 **Containerized Deployment** using Docker & Docker Compose

The pipeline ensures **secure, automated, and scalable deployments**.

---

## 📁 Repository Structure

.
├── .github/workflows/ # CI/CD pipeline definitions
├── templates/ # Frontend templates
├── Dockerfile # Backend container configuration
├── docker-compose.yml # Multi-service orchestration
├── app.py # Backend application (Flask)
├── requirements.txt # Python dependencies
├── index.html # Frontend entry point
├── .trivyignore # Ignored vulnerabilities
