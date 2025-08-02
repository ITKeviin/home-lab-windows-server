# 🖥️ Windows Server Home Lab – AD, GPO, Ticketing System

This project is a self-hosted Windows Server 2022 lab running on Proxmox, designed to simulate a real-world small business IT environment. It includes Active Directory, Group Policy, file sharing, and a Peppermint-based help desk ticketing system.

## 🧩 Network Overview

## 🔧 Lab Components

- **Proxmox Host 1:**  
  - Windows Server 2022 (ADDS, DNS, File Sharing)
- **Physical PC 2:**  
  - VirtualBox running Windows 11 Enterprise client
- **Peppermint Help Desk System**  
  - Self-hosted on Ubuntu VM

## 🧑‍💻 Features Implemented

- Active Directory with domain `lab.local`
- Domain-joined Windows 11 clients
- Group-based file share permissions (NTFS + Share)
- Static IP addressing and DNS
- GPO for mapped drives and user policy enforcement
- Peppermint ticketing system for help desk simulation

## 📸 Screenshots

Screenshots of the working environment can be found in `/screenshots`.

## 📚 Guides

Setup documentation is included under `/docs`:
- Create AD users and groups
- Set up shared folders and permissions
- Deploy and configure Peppermint ticketing

## 🎥 Video Walkthrough

▶️ [Watch on YouTube] Coming Soon!

---

## 🛠️ Tools Used

- Proxmox VE
- VirtualBox
- Windows Server 2022
- Windows 11 Enterprise
- Peppermint Ticketing System
- Group Policy Editor (GPO)
