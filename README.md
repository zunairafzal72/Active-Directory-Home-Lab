# Active Directory Home Lab

## Overview

This project documents a personal home lab built to practice real-world system administration and IT support tasks using Active Directory.

The goal of the lab was to simulate a small company environment where common help desk tasks can be performed, such as creating user accounts, resetting passwords, joining computers to a domain, and applying Group Policy settings.

The lab was created using Oracle VirtualBox to host a Windows Server acting as a Domain Controller and a Windows client machine joined to the domain.

This project reflects the type of work typically handled by IT Service Desk analysts, Desktop Support technicians, and junior system administrators.

---

## Lab Environment

Hypervisor  
Oracle VirtualBox

Domain Controller  
Windows Server 2022

Client Machine  
Windows 11

Directory Service  
Active Directory Domain Services

Domain Name  
company.local

---

## Lab Architecture

The environment consists of one Domain Controller and one client machine connected on the same virtual network.

Windows 11 Client  
↓  
Domain Controller (Windows Server 2022)  
Active Directory + DNS

The Domain Controller manages authentication, directory services, and domain policies for the environment.

---

## Skills Practiced in This Lab

Through this lab I practiced several common administrative and help desk tasks including:

- Installing Active Directory Domain Services
- Promoting a server to a Domain Controller
- Creating Organizational Units
- Creating and managing user accounts
- Resetting user passwords
- Unlocking locked user accounts
- Joining computers to a domain
- Managing security groups
- Applying basic Group Policy settings
- Troubleshooting login and authentication issues

These tasks closely mirror the daily responsibilities of many IT support roles.

---

## Why I Built This Lab

Many entry-level IT jobs require familiarity with Active Directory and domain environments. Since I wanted to gain hands-on experience outside of a production workplace, I built this lab to simulate a real company network.

Working in this environment allowed me to understand how identity management works in Windows-based enterprise environments and how IT support teams manage users and computers.

---

## Project Structure

Active-Directory-Home-Lab

README.md  
Install-Active-Directory.md  
Create-Users.md  
Password-Reset.md  
Unlock-Account.md  
Join-Computer-To-Domain.md  
Group-Policy.md

Each document explains a specific task performed within the lab environment.

---

## Possible Improvements

Future improvements to this lab could include:

- Adding more client machines
- Creating multiple Organizational Units for departments
- Implementing file servers
- Deploying login scripts
- Practicing Group Policy management in greater depth
- Simulating additional help desk scenarios

---

## Author

Zunair Afzal

This repository is part of my learning process while developing practical IT support and system administration skills.
