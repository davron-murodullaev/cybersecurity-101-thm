<img width="1709" height="756" alt="Screenshot 2025-07-29 103936" src="https://github.com/user-attachments/assets/d6712dc5-a502-43cc-b19c-a4455a6ef95e" />
# Section 1: Start Your Cybersecurity Journey

## 🧭 Overview

This introductory module sets the foundation for your cybersecurity learning journey. It provides an essential overview of the field of cybersecurity, including the roles of offensive and defensive security. You'll also gain insight into how ethical hackers think and operate, and perform your first hands-on challenge simulating a real-world attack scenario in a safe virtual environment.

## 📌 Key Concepts

| Topic               | Description |
|---------------------|-------------|
| Cybersecurity Basics| Understanding the CIA triad: Confidentiality, Integrity, Availability |
| Offensive Security  | Simulating real-world attacks to discover vulnerabilities |
| Defensive Security  | Monitoring, detecting, and responding to threats |
| Ethical Hacking     | Legal hacking to improve system security |
| TryHackMe Platform  | Learning through interactive, gamified labs |

## 🧪 Hands-On Lab: FakeBank Web Challenge

### 🔍 Scenario

You are introduced to a vulnerable web application named **FakeBank**. The goal is to discover hidden pages through directory brute-forcing and simulate an unauthorized money transfer to understand how attackers exploit web flaws and how defenders can prevent such attacks.

### 💻 Tools & Commands Used

```bash
# Discovering hidden directories using gobuster
gobuster dir -u http://fakebank.thm -w /usr/share/wordlists/dirb/common.txt

# Accessing discovered hidden path
http://fakebank.thm/bank-transfer
