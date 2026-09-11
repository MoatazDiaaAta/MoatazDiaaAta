# Hi 👋, I'm Moataz Diaa

## Junior DevOps & Cloud Engineer

**Linux • Bash • Ansible • Git • GitHub • Networking**

I am an Electronics and Communication Engineering student at **Mansoura University**, building my career toward **DevOps and Cloud Engineering** through hands-on learning, Linux administration, automation, configuration management, and infrastructure-focused projects.

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

- 🎓 Electronics and Communication Engineering student at **Mansoura University**
- 🚀 Building my career toward **DevOps & Cloud Engineering**
- 🐧 Hands-on experience with **Linux and Ubuntu**
- ⚙️ Practicing automation with **Bash and Ansible**
- 🔧 Working with **Git and GitHub**
- 🌐 Studying **Linux networking fundamentals**
- 🛠️ Building practical infrastructure and automation projects
- 👥 **Team Leader** in the DEPI DevOps training track
- 📚 Currently expanding my knowledge in **DevOps and Cloud Engineering**

My current focus is building a strong technical foundation and turning what I learn into practical, documented projects.

---

# 🛠️ Technical Skills

## Operating Systems & Linux

- Linux
- Ubuntu
- Linux filesystem
- Users and groups
- File permissions
- Processes and services
- `systemctl`
- Basic Linux troubleshooting
- Basic server administration

## Networking

- Networking fundamentals
- TCP / UDP fundamentals
- DNS fundamentals
- Connectivity troubleshooting
- Basic network monitoring
- Netplan
- UFW
- `ping`
- `nmap`
- `netstat`

## Automation & Configuration Management

- Bash scripting
- Ansible
- Ansible Playbooks
- Ansible Roles
- Variables
- Loops
- Handlers
- Ansible Galaxy
- Configuration management
- Basic infrastructure automation

## Web Server

- Nginx
- Nginx deployment using Ansible
- Service management
- Basic web server configuration

## Version Control

- Git
- GitHub
- Git repositories
- Branching fundamentals
- Git workflow
- Repository management

## Cloud

- Cloud Engineering fundamentals
- Currently expanding practical Cloud Engineering skills

> My current focus is strengthening my DevOps foundation and continuing to build practical Cloud Engineering knowledge.

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
- `ping`
- `systemctl`
- NetworkManager

### ⚙️ How It Works

The script:

1. Checks connectivity to `google.com`
2. Logs the result with a timestamp
3. Tracks consecutive connection failures
4. Allows up to 3 consecutive failures
5. Restarts `NetworkManager` when the failure threshold is reached
6. Continues monitoring every 5 minutes

### 🧩 Core Logic

```bash
#!/bin/bash

TARGET="google.com"
LOGFILE="$HOME/network_monitor.log"
MAX_FAILS=3
FAIL_COUNT=0

while true
do
    if ping -c 1 "$TARGET" > /dev/null 2>&1
    then
        echo "$(date): Network is UP" >> "$LOGFILE"
        FAIL_COUNT=0
    else
        echo "$(date): Network is DOWN" >> "$LOGFILE"
        FAIL_COUNT=$((FAIL_COUNT + 1))

        if [ "$FAIL_COUNT" -ge "$MAX_FAILS" ]
        then
            echo "$(date): Restarting NetworkManager" >> "$LOGFILE"
            sudo systemctl restart NetworkManager
            FAIL_COUNT=0
        fi
    fi

    sleep 300
done
```

### 🎯 What I Practiced

- Bash scripting
- Conditional logic
- Loops
- Linux commands
- Service management
- File permissions
- Network connectivity monitoring
- Troubleshooting Bash and permission issues

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
           │
           │ SSH
           ▼
┌──────────────────────┐
│    Managed Node      │
│      worker01        │
│                      │
│       Nginx          │
└──────────────────────┘
```

### 🔧 Technologies

- Ansible
- Linux
- Ubuntu
- Nginx
- SSH
- YAML
- Ansible Roles

### ⚙️ What the Automation Does

The Ansible automation was used to:

- Create users and groups
- Create required directories
- Create and manage configuration files
- Install required packages
- Install Nginx
- Deploy a website file
- Start and enable the Nginx service
- Use a handler to restart Nginx when configuration/content changes
- Verify the deployment from the control node

### 📁 Role Structure

```text
roles/
└── webserver/
    ├── defaults/
    │   └── main.yml
    ├── handlers/
    │   └── main.yml
    ├── tasks/
    │   └── main.yml
    ├── templates/
    ├── files/
    └── vars/
        └── main.yml
```

### ▶️ Ansible Execution

The playbook was checked for syntax before execution and then executed against the managed node.

The execution completed successfully with:

```text
ok=6
changed=3
unreachable=0
failed=0
```

### 🔍 Verification

The deployed web server was verified from the control node using `curl`.

```bash
curl http://worker01
```

### 🎯 What I Practiced

- Ansible inventory
- Playbooks
- Tasks
- Modules
- Variables
- Loops
- Handlers
- Roles
- Package installation
- Service management
- Nginx deployment
- Configuration management
- Deployment verification

---

# 📚 Currently Learning

## DevOps

- Linux administration
- Bash automation
- Ansible automation
- Configuration management
- Git & GitHub workflows
- Networking fundamentals
- Infrastructure automation
- System troubleshooting

## Cloud Engineering

I am currently expanding my practical Cloud Engineering knowledge and connecting cloud concepts with the DevOps skills I have been developing.

---

# 👥 Leadership

## Team Leader — DEPI DevOps Track

I currently serve as a **Team Leader within the DEPI DevOps training track**.

This is a training and learning responsibility rather than professional employment.

Through this role, I am developing:

- Communication
- Collaboration
- Team coordination
- Responsibility
- Technical discussion
- Problem solving

---

# 🎓 Education

## Mansoura University

**Faculty of Engineering — Electronics and Communication Engineering**

Expected Graduation: **2028**

---

# 📜 Training

## Digital Egypt Pioneers Initiative — DEPI

**DevOps Track**

Focused on practical learning across:

- Linux
- Bash
- Networking
- Ansible
- Git
- GitHub
- DevOps fundamentals
- Cloud Engineering fundamentals

---

# 💼 Career Interests

I am interested in opportunities related to:

- DevOps Engineering
- Cloud Engineering
- Linux Administration
- Infrastructure Automation
- Configuration Management
- Bash Automation
- Networking
- System Troubleshooting

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

Thanks for taking the time to explore my profile.

I am continuously learning, building practical projects, and developing my skills toward becoming a strong **DevOps & Cloud Engineer**.
