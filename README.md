# Hi 👋, I'm Moataz Diaa

## Junior DevOps & Cloud Engineer

**Linux • Bash • Ansible • Docker • Kubernetes • CI/CD • Terraform • AWS**

I am an Electronics and Communication Engineering student at **Mansoura University**, building my career toward **DevOps and Cloud Engineering** through hands-on learning, infrastructure automation, containerization, orchestration, CI/CD pipelines, and cloud technologies.

I enjoy building practical projects, automating infrastructure, solving technical challenges, and continuously expanding my knowledge of modern DevOps tools and practices.

<p align="left">
  <a href="https://www.linkedin.com/in/moataz-diaa">
    <img src="https://img.shields.io/badge/LinkedIn-Moataz%20Diaa-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:moataz.diaa.ata@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email">
  </a>
  <a href="https://github.com/MoatazDiaaAta">
    <img src="https://img.shields.io/badge/GitHub-MoatazDiaaAta-black?style=for-the-badge&logo=github" alt="GitHub">
  </a>
</p>

---

## 🌐 Portfolio Website

<p align="left">
  <a href="YOUR_PORTFOLIO_URL">
    <img src="https://img.shields.io/badge/Visit%20My%20Portfolio-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio Website">
  </a>
</p>

> Portfolio website featuring my DevOps profile, services, technical skills, and hands-on projects.

---

## 👨‍💻 About Me

- 🎓 Electronics and Communication Engineering student at **Mansoura University**.
- 🚀 Building my career toward **DevOps & Cloud Engineering**.
- 🐧 Hands-on experience with Linux and Ubuntu environments.
- ⚙️ Practicing automation and configuration management using Bash and Ansible.
- 🐳 Learning containerization and application deployment using Docker and Docker Compose.
- ☸️ Exploring container orchestration using Kubernetes.
- 🔄 Working with CI/CD concepts and tools such as Jenkins and GitLab CI/CD.
- ☁️ Developing practical Cloud Engineering skills using AWS.
- 🏗️ Currently learning Infrastructure as Code (IaC) using Terraform.
- 👥 Team Leader in the DEPI DevOps training track.

My goal is to build reliable, scalable, and automated infrastructure through continuous learning and hands-on projects.

---

# 🛠️ Technical Skills

## Operating Systems & Linux

- Linux
- Ubuntu
- Linux Filesystem
- Users and Groups Management
- File Permissions
- Processes and Services
- systemctl
- Basic Linux Troubleshooting
- Server Administration Fundamentals

## Networking

- Networking Fundamentals
- TCP / UDP
- DNS Fundamentals
- Connectivity Troubleshooting
- Netplan
- UFW
- ping
- nmap
- netstat

## Automation & Configuration Management

- Bash Scripting
- Ansible
- Ansible Playbooks
- Ansible Roles
- Variables and Loops
- Handlers
- Ansible Galaxy
- Configuration Management
- Infrastructure Automation

## Containerization & Orchestration

- Docker
- Docker Images and Containers
- Dockerfile
- Docker Volumes
- Docker Networking
- Docker Compose
- Kubernetes Fundamentals
- Kubernetes Architecture
- kubeadm
- Pods, Deployments, and Services
- Container Orchestration Fundamentals

## CI/CD & Version Control

- Git
- GitHub
- GitLab
- Jenkins
- GitLab CI/CD
- CI/CD Pipeline Fundamentals
- Git Branching and Workflows
- Repository Management
- Automated Build and Deployment Concepts

## Cloud & Infrastructure as Code

- Amazon Web Services (AWS)
- EC2
- S3
- AWS CLI
- Cloud Computing Fundamentals
- Terraform (Currently Learning)
- Infrastructure as Code (IaC) Fundamentals

## Web Servers

- Nginx
- Nginx Deployment Using Ansible
- Service Management
- Basic Web Server Configuration

---

# 🚀 Featured Projects

## 1. Automated Network Monitor with Self-Healing

A Linux and Bash automation project built on an Ubuntu virtual machine.

The project continuously monitors network connectivity and automatically attempts recovery when repeated connectivity failures are detected.

### 🔧 Technologies

- Linux
- Ubuntu
- Bash
- Networking
- ping
- systemctl
- NetworkManager

### ⚙️ How It Works

The script:

1. Checks connectivity to google.com.
2. Logs the result with a timestamp.
3. Tracks consecutive connection failures.
4. Allows up to 3 consecutive failures.
5. Restarts NetworkManager when the failure threshold is reached.
6. Continues monitoring every 5 minutes.

### 🎯 What I Practiced

- Bash Scripting
- Conditional Logic and Loops
- Linux Commands
- Service Management
- Network Connectivity Monitoring
- Troubleshooting

---

## 2. Ansible Provisioning & Nginx Deployment

An infrastructure automation project using Ansible to configure a managed Ubuntu node and deploy an Nginx web server.

