# 🟢 Linux Beginner Level Notes

## 1. What is Linux? History and Distributions
Linux is an open-source Unix-like operating system kernel developed by Linus Torvalds in 1991. It is widely used in servers, desktops, mobile devices, and embedded systems.

### Popular Distributions:
- Ubuntu
- CentOS
- Debian
- Fedora
- Arch Linux


# 🐧 What is Linux? History and Distributions

## ✅ What is Linux?

**Linux** is a free and open-source operating system (OS) based on **UNIX**. It acts as an interface between a computer's hardware and software, managing system resources and allowing users to interact with the machine.

Linux is known for being:
- **Stable**
- **Secure**
- **Flexible**
- **Free to use and modify**

It powers a wide range of systems: from smartphones and servers to supercomputers and IoT devices.

---

## 🕰️ Brief History of Linux

| Year | Milestone |
|------|-----------|
| **1969** | UNIX was developed at Bell Labs by Ken Thompson and Dennis Ritchie. |
| **1983** | Richard Stallman started the **GNU Project** to create a free Unix-like OS. |
| **1991** | **Linus Torvalds**, a Finnish student, released the first Linux kernel (version 0.01) and combined it with GNU utilities. |
| **1992** | Linux was released under the **GNU General Public License (GPL)**. |
| **Today** | Linux is maintained by a global community and supported by organizations like the **Linux Foundation**. |

---

## 🧩 Linux Distributions (Distros)

A **Linux distribution (or distro)** is a complete OS built from the Linux kernel and a collection of software, package managers, and desktop environments.

### 🔸 Popular Linux Distributions

| Distro | Description | Target Users |
|--------|-------------|--------------|
| **Ubuntu** | User-friendly, Debian-based, good for beginners and servers. | Beginners, Developers |
| **Debian** | Stable and versatile, base for many other distros. | Advanced Users, Servers |
| **CentOS / Rocky Linux** | Red Hat-based, used in enterprises and servers. | Enterprises |
| **Fedora** | Cutting-edge features, sponsored by Red Hat. | Developers, Testers |
| **Arch Linux** | Lightweight, rolling release, fully customizable. | Advanced Users |
| **Kali Linux** | Security-focused distro used for penetration testing. | Ethical Hackers |
| **Linux Mint** | Ubuntu-based, designed for ease of use and productivity. | Beginners, Home Users |
| **openSUSE** | Stable and enterprise-friendly, with YaST configuration tool. | Developers, SysAdmins |

---

## 🧠 Key Concepts

- **Kernel**: The core of the OS; manages hardware.
- **Shell**: Command-line interpreter for user interaction.
- **Package Manager**: Tool to install/update software (e.g., `apt`, `yum`, `dnf`, `pacman`).
--------------------------------------------------------------------



## 2. Linux Installation (Ubuntu/CentOS)
# AWS Lab Setup

## 1. Create an AWS Account
- Sign up at: [AWS Signup Link](https://signin.aws.amazon.com/signup?request_type=register)  
- Reference PPT: [AWS Setup Guide](https://docs.google.com/presentation/d/12kD5Rs9MEpfGMqweTB0kTGzXKAz-6N9L/edit?usp=sharing&ouid=111596827579688305692&rtpof=true&sd=true)

## 2. Log in to Your AWS Account
- Use your registered credentials to access [AWS Console](https://aws.amazon.com/console/).

## 3. Launch an EC2 Instance
1. Go to **EC2 Dashboard** → **Launch Instance**.
2. Choose an **AMI (Amazon Machine Image)** (e.g., Amazon Linux, Ubuntu).
3. Select an instance type (**t2.micro** for free-tier users).
4. Configure networking (default settings work for now).
5. **Download the key pair (.pem file)** for SSH access.
6. Launch the instance.

## 4. Connect to the EC2 Instance
Use any of the following SSH tools:

### **SSH Tools (Windows & Mac)**
| Tool | Download Link |
|------|--------------|
| **GitBash (Windows)** | [Download](https://git-scm.com/downloads) |
| **Putty** | [Download](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) |
| **Super Putty** | [Download](https://github.com/jimradford/superputty) |
| **MobXterm** | [Download](https://mobaxterm.mobatek.net/download.html) |
| **Mac Terminal** | Pre-installed |

### **SSH Connection Command**
For GitBash or Mac Terminal:
```bash
ssh -i "your-key.pem" ec2-user@your-ec2-public-ip


