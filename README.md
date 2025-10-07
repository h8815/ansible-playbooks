
# Ansible Playbook Practice

Welcome to the **Ansible Playbook Practice** repository! This repository contains practice playbooks, roles, and inventories to help you learn and master Ansible automation.

---

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Practice Playbooks](#practice-playbooks)
- [Contributing](#contributing)

---

## Introduction

Ansible is an open-source automation tool used for configuration management, application deployment, and task automation. This repository is designed for hands-on practice with Ansible playbooks, roles, and inventories.  

By working through the examples, you will learn how to:

- Automate server setup
- Deploy applications
- Manage users and permissions
- Work with roles and inventories
- Utilize Ansible modules effectively

---

## Prerequisites

Before you start, ensure you have:

- A machine with **Linux** or **macOS** (Windows with WSL works too)
- **Ansible 2.9+** installed
- SSH access to target nodes (for remote host testing)
- Basic knowledge of **YAML** and **Linux commands**

Check your Ansible installation:

```bash
ansible --version
```

---

## Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/h8815/ansible-playbooks.git
cd ansible-playbook-practice
```

2. **Install role dependencies (if using Ansible Galaxy):**

```bash
ansible-galaxy install -r requirements.yml
```

3. **Run a playbook:**

```bash
ansible-playbook -i inventories/dev/hosts playbooks/setup.yml
```

Replace `inventories/dev/hosts` and `playbooks/setup.yml` with your desired inventory and playbook.

---

## Practice Playbooks

- `setup.yml` – Basic system setup and package installation  
- `deploy.yml` – Application deployment example  
- `users.yml` – User management and SSH key setup  

Feel free to add your own playbooks and experiment with different Ansible modules.

---

## Contributing

Contributions are welcome! You can:

- Add new practice playbooks
- Create and improve roles
- Fix issues and improve documentation

To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a pull request

---

Happy automating! 🚀

