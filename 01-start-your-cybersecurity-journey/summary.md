# Section 1: Start Your Cybersecurity Journey

## 🧭 Overview

This module introduces what cybersecurity is, the different domains within the field, and how hackers think. You will gain insight into ethical hacking, how attackers approach systems, and how defenders respond. You’ll also perform your first hands-on lab simulating a web application vulnerability.

## 📌 Key Concepts

| Topic               | Description |
|---------------------|-------------|
| Cybersecurity Basics| Understanding the CIA triad: Confidentiality, Integrity, Availability |
| Offensive Security  | Simulating real-world attacks to find vulnerabilities |
| Defensive Security  | Monitoring and protecting systems from threats |
| Ethical Hacking     | Legal hacking to strengthen security |
| TryHackMe Platform  | Learning in a virtual lab environment |

## 🧪 Hands-On Lab: FakeBank Web Challenge

### 🔍 Scenario

You access a vulnerable web application called **FakeBank**, which has a hidden directory. Using enumeration techniques, you discover and access it, then simulate an unauthorized bank transfer.

### 💻 Tools & Commands Used

```bash
# Directory brute forcing with gobuster
gobuster dir -u http://fakebank.thm -w /usr/share/wordlists/dirb/common.txt

# Discover the hidden path: /bank-transfer
# Simulate the attack by visiting the URL and transferring funds


## 📷 Screenshot

![Start Your Cyber Security Journey](<img width="1709" height="756" alt="image" src="https://github.com/cybersecurity-101-thm/01-start-your-cybersecurity-journey/sections-1"/>)


