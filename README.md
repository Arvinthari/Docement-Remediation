# 🚀 Unified Gitea + Nextcloud + MkDocs Local Setup

This repository contains the foundational setup to deploy **Gitea**, **Nextcloud**, and **MkDocs**, providing an integrated environment for version control, file storage, and project documentation.

This system was developed as part of my independent project to streamline project management, documentation, and file collaboration — all hosted locally using Docker.

---

## 🔍 Project Description

The unified setup provides:

- ⚙️ **Gitea** — A lightweight, self-hosted Git service for version control  
- ☁️ **Nextcloud** — A secure private cloud for file storage, collaboration, and sharing  
- 📖 **MkDocs Dashboard** — A clean, responsive site for project documentation using MkDocs  

With this setup, you can manage code, store files, and access project documentation — all hosted on your own system without relying on third-party platforms.

---

## ✅ Features Completed

Basic Docker Compose setup for:

- **Gitea** available at [http://localhost:3000](http://localhost:3000)  
- **Nextcloud** accessible via [http://127.0.0.1:8000](http://127.0.0.1:8000)  
- **MkDocs Dashboard** served at [http://localhost:8080/apps/dashboard](http://localhost:8080/apps/dashboard)  

Pre-configured folders and settings to get each service running quickly.  
Local-first development focus, easily expandable for production needs.

---

## 🛠️ Tech Stack

- **Docker & Docker Compose** — Containerized service deployment  
- **MkDocs** — Static site generator for documentation  
- **Gitea** — Lightweight Git repository hosting  
- **Nextcloud** — File storage and collaboration platform  

---

## 🚀 How It Works

- **Gitea**: Run the Gitea Docker container, manage Git repositories locally  
- **Nextcloud**: Run Nextcloud for storing project files and resources securely  
- **MkDocs**: Use MkDocs to create, edit, and serve project documentation with a live dashboard  

Each service is isolated but runs concurrently, accessible via their respective URLs.

---

## 📌 Prerequisites

- Docker & Docker Compose installed  
- Python 3.x for MkDocs  
- Internet connection (initial image pulls)  

**To install MkDocs:**  
```bash
pip install mkdocs
```

## 📝 Future Work
-Add persistent data volumes for long-term storage

-Secure services with user authentication and HTTPS

-Integrate MkDocs with Gitea repositories for automated documentation builds

-Explore AI-enhanced search for files and code using OpenAI

---

## 📂 Folder Structure
arduino
```bash
project-root/
├── gitea/           # Gitea setup  
│   ├── docker-compose.yml  
│   └── config.txt  
├── nextcloud/       # Nextcloud setup  
│   ├── docker-compose.yml  
│   └── config.txt  
├── mkdocs/          # MkDocs documentation site  
│   ├── mkdocs.yml  
│   ├── docs/  
│   │   └── index.md  
│   └── config.txt  
└── README.md  
```

## 🤝 Contributing
Pull requests are welcome. For improvements, issues, or suggestions, please open an issue to discuss changes.

---

## 📄 License
This project is intended for educational, internship, testing, and personal development use only.

---

## 🙋‍♂️ About Me
**A G Sriee Arvinth Raajhen**                                                                                                                                                  
Intern at WinVinaya Foundation  
Passionate about using automation and AI for good.
