# Hi, I'm Mahevish Fatema 👋

### Aspiring DevOps Engineer | AWS | Docker | Kubernetes | Jenkins | Linux

I'm an **Aspiring DevOps Engineer** with hands-on experience through projects and practical training in **Docker, Kubernetes, Jenkins, and CI/CD**.

I'm passionate about learning how applications move from **code to production** through automation, containerization, orchestration, and cloud technologies.

> **Turning Code into Reliable Deployments 🚀**

---

## 👩‍💻 About Me

* 🎓 Master's in Computer Science
* ☁️ Interested in **Cloud & DevOps**
* 🐳 Practicing **Docker & Containerization**
* ☸️ Learning and working with **Kubernetes**
* 🔄 Building **CI/CD pipelines with Jenkins**
* 🐧 Working with **Linux and Bash**
* ☁️ Exploring **AWS cloud services**
* 🔐 Interested in **DevOps security and reliable application delivery**

---

## 🛠️ Skills & Technologies

### DevOps & Cloud

* AWS
* Docker
* Kubernetes
* Jenkins
* CI/CD

### Programming & Application Development

* Python

### Operating Systems & Tools

* Linux
* Git
* GitHub
* Bash

---

## 🚀 Projects

### Employee Messaging System

A web-based internal messaging system developed using Django to enable communication between employees.

**Highlights:**

* Developed an employee messaging system using Django.
* Designed the system to support internal communication.
* Focused on reducing external data sharing and supporting secure internal communication.

**Technologies:** Python, Django

---

### 🔧 DevOps Projects

# AWS EKS Java Application Deployment Pipeline

An automated CI/CD pipeline designed to build, containerize, and deploy the **`maven-web-app1`** Java web application onto Amazon Elastic Kubernetes Service (AWS EKS) with zero-downtime rollouts.

---

## Architecture & Tech Stack

* **Application:** Java Web Application (`siddiquimahevishfatema/maven-web-app1`)
* **Build Tool:** Apache Maven
* **CI/CD Orchestration:** Jenkins
* **Containerization:** Docker
* **Container Registry:** Amazon ECR / Docker Hub
* **Orchestration Platform:** Amazon Elastic Kubernetes Service (AWS EKS)
* **Deployment Strategy:** Rolling Updates (Zero-Downtime)

---

## CI/CD Pipeline Workflow

[ Code Commit ] ➔ [ Jenkins Pipeline ] ➔ [ Maven Build & Test ]
│
[ Zero-Downtime EKS Deployment ] ◄─ [ Push Docker Image ] ◄─ [ Docker Build ]


1. **Source Control:** Jenkins pulls the latest source code from `siddiquimahevishfatema/maven-web-app1`.
2. **Build & Test:** Maven compiles the code and packages the web application into a `.war` file.
3. **Containerization:** Builds a lightweight Docker image containing Tomcat/Jetty to serve the application artifact.
4. **Registry Push:** Authenticates and pushes the tagged image to the container registry.
5. **EKS Rollout:** Applies updated Kubernetes manifests via `kubectl` to trigger a rolling update across worker nodes with zero application downtime.

---

## Repository Structure

```text
├── .jenkins/
│   └── Jenkinsfile            # Declarative Jenkins pipeline script
├── k8s/
│   ├── deployment.yaml        # EKS Deployment spec (rolling updates)
│   └── service.yaml           # Service configuration (LoadBalancer/Ingress)
├── src/                       # Java application source code
├── Dockerfile                 # Multi-stage Dockerfile for Maven build & web server
├── pom.xml                    # Maven dependencies and build settings
└── README.md
Setup & Configuration
Prerequisites
Active AWS EKS cluster and configured worker nodes.

Installed local tools: Java JDK (11+), Apache Maven, Docker, AWS CLI, kubectl.

Jenkins server configured with AWS credentials, Docker, and Kubernetes CLI plugins.

Running Locally
Build the WAR file:

Bash
mvn clean package
Build the Docker Image:

Bash
docker build -t maven-web-app1:latest .
Run Container Locally:

Bash
docker run -d -p 8080:8080 maven-web-app1:latest
Key Metrics & Achievements
Automated Rollouts: Fully automated CI/CD pipeline triggered on code commit using Jenkins.

Zero Downtime: Implemented Kubernetes rolling update strategy to eliminate downtime during releases.

Streamlined Containerization: Leveraged multi-stage Docker builds to reduce image footprint and speed up deployment times across EKS worker nodes.

I'm currently building hands-on DevOps projects by taking applications and implementing modern deployment practices using:

* Docker
* Jenkins
* Kubernetes
* AWS
* CI/CD
* Linux

These projects will demonstrate my practical experience in **containerization, automated deployments, Kubernetes orchestration, and cloud deployment**.

---


## 📚 Currently Learning

* Advanced Kubernetes
* AWS & Cloud Infrastructure
* CI/CD Automation
* Infrastructure & Deployment Automation
* DevOps Security
* Containerized Application Deployment

---

## 🎓 Education

**Master's in Computer Science**
Dr. Rafiq Zakaria Centre for Higher Learning and Advanced Research, Aurangabad
2021–2023 | 88.8%

**Bachelor's in Computer Science**
Maulana Azad College, Aurangabad
2018–2021 | 82.83%

---

## 🏆 Achievements

* 🥇 Secured Rank 1 in College Academics.
* 📚 Assisted teachers in designing assignments and learning materials.

---

## 📊 My DevOps Journey

I'm continuously building practical projects to strengthen my understanding of DevOps and cloud technologies.

```text
Application
     ↓
   Git/GitHub
     ↓
   Jenkins
     ↓
    Docker
     ↓
 Kubernetes
     ↓
     AWS
```

---

## 🤝 Let's Connect

* 💼 **LinkedIn:** https://www.linkedin.com/in/mahevish-fatema-7015512a8/
* 🐙 **GitHub:** https://github.com/siddiquimahevishfatema
* 🌐 **Portfolio:** https://siddiquimahevishfatema.github.io/mahevish_fatema.github.io/
* 📧 **Email:** siddiquimahevish07@gmail.com

---

⭐ Feel free to explore my repositories as I continue building and documenting my DevOps journey.
