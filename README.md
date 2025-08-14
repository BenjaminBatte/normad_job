# NomadLite — Distributed Job Runner

[![Go Version](https://img.shields.io/badge/Go-1.24+-blue.svg)](https://go.dev/)
[![GitHub Pages](https://img.shields.io/badge/Docs-GitHub%20Pages-brightgreen.svg)](https://benjaminbatte.github.io/normad_job/)

NomadLite is a self-hosted, distributed job execution system that schedules and runs jobs (shell commands, containers, or Go plugins) across multiple Linux agents.  

It features:

- **Real-time logs** via WebSockets  
- **Flexible scheduling**: FIFO, cron, and dependency-based  
- **Secure secret handling**  
- **Observability** with Prometheus and OpenTelemetry  

---

## 📚 Documentation

Full project documentation is available here:  
➡ **[NomadLite Docs on GitHub Pages](https://benjaminbatte.github.io/normad_job/)**

---

## 🚀 Status
This is an early-stage project. More detailed documentation, installation steps, and examples will be added as development progresses.

---

## 🛠️ Tech Stack
- **Backend:** Go 1.24+  
- **Frontend:** Angular  
- **Database:** PostgreSQL / SQLite  
- **Observability:** Prometheus, OpenTelemetry  
- **Service Management:** systemd  

---

## 📦 Repository Structure
\`\`\`
backend/      # Go backend code
ui/           # Angular frontend
docs/         # Project documentation (served via GitHub Pages)
\`\`\`
