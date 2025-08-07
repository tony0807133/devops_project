# 🚀 DevOps_Project – Static Website Deployment with Docker, Git & Jenkins

![Home Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/home.jpg?raw=true)
![About Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/about.jpg?raw=true)
![Shop Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/shop.jpg?raw=true)

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
2. GitHub webhook triggers Jenkins.
3. Jenkins pulls the GitHub repo.
4. Jenkins builds a Docker image from the project.
5. Jenkins runs a Docker container with Apache2.
6. Static website is served via Apache in Docker.

---

## 🛠 Technologies Used

- **Frontend:** HTML5, CSS3 (Static Web Pages)
- **Version Control:** Git & GitHub
- **CI/CD:** Jenkins
- **Containerization:** Docker
- **Web Server:** Apache2
- **Operating System:** Ubuntu 24.04 LTS

---
![cicd Page](https://github.com/tony0807133/devops_project/blob/master/screenshots/cicd.png?raw=true)
