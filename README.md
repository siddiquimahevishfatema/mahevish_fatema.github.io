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
* YAML

### Operating Systems & Tools
* Linux
* Git
* GitHub
* Bash

---

## 🚀 Projects

### 🔧 DevOps Projects

#### AWS EKS Java Application Deployment Pipeline

Designed and built an end-to-end continuous integration and deployment pipeline targeting an Amazon EKS cluster to automate application rollouts.

**Key Achievements & Technical Architecture:**
* **Infrastructure & Cluster Setup:** Provisioned an AWS EKS cluster using `eksctl` with custom node groups and configured IAM roles for node communication. Verified active cluster nodes (`kubectl get nodes`).
* **Continuous Integration:** Configured a multi-stage Jenkins pipeline triggered by GitHub commits, integrating Apache Maven (`mvn clean package`) for automated compilation and artifact creation.
* **Containerization & Registry:** Built lightweight container images from the `.war` application artifact and pushed tagged images to Docker Hub (`mahevish07/maven-web-app`).
* **Automated Deployment & Load Balancing:** Authenticated Jenkins with cluster credentials (`kubeconfig`) to execute dynamic rollouts (`kubectl apply -f k8s-deploy.yml`), exposing the application externally via AWS Elastic Load Balancer (ELB).

**GitHub:** [Repository Link](https://github.com/siddiquimahevishfatema/maven-web-app1)

---

#### Automated Web Application Infrastructure & Containerized Deployment

Provisioned secure, scalable AWS cloud infrastructure and automated state management using Terraform to support reliable containerized application deployments.

**Key Achievements & Technical Architecture:**
* **Infrastructure Provisioning & Versioning:** Authored declarative Infrastructure-as-Code (IaC) scripts using Terraform, pinning HashiCorp AWS provider plugins to `v5.100.0` for predictable resource orchestration and provider stability.
* **State Management & Concurrency:** Configured AWS provider authentication and integrated remote backend state locking to maintain deployment state integrity and support concurrent developer workflows.
* **Network Access & Security Controls:** Designed and applied secure VPC-bound security group rules to restrict inbound access strictly to application port `8080` while enabling full egress traffic for external updates and API calls.

**GitHub:** [Repository Link](https://github.com/siddiquimahevishfatema/aws-terraform-docker-webapp)

---

## 📚 Currently Learning

* ☸️ Advanced Kubernetes
* ☁️ AWS & Cloud Infrastructure
* 🔄 CI/CD Automation
* 🛡️ DevOps Security
* ⚙️ Infrastructure & Deployment Automation
* 🌐 NGINX & Reverse Proxies
* 🐳 Containerized Application Deployment

---

## 🎓 Education

**Master's in Computer Science**  
Dr. Rafiq Zakaria Centre for Higher Learning and Advanced Research, Aurangabad  
*2021–2023  

**Bachelor's in Computer Science**  
Maulana Azad College, Aurangabad  
*2018–2021 

---

## 🏆 Achievements

* 🥇 Secured Rank 1 in College Academics.
* 📚 Assisted teachers in designing assignments and learning materials.

---

## 🤝 Let's Connect

* 💼 **LinkedIn:** [Mahevish Fatema](https://www.linkedin.com/in/mahevishfatema07/)
* 🐙 **GitHub:** [siddiquimahevishfatema](https://github.com/siddiquimahevishfatema)
* 🌐 **Portfolio:** [Live Portfolio Site](https://siddiquimahevishfatema.github.io/mahevish_fatema.github.io/)
* 📧 **Email:** [siddiquimahevish07@gmail.com](mailto:siddiquimahevish07@gmail.com)

---

⭐ Feel free to explore my repositories as I continue building and documenting my DevOps journey.
