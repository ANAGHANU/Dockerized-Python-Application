# Dockerized Python Application

A simple Python application containerized using Docker and Docker Compose.

This project demonstrates how to package a Python application into a Docker container, manage dependencies, and run the application together with its required services using Docker Compose.

## 📁 Project Structure

```text
.
├── .github/
│   └── workflows/          # GitHub Actions workflows
├── Dockerfile              # Docker image configuration
├── app.py                  # Main Python application
├── create_db.py            # Database creation/setup script
├── drop_db.py              # Database cleanup/removal script
├── docker-compose.yml      # Docker Compose configuration
└── requirements.txt        # Python dependencies
