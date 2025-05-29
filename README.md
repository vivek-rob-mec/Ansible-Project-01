# Ansible-Project-01
# Ansible Project: Installing Nginx on EC2 Hosts

This project demonstrates how to use **Ansible** from a **Windows system via WSL (Ubuntu)** to automate the installation of **Nginx** on two Amazon EC2 instances.

## 🛠️ Project Overview

- ✅ **Configuration Management Tool**: Ansible
- 🧑‍💻 **Control Node**: WSL (Windows Subsystem for Linux - Ubuntu)
- ☁️ **Target Nodes**: Two EC2 Ubuntu instances
- 🔧 **Objective**: Install and start the **Nginx** web server on both hosts using an Ansible playbook

* ansible -i inventory.ini webserver -m ping
* ansible-playbook -i inventory.ini playbook.yml
