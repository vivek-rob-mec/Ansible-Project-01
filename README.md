# Ansible-Project-01
# Ansible Project: Installing Nginx on EC2 Hosts

This project demonstrates how to use **Ansible** from a **Windows system via WSL (Ubuntu)** to automate the installation of **Nginx** on two Amazon EC2 instances.

## 🛠️ Project Overview

- ✅ **Configuration Management Tool**: Ansible
- 🧑‍💻 **Control Node**: WSL (Windows Subsystem for Linux - Ubuntu)
- ☁️ **Target Nodes**: Two EC2 Ubuntu instances
- 🔧 **Objective**: Install and start the **Nginx** web server on both hosts using an Ansible playbook

* run: ssh -i ~/.ssh/ansible-projet-01.pem ec2-user@ec2-13-127-51-189.ap-south-1.compute.amazonaws.com to connect to specific ec2 host machine
* ansible -i inventory.ini webserver -m ping
* ansible-playbook -i inventory.ini nginx_install.yml