The project uses a control node and a managed node.

### 🏗️ Architecture

```text
┌──────────────────────┐
│     Control Node     │
│        master        │
│                      │
│       Ansible        │
└──────────┬───────────┘
           │ SSH
           ▼
┌──────────────────────┐
│     Managed Node     │
│       worker01       │
│                      │
│        Nginx         │
└──────────────────────┘
```

### 🔧 Technologies

- Ansible
- Linux
- Ubuntu
- Nginx
- SSH
- YAML

### ⚙️ What the Automation Does

- Creates users and groups.
- Creates required directories.
- Manages configuration files.
- Installs required packages.
- Installs and configures Nginx.
- Deploys a website file.
- Starts and enables the Nginx service.
- Uses handlers to restart Nginx when changes occur.
- Verifies the deployment from the control node.

### 🎯 What I Practiced

- Ansible Inventory
- Playbooks and Tasks
- Modules and Variables
- Loops and Handlers
- Roles
- Package Installation
- Service Management
- Configuration Management

---

## 3. Kubernetes Cluster Deployment

A hands-on project focused on deploying and managing a Kubernetes cluster using kubeadm on Ubuntu virtual machines.

### 🔧 Technologies

- Kubernetes
- kubeadm
- containerd
- Ubuntu
- Linux
- Flannel (CNI)
- Bash

### ⚙️ What I Practiced

- Kubernetes Cluster Architecture
- Control Plane and Worker Nodes
- Cluster Initialization
- Worker Node Joining
- Container Runtime Configuration
- Pod and Service Management
- CNI Networking
- Flannel Deployment
- Cluster Troubleshooting
- Kubernetes YAML Manifests

The project helped me understand how Kubernetes manages containerized workloads and provides networking and orchestration across multiple nodes.

---

## 4. DEPI E-Commerce Final Project

A team-based E-Commerce project developed as part of the Digital Egypt Pioneers Initiative (DEPI) DevOps training track.

### 🔧 Technologies & Tools

- Docker
- Docker Compose
- Jenkins
- GitLab
- CI/CD
- Git
- Linux

### 🎯 Focus Areas

- Containerization
- Application Deployment
- CI/CD Pipeline Concepts
- Version Control and Collaboration
- DevOps Workflow Integration

*More project details and implementation documentation will be added as the project progresses.*

---

# 📚 Currently Learning

I am continuously expanding my DevOps and Cloud Engineering knowledge, with a focus on the following areas:

## DevOps & Automation

- Advanced Linux Administration
- Bash Scripting
- Ansible Automation
- Docker & Docker Compose
- Kubernetes
- CI/CD with Jenkins and GitLab
- Infrastructure Automation

## Cloud Engineering

- AWS Services and Architecture
- EC2 and S3
- Cloud Infrastructure Deployment
- AWS CLI
- Cloud Networking

## Infrastructure as Code

- Terraform Fundamentals
- Infrastructure as Code Concepts
- Resource Provisioning
- Terraform Configuration and State Management

My current focus is connecting these technologies into practical workflows and building automated, scalable infrastructure.

---

# 👥 Leadership

## Team Leader — DEPI DevOps Track

I currently serve as a **Team Leader within the DEPI DevOps training track**.

This is a training and learning responsibility rather than professional employment.

Through this role, I am developing:

- Team Coordination
- Technical Collaboration
- Communication
- Problem Solving
- Responsibility
- Technical Discussion

---

# 🎓 Education

## Mansoura University

**Faculty of Engineering — Electronics and Communication Engineering**

Expected Graduation: **2028**

---

# 📜 Training & Certifications

## Digital Egypt Pioneers Initiative (DEPI)

**DevOps Track**

Focused on practical learning across:

- Linux
- Bash
- Networking
- Ansible
- Git & GitHub
- Docker
- Cloud Engineering Fundamentals
- DevOps Practices

---

# 💼 Career Interests

I am interested in opportunities related to:

- DevOps Engineering
- Cloud Engineering
- Infrastructure Automation
- Containerization & Orchestration
- CI/CD Engineering
- Infrastructure as Code
- Linux Administration
- Cloud Infrastructure

---

# 📫 Let's Connect

If you are interested in discussing a project, collaboration, or entry-level DevOps opportunity, feel free to reach out.

<p align="left">
  <a href="https://www.linkedin.com/in/moataz-diaa">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="mailto:moataz.diaa.ata@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email">
  </a>
</p>

### Contact

**Email:** moataz.diaa.ata@gmail.com

**LinkedIn:** https://www.linkedin.com/in/moataz-diaa

**GitHub:** https://github.com/MoatazDiaaAta

---

# ⭐ Thanks for Visiting

Thanks for taking the time to explore my profile!

I am continuously learning, building practical projects, and developing my skills toward becoming a strong **DevOps & Cloud Engineer**.
