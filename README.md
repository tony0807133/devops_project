# DevOps_Project – Static Website Deployment

<!--
Update your image links once you upload screenshots like below:

![Home Page](https://github.com/tony0807133/devops_project/screenshots/home.png?raw=true)
![About Page](https://github.com/tony0807133/devops_project/blob/master/assets/screenshots/about.png?raw=true)
![Shop Page](https://github.com/tony0807133/devops_project/blob/master/assets/screenshots/shop.png?raw=true)
![Contact Page](https://github.com/tony0807133/devops_project/blob/master/assets/screenshots/contact.png?raw=true)
-->

## 🚀 Deploying Static Website using Docker, Git & Jenkins

This project demonstrates how a complete CI/CD pipeline is implemented to automatically deploy a static website using Jenkins, Docker, and GitHub (for version control) on an Ubuntu server. Whenever new code is pushed to the GitHub repository, Jenkins is triggered using a webhook, builds a new Docker image, and deploys the website container.

This ensures:
- ✅ Continuous Integration
- ✅ Continuous Delivery
- ✅ Zero manual deployment effort
- ✅ Consistency and reliability in the deployment process

---

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Outputs](#outputs)
- [Conclusion](#conclusion)

---

## 📌 Project Overview

This project showcases the implementation of a DevOps workflow that:
- Monitors a GitHub repository for code updates.
- Triggers Jenkins pipeline through a webhook.
- Builds and tags a Docker image for the website.
- Pushes and runs the image on a server using Docker.

The website is a simple responsive HTML/CSS site packaged and served via Docker. The goal is to demonstrate core DevOps concepts—automation, version control, containerization, and delivery pipelines.

---

## 🛠 Technologies Used

- **HTML/CSS** – Frontend pages
- **Git & GitHub** – Code versioning and repository
- **Docker** – For containerizing the static site
- **Jenkins** – Automating build and deployment
- **Ubuntu 24.04 LTS** – Server environment
- **Apache Web Server** – Served via Docker container

---

## 🧑‍💻 Setup Instructions

### 1. 📁 Clone the Repository

```bash
git clone https://github.com/tony0807133/devops_project.git
cd devops_project
