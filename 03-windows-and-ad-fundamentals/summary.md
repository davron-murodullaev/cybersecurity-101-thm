# Section 3: Windows & Active Directory Fundamentals

## 🧭 Overview

This module covers essential Windows security foundations and Active Directory (AD), the backbone of identity management in enterprise networks. You’ll explore NTFS permissions, User Account Control (UAC), registry editing, and the structure of AD domains, groups, and policies. By completing this section, you will understand how Windows environments are structured and secured.

## 📌 Key Concepts

| Topic                      | Description                                                                    |
|---------------------------|--------------------------------------------------------------------------------|
| NTFS File Permissions     | Understanding Ownership and Access Control Lists on Windows file systems       |
| UAC (User Account Control)| How Windows handles privileges and elevation                                 |
| Windows Registry          | Editing and inspecting system configuration via `regedit`                      |
| Event Logs & Monitoring   | Investigating system and security events using Event Viewer                    |
| Active Directory (AD)     | Managing users, groups, OUs, and domain controllers                             |
| Group Policy Objects (GPO)| Centralized policy enforcement across the network                              |
| Trust Domains & Forests   | Managing inter-domain and inter-forest access                                  |

---

## 🧪 Hands‑On Labs & Tasks

### 💻 Windows Fundamentals Lab (TryHackMe)

- Explore Windows GUI tools including **Task Manager**, **Resource Monitor**, **Event Viewer**, and **regedit**.
- Learn about NTFS permissions and how UAC controls elevated access levels.

### 🧑‍💼 Active Directory Basics (TryHackMe)

- Log in as Domain Admin and list all domain users and groups using PowerShell:  
  ```powershell
  Get‑ADUser –Filter * | Select‑Object Name,Enabled
  Get‑ADGroup –Filter * | Select‑Object Name
  ```

  
### Screenshot

<img width="1749" height="944" alt="image" src="https://github.com/user-attachments/assets/baeeece0-211b-473d-ada0-cbb7bd8d6c87" />
