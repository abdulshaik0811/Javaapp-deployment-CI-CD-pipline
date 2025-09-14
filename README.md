🚀 CI/CD Pipeline for Java Application

This project demonstrates a CI/CD pipeline to build, test, analyze, secure, and deploy a Java application using modern DevSecOps tools.

🛠️ Tools & Technologies

Java (Spring Boot / Maven) → Application

Jenkins → CI/CD automation

Docker & Docker Compose → Containerization & orchestration

SonarQube → Code quality and static analysis

Trivy → Container image vulnerability scanning

AWS EC2 → Deployment environment

GitHub → Source code version control

New Relic → Application monitoring

📌 Workflow

Code Commit (GitHub)

Java application source code is pushed to GitHub.

Continuous Integration (Jenkins)

Jenkins pipeline triggers automatically.

Pipeline stages:

Checkout Code from GitHub

Build & Test (Maven/Gradle)

SonarQube Analysis for code quality

Trivy Scan for vulnerabilities

Build Docker Image

Continuous Deployment

Docker image deployed to AWS EC2 using Docker Compose.

Monitoring

Application health and performance monitored via New Relic
