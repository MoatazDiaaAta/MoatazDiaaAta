<h1 align="center">Hi 👋, I'm Moataz Diaa</h1>

<h3 align="center">
  Junior DevOps & Cloud Engineer
</h3>

<p align="center">
  Linux • Bash • Ansible • Git • GitHub • Networking
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/moataz-diaa">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:moataz.diaa.ata@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/MoatazDiaaAta">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## About Me

I'm an Electronics & Communication Engineering student at **Mansoura University** with a growing focus on **DevOps and Cloud Engineering**.

I'm currently developing hands-on experience in Linux systems, Bash automation, Ansible configuration management, Git/GitHub workflows, and networking fundamentals.

I enjoy understanding how systems work, automating repetitive tasks, troubleshooting problems, and building practical solutions through hands-on projects.

- 🎓 **B.Sc. Electronics & Communication Engineering — Mansoura University**
- 📅 Expected Graduation: **2028**
- 🚀 **DEPI — DevOps Track**
- 👨‍💻 Current Focus: **DevOps & Cloud Engineering**
- 🐧 Linux & Bash
- ⚙️ Ansible Automation
- 🔧 Git & GitHub
- 🌐 Networking Fundamentals
- 🌍 Cloud Fundamentals
- 👥 **Team Leader — DEPI DevOps Training Group**

---

## 🛠️ Technical Skills

### Operating Systems & Networking

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white"/>
  <img src="https://img.shields.io/badge/Networking-Fundamentals-2F80ED?style=flat"/>
  <img src="https://img.shields.io/badge/DNS-Fundamentals-444444?style=flat"/>
</p>

### Automation & Configuration Management

<p>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white"/>
</p>

### Version Control

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
</p>

### Cloud

<p>
  <img src="https://img.shields.io/badge/Cloud-Foundations-4285F4?style=flat"/>
  <img src="https://img.shields.io/badge/Cloud%20Engineering-Learning-6C63FF?style=flat"/>
</p>

> My current focus is building a strong DevOps foundation and expanding my practical Cloud Engineering skills.

---

## 🚀 Featured Projects

### 1. Automated Network Monitor with Self-Healing

A Bash-based network monitoring script developed on an **Ubuntu virtual machine**.

The script:

- Checks connectivity to `google.com`
- Runs automatically every **5 minutes**
- Records successful and failed checks with timestamps
- Tracks consecutive failures
- Triggers a recovery action after **3 consecutive failures**
- Restarts `NetworkManager` as the recovery mechanism
- Writes monitoring results to a log file
- Uses Linux permissions and `systemctl`

**Technologies:**

`Linux` `Ubuntu` `Bash` `systemctl` `Networking`

---

### 2. Ansible Provisioning & Nginx Deployment

A hands-on Ansible automation project using a control node and managed node.

The project automates:

- User and group creation
- Directory and configuration setup
- Package installation
- Nginx installation and configuration
- Website deployment
- Service management
- Handler-based Nginx restart
- Deployment verification

The environment was structured around:

```text
master
   │
   │ Ansible
   ▼
worker01
