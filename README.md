# DevOps CI/CD Pipeline with GitHub Actions 🚀

## 📌 Task Objective
Automate the deployment of a Node.js web app using GitHub Actions and Docker.

## ⚙️ Tools Used
- GitHub Actions
- Node.js
- Docker & DockerHub

## 🛠 Pipeline Workflow
1. Trigger on push to `main`
2. Install dependencies
3. Run tests
4. Build Docker image
5. Push to DockerHub

## 📂 Repo Structure
```
devops-ci-cd-nodejs/
 ┣ .github/workflows/main.yml
 ┣ app/index.js
 ┣ app/package.json
 ┣ app/Dockerfile
 ┗ README.md
```

## 🔗 DockerHub Image
- Image: `dockerhub-username/nodejs-demo-app:latest`

## ✅ Learning
- Understood CI/CD workflow
- Built & deployed a containerized app
- Learned GitHub Actions secrets handling
