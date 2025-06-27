# espocrm-preciousmeinc
This is the creation of a Lightweight CRM integration using EspoCRM and REST API client for the company Precious Me Inc

Precious Me Website: https://preciousmeinc.org/

# 🧊 EspoCRM Dockerized Setup

A local development environment for [EspoCRM](https://www.espocrm.com/) powered by Docker.

---

## 🚀 Features

- EspoCRM running in an Apache + PHP container
- MySQL database container
- Persistent volume storage
- Simple local deployment using Docker Compose

---

## 📦 Project Structure

espocrm-preciousmeinc/
├── docker-compose.yml # Defines containers & environment
├── Dockerfile # Builds PHP + Apache with extensions
├── espocrm/ # EspoCRM source code (not a separate Git repo)
├── .gitignore
└── README.md

## 🛠 Prerequisites

Make sure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Git](https://git-scm.com/)

---

## 🧑‍💻 Getting Started

### 1. Clone this repository

```bash
git clone https://github.com/YOUR_USERNAME/espocrm-preciousmeinc.git
cd espocrm-preciousmeinc
cd docker

### 2. Build Start containers

docker-compose up --build -d

### 3. Open EspoCRM in your browser

http://localhost:8080

---

Additional Commands

Stop Github Container:

docker-compose down

Clean Up:

docker-compose down -v # To stop and remove containers and volumes

Git Commit Push:

git add .
git commit -m "Initial working EspoCRM Docker setup"
git push origin main
