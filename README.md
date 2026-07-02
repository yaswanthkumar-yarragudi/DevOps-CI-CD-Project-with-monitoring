# 🚀 DevOps CI/CD Project with Monitoring

This project demonstrates a complete **CI/CD pipeline** for deploying a Java Spring Boot application using modern DevOps tools. It automates code integration, testing, containerization, deployment, and monitoring to ensure reliable and efficient software delivery.

---

## 📌 Project Overview

The pipeline covers the complete DevOps lifecycle:

- Source Code Management with Git & GitHub
- Continuous Integration using Jenkins
- Build Automation using Maven
- Code Quality Analysis with SonarQube
- Containerization using Docker
- Container Image Storage with Docker Hub
- Continuous Deployment to Kubernetes
- Monitoring using Prometheus & Grafana

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Version Control | Git, GitHub |
| CI/CD | Jenkins |
| Build Tool | Maven |
| Code Quality | SonarQube |
| Containerization | Docker |
| Container Registry | Docker Hub |
| Orchestration | Kubernetes |
| Monitoring | Prometheus, Grafana |
| Language | Java (Spring Boot) |

---

## 📂 Project Structure

```
.
├── src/
├── Dockerfile
├── Jenkinsfile
├── pom.xml
├── deployment-service.yaml
├── sonar-project.properties
└── README.md
```

---

## ⚙️ CI/CD Pipeline Workflow

```
Developer
      │
      ▼
 GitHub Repository
      │
      ▼
 Jenkins Pipeline
      │
      ├── Checkout Code
      ├── Maven Build
      ├── Unit Testing
      ├── SonarQube Analysis
      ├── Build Docker Image
      ├── Push Image to Docker Hub
      └── Deploy to Kubernetes
                 │
                 ▼
         Prometheus Monitoring
                 │
                 ▼
          Grafana Dashboard
```

---

## 🔄 Pipeline Stages

### ✅ Source Code Checkout
Jenkins pulls the latest code from GitHub.

### ✅ Build Application
The application is built using Maven.

```bash
mvn clean package
```

### ✅ Code Quality Analysis
SonarQube performs static code analysis and checks for code quality issues.

### ✅ Docker Image Build

```bash
docker build -t your-dockerhub-username/boardgame .
```

### ✅ Push Docker Image

```bash
docker push your-dockerhub-username/boardgame
```

### ✅ Kubernetes Deployment

```bash
kubectl apply -f deployment-service.yaml
```

### ✅ Monitoring

- Prometheus collects application and cluster metrics.
- Grafana visualizes metrics through interactive dashboards.

---

## 🚀 Prerequisites

- Java 17+
- Maven
- Git
- Docker
- Kubernetes Cluster
- Jenkins
- SonarQube
- Prometheus
- Grafana

---

## 📸 Screenshots

You can add screenshots of:

- Jenkins Pipeline
- SonarQube Dashboard
- Docker Hub Repository
- Kubernetes Pods
- Prometheus Targets
- Grafana Dashboard

---

## 📈 Features

- Automated CI/CD Pipeline
- Code Quality Checks
- Docker Containerization
- Kubernetes Deployment
- Monitoring & Visualization
- Scalable Deployment Architecture

---

## 📚 Learning Outcomes

Through this project, I learned:

- CI/CD Pipeline Implementation
- Jenkins Pipeline Automation
- Docker Image Creation
- Kubernetes Deployments
- SonarQube Integration
- Monitoring using Prometheus & Grafana
- GitHub Workflow
- DevOps Best Practices

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is for educational and learning purposes.

---

## 👨‍💻 Author

**Yaswanth Kumar Yarragudi**

- GitHub: https://github.com/yaswanthkumar-yarragudi
- LinkedIn: https://www.linkedin.com/in/yaswanth-kumar-yarragudi/

⭐ If you found this project useful, don't forget to star the repository!
