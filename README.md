# 🚀 DevOps_Project – Static Website Deployment with Docker, Git & Jenkins

![Home Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/home.png?raw=true)
![About Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/about.png?raw=true)
![Shop Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/shop.png?raw=true)
![Contact Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/contact.png?raw=true)

---

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Setup Instructions](#setup-instructions)
- [Outputs](#outputs)
- [Conclusion](#conclusion)

---

## 📌 Project Overview

This project demonstrates the CI/CD pipeline implementation for deploying a **static website** using:

- **GitHub** for version control
- **Jenkins** for automation
- **Docker** for containerization
- **Apache2** as a web server (inside Docker)
- **Ubuntu Server (24.04 LTS)** as the host OS

### 💡 Workflow:
1. Developer pushes code to GitHub.
2. GitHub webhook notifies Jenkins.
3. Jenkins pulls the repo → builds Docker image.
4. Jenkins runs the Docker container → website is deployed.

---

## 🛠 Technologies Used

- **Frontend:** HTML5, CSS3 (Static pages)
- **Version Control:** Git & GitHub
- **Containerization:** Docker
- **Automation:** Jenkins
- **Web Server:** Apache2 (within Docker)
- **OS:** Ubuntu 24.04 LTS

---

## 📁 Folder Structure

