# ☁️ Cloud Security with OpenStack

This repository focuses on setting up **DevStack** for exploring **cloud infrastructure** and **security configurations** within the OpenStack ecosystem.

## 📌 Overview

This branch contains scripts and configuration files used for deploying **DevStack**, a flexible and extensible way to install OpenStack for development and testing purposes. It’s ideal for developers, students, and researchers exploring secure OpenStack deployments.

## 🛠️ What’s Inside

- DevStack installation and setup scripts  
- Configuration files (`local.conf`)  
- Notes and tips for common issues during setup  
- Basic security practices to follow when configuring DevStack  

## 🚀 Getting Started

Follow the [official DevStack installation guide](https://docs.openstack.org/devstack/latest/) to set up your environment.

Alternatively, here’s a quick summary:

### 1. Clone DevStack

```bash
git clone https://opendev.org/openstack/devstack
cd devstack
```

### 2. Create `local.conf`

Make sure to customize your `local.conf` file. Example configurations can be found in this repository under the `config` directory.

### 3. Run the Installer

```bash
./stack.sh
```

> ⚠️ **Note:** This script can take a while depending on your system and internet speed.

## 🔐 Cloud Security Focus

This repository is also tailored for security-focused setups. We aim to:

- Enable secure default configurations  
- Understand identity and access management in OpenStack (Keystone)  
- Explore secure networking using Neutron  
- Practice isolating tenants/projects  
- Monitor and log security events  

## 📂 Folder Structure

```plaintext
.
├── config/
│   └── local.conf              # Sample configuration file
├── docs/
│   └── security-notes.md       # Security best practices and notes
├── install-guide.md            # Step-by-step setup instructions
└── README.md
```

## ✅ Prerequisites

- Ubuntu-based OS (20.04 or newer recommended)  
- At least 8 GB RAM and 2 CPUs (for this projects, we used 4GB and 4 CPUs)
- Git and Python3 installed (make sure to update your Python to avoid dependency and other issues)
- Internet connection for package installation  

## 💬 Community & Support

- [OpenStack Docs](https://docs.openstack.org/)
- [Ask OpenStack](https://ask.openstack.org/)
- [DevStack Repo](https://opendev.org/openstack/devstack)

## 🧑‍💻 Contributors

This project is maintained by Fify (aka North Blue). Contributions are welcome!