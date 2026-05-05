
# 🚀 DevOps Kickstart Project:Production-Ready CI/CD Pipeline with Dockerized Deployment on AWS - JIra Ticket rising

## 📌 Project Overview

This project demonstrates a complete **real-world DevOps workflow** by building, containerizing, automating, and deploying an application to the cloud.

The goal is to simulate how DevOps / SRE teams work in production environments using modern tools and best practices.

This is NOT just an app — it is a full **end-to-end DevOps pipeline**.

---

## 🏗 Architecture Flow

Developer → GitHub → CI Pipeline → Docker Build → AWS EC2 → Live Application

---

## ⚙️ Tech Stack

- Node.js (Express)
- Docker (Containerization)
- AWS EC2 (Deployment)
- Git & GitHub (Version Control)
- GitHub Actions (CI/CD Automation)
- Jira (Agile Task Tracking)

---

## 🚀 Features Implemented

✅ Node.js web application  
✅ Dockerized application  
✅ EC2 cloud deployment  
✅ Git branching strategy (main / develop / feature)  
✅ Automated CI pipeline using GitHub Actions  
✅ Jira ticket tracking (Agile workflow)  
✅ Production-style DevOps process  

---

## 📂 Project Structure

```

devops-kickstart-project/
│
├── server.js
├── package.json
├── Dockerfile
├── .github/workflows/ci.yml
├── jira-tickets.csv
├── README.md
├── docs/
└── scripts/

```

---

## 🐳 Run Locally (Docker)

### Build image
```

docker build -t devops-app .

```

### Run container
```

docker run -p 3000:3000 devops-app

```

### Open browser
```

[http://localhost:3000](http://localhost:3000)

```

---

## ☁️ Deployment (AWS EC2)

Steps followed:

1. Launch EC2 Ubuntu instance
2. Install Docker & Node
3. Clone repository
4. Build Docker image
5. Run container
6. Expose port 3000 in security group

Access:
```

http://<EC2-PUBLIC-IP>:3000

```

---

## 🔁 CI/CD Pipeline

Implemented using GitHub Actions.

### Automatically triggers on:
- push to main
- push to develop

### Pipeline steps:
- Checkout code
- Install dependencies
- Build Docker image
- Validate build

Flow:
```

git push → GitHub → Actions → Build → Success

```

---

## 🧩 Git Workflow Strategy

```

main      → production
develop   → integration
feature/* → task branches

```

Example:
```

git checkout -b feature/DOK-5-dockerfile
git commit -m "DOK-5 Added Dockerfile"

```

---

## 📋 Jira Workflow

Agile Scrum tracking:

Statuses:
```

To Do → In Progress → In Review → Done

```

Issue Types:
- Task
- Story
- Feature
- Bug
- Request

Each task is:
Ticket → Branch → Code → PR → Done

---

## 🎯 Learning Outcomes

Through this project, we practiced:

- Cloud deployment
- Containerization
- CI/CD automation
- Git workflows
- Agile project tracking
- Production DevOps practices

---


---


