# Section 2: Linux Fundamentals

## 🧭 Overview

Linux is the operating system that powers most servers, cloud infrastructure, containers, and cybersecurity labs. This module strengthens your confidence on the command line by teaching essential commands, file system navigation, process management, user and permission control, utilities, and shell scripting basics — all through interactive TryHackMe labs.

## 📌 Key Concepts & Commands

| Command / Concept       | Description |
|-------------------------|-------------|
| `pwd`, `ls`, `cd`       | Navigate the filesystem and locate files and directories |
| `cat`, `tac`, `head`, `tail`, `xxd`, `base64` | Read, inspect, and manipulate file contents |
| `grep`, `find`, `locate`| Efficiently search for text patterns or files across the system |
| `chmod`, `chown`, `sudo`| Manage file permissions and user ownership |
| `tar`, `gzip`, `7zip`, `binwalk` | Archive or unpack files and examine binaries |
| `ssh`, `curl`, `wget`   | Connect remotely and transfer or fetch content |
| Text Editors: `nano`, `vim` | Modify or create configuration and script files |
| Process Management: `ps`, `top`, `kill`, `systemctl` | Monitor and control running processes and services |
| Cron Jobs & Automation   | Create basic scheduled tasks for system maintenance |
| Shell Basics: `echo`, shell operators (`>`, `>>`, `&`, `&&`) | Use redirection, background execution, and chaining |

## 🧪 Lab Projects (from TryHackMe Linux Fundamentals Parts 1–3)

### Part 1 & 2 – Basics Walkthrough
- Navigate the filesystem: `pwd`, `ls`, `cd`
- Read files: `cat`, `head`, `tail`, `tac`
- Search by content or name: `grep`, `find`
- Use shell redirection and backgrounding (`echo "text" > file.txt`, `&`)
- Identify your login user via `whoami` and explore system structure :contentReference[oaicite:1]{index=1}

### Part 3 – Utilities & Automation
- Edit files using `nano` or `vim`, creating your own script or flag file (e.g. `THM{TEXT_EDITORS}`) :contentReference[oaicite:2]{index=2}
- Start a quick web server with `python3 -m http.server`, fetch a flag using `wget` or `curl` :contentReference[oaicite:3]{index=3}
- Explore process control: find active processes (`ps aux`), kill unwanted ones, and manage services with `systemctl` :contentReference[oaicite:4]{index=4}
- Read logs (e.g., Apache), identify user-access patterns and accessed files :contentReference[oaicite:5]{index=5}

## 🧰 Tools Used

- Bash shell on Ubuntu
- Standard tools: `grep`, `find`, `tar`, `gzip`, `wget`, `curl`, `binwalk`
- Text editors: `nano`, `vim`
- Python HTTP server
- System commands: `systemctl`, `ps`, `cron`

## 🌍 Real-World Relevance

- Most servers and security tools run on Linux — managing systems requires familiarity with CLI.
- Automating routine tasks with shell scripts and cron jobs improves operational efficiency.
- Log analysis, process monitoring, and remote access via SSH are everyday tasks for sysadmins and security professionals.

## 📚 Resources & Further Reading

- [TryHackMe – Linux Fundamentals (module overview)](https://tryhackme.com/module/linux-fundamentals) :contentReference[oaicite:6]{index=6}  
- [Hands‑on walkthrough: Linux Fundamentals Part 1](https://medium.com/@hammaadm/tryhackme-linux-fundamentals-part-i-15453d23c926) :contentReference[oaicite:7]{index=7}  
- [Utilities, file manipulation, and process control labs walkthrough](https://inventyourshit.com/tryhackme-linux-fundamentals-part-3/) :contentReference[oaicite:8]{index=8}

- ## Screenshot
- 
<img width="1700" height="760" alt="Screenshot 2025-07-29 134250" src="https://github.com/user-attachments/assets/a73ae06a-acc5-4281-9ed0-f120026c7c63" />


