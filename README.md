# Cloud Infrastructure Labs

## About This Project

I am an IT professional with over 10 years of experience in enterprise IT operations, technical support, and Major Incident Management.

I am currently expanding my technical skills in Systems Administration and Microsoft Azure Cloud Infrastructure, with a focus on hands-on learning and practical experience.

This repository documents my learning journey through practical labs involving operating systems, virtualisation, networking, server configuration, identity management, infrastructure automation, and troubleshooting.

My goal is to transition into a more hands-on technical role focused on infrastructure administration and cloud technologies.

## Lab 01 — Ubuntu Server Administration

### Overview

This lab focuses on deploying and configuring an Ubuntu Server virtual machine using Oracle VirtualBox and establishing remote access from a Windows computer.

The objective is to gain practical experience with Linux server administration, virtualisation, networking, and remote connectivity.

### Lab Environment

| Component | Configuration |
|---|---|
| Host Operating System | Windows |
| Virtualisation Platform | Oracle VirtualBox |
| Guest Operating System | Ubuntu Server |
| Network Configuration | NAT |
| Remote Access Protocol | SSH |
| Host Port | 2222 |
| Guest Port | 22 |
| Client | Windows PowerShell |

### Tasks Completed

- Installed Ubuntu Server in Oracle VirtualBox.
- Created and configured a Linux virtual machine.
- Configured NAT networking.
- Configured TCP port forwarding for SSH connectivity.
- Set up SSH remote access.
- Successfully connected to Ubuntu Server from Windows PowerShell.

### Remote Access Configuration

To enable remote administration, I configured port forwarding in VirtualBox to allow SSH connections from the Windows host to the Ubuntu Server virtual machine.

The following command was used in Windows PowerShell:

`ssh -p 2222 cloudlab@127.0.0.1`

The connection was successfully established, allowing remote administration of the Linux server directly from Windows.

### Skills Practised

- Linux Server Installation
- Oracle VirtualBox
- Virtual Machine Configuration
- Basic TCP/IP Networking
- NAT and Port Forwarding
- SSH Remote Administration
- Windows PowerShell
- Basic Infrastructure Troubleshooting

### Challenges and Learning Outcomes

This lab provided practical experience in configuring remote connectivity between a Windows host and a Linux virtual machine.

During the configuration process, the initial connectivity test failed. The issue was identified as the virtual machine not being powered on.

After starting the virtual machine and confirming the configuration, the SSH connection was successfully established.

This exercise helped reinforce the importance of checking system availability and connectivity when troubleshooting infrastructure issues.

### Evidence

#### VirtualBox Network Configuration

![VirtualBox Network](evidence/01-virtualbox-network.png)

#### Ubuntu Server Information

![Ubuntu Server](evidence/02-ubuntu-server.png)

#### SSH Connection

![SSH Connection](evidence/03-ssh-connection.png)

#### SSH Service and Firewall

![SSH and Firewall](evidence/04-ssh-firewall.png)

---

## Learning Roadmap

This learning roadmap is designed to develop practical infrastructure administration skills through hands-on labs, technical documentation, and independent experimentation.

**Estimated duration:** 6 months

**Weekly commitment:** Approximately 6 hours

**Primary focus:** Windows Server, Linux, Microsoft Azure, Networking, and Infrastructure Administration.

The schedule is flexible and may be extended to allow additional practice and consolidation of technical skills.

### Month 1 — Linux Fundamentals

**Objective:** Build foundational Linux server administration skills.

**Topics:**
- Ubuntu Server installation and configuration
- Linux terminal commands
- File system navigation and management
- User accounts and file permissions
- SSH and remote administration
- Linux services and system logs
- Basic networking and troubleshooting
- System updates and package management
- Introduction to GitHub documentation

**Practical Project:**

Deploy and administer an Ubuntu Server virtual machine using Oracle VirtualBox, configure remote access, manage services, and document troubleshooting exercises.

**Expected Outcome:**

Ability to perform basic Linux administration tasks and troubleshoot common server connectivity issues.

### Month 2 — Windows Server & Active Directory

**Objective:** Develop practical Windows Server administration and identity management skills.

**Topics:**
- Windows Server installation and configuration
- Server Manager and administrative tools
- Introduction to Active Directory Domain Services (AD DS)
- Domain Controller configuration
- Organisational Units (OUs)
- User and group administration
- Introduction to Group Policy Objects (GPO)
- Windows Server remote administration
- Basic PowerShell commands

**Practical Project:**

Create a Windows Server virtual machine, configure an Active Directory domain, create users and groups, and apply basic Group Policies.

**Expected Outcome:**

Understanding of Windows Server administration, domain environments, and centralised user management.

### Month 3 — Networking & PowerShell

**Objective:** Strengthen networking knowledge and develop basic automation skills.

**Topics:**
- TCP/IP fundamentals
- IPv4 addressing and subnetting
- DNS and DHCP configuration
- Network connectivity troubleshooting
- Windows and Linux networking tools
- PowerShell fundamentals
- Basic administrative scripts
- Joining computers to an Active Directory domain
- Introduction to cloud computing
- Microsoft Azure Fundamentals (AZ-900) preparation

**Practical Project:**

Build a small virtual network with Windows Server and client machines, configure DNS and DHCP, and create PowerShell scripts for basic administrative tasks.

**Expected Outcome:**

Ability to configure basic networking services, troubleshoot connectivity, and automate simple system administration tasks.

### Month 4 — Microsoft Azure & Entra ID

**Objective:** Understand Azure cloud services and cloud-based identity administration.

**Topics:**
- Microsoft Azure Portal
- Azure subscriptions and resource groups
- Introduction to Azure Virtual Machines
- Azure storage fundamentals
- Azure networking fundamentals
- Microsoft Entra ID
- Users and groups in Microsoft Entra ID
- Azure Role-Based Access Control (RBAC)
- Identity and access administration
- Azure resource management
- Introduction to Azure CLI

**Practical Project:**

Create a basic Azure environment, configure resource groups, explore Entra ID user and group management, and practise assigning Azure roles.

**Expected Outcome:**

Understanding of Azure resource organisation, cloud identity concepts, and basic administrative operations.

### Month 5 — Azure Infrastructure Administration

**Objective:** Gain hands-on experience deploying and managing Azure infrastructure.

**Topics:**
- Azure Virtual Machine deployment
- Windows and Linux virtual machines in Azure
- Virtual Networks (VNets)
- Subnets and Network Security Groups (NSGs)
- Azure Storage Accounts
- Virtual machine administration
- Azure Monitor and basic alerts
- Backup and recovery fundamentals
- Infrastructure troubleshooting
- Azure cost management

**Practical Project:**

Deploy a small Azure infrastructure environment with virtual machines, networking, storage, and monitoring.

Document the deployment process, configuration steps, and troubleshooting scenarios.

**Expected Outcome:**

Ability to deploy and manage basic Azure infrastructure resources, investigate connectivity issues, and perform routine administrative tasks.

### Month 6 — Infrastructure Automation & Portfolio Development

**Objective:** Introduce infrastructure automation, consolidate technical knowledge, and prepare for Cloud Administrator opportunities.

**Topics:**
- Bash scripting fundamentals
- PowerShell scripting
- Azure CLI administration
- Introduction to Infrastructure as Code (IaC)
- Microsoft Bicep fundamentals
- Deploying Azure resources with Bicep
- Reusable infrastructure configurations
- Microsoft Azure Administrator (AZ-104) preparation
- Technical documentation
- GitHub portfolio organisation

**Practical Project:**

Create a basic Bicep deployment that provisions an Azure virtual network and virtual machine.

Document the architecture, deployment process, configuration, and results.

Consolidate completed projects into a structured technical portfolio.

**Expected Outcome:**

Foundational infrastructure automation skills and a practical portfolio demonstrating Linux, Windows Server, networking, and Azure administration.

---

## Portfolio Projects

The following projects are planned to demonstrate technical progress and hands-on experience.

### Project 01 — Linux Server Administration

**Technologies:** Ubuntu Server, Oracle VirtualBox, SSH, Windows PowerShell

**Status:** Initial installation and SSH connectivity completed.

Practical Linux server installation, configuration, remote administration, and troubleshooting.

### Project 02 — Windows Server & Active Directory

**Technologies:** Windows Server, Active Directory Domain Services, Group Policy, PowerShell

**Status:** Planned.

Deploy a Windows Server domain environment and practise centralised administration of users, groups, and computers.

### Project 03 — Azure Infrastructure Administration

**Technologies:** Microsoft Azure, Virtual Machines, Virtual Networks, Storage, Azure Monitor, Microsoft Entra ID

**Status:** Planned.

Deploy and configure a basic Azure infrastructure environment, including virtual machines, networking, identity management, and monitoring.

### Project 04 — Azure Infrastructure Automation

**Technologies:** Microsoft Bicep, Azure CLI, PowerShell

**Status:** Planned.

Automate the deployment of basic Azure infrastructure resources using Infrastructure as Code.

---

## Technical Skills Development

The following technologies are part of my ongoing learning roadmap.

**Operating Systems**
- Ubuntu Server
- Windows Server

**Virtualisation**
- Oracle VirtualBox
- Virtual Machine Administration

**Networking**
- TCP/IP
- DNS and DHCP
- NAT and Port Forwarding
- SSH
- Virtual Networks

**Identity Administration — Planned**
- Active Directory Domain Services
- Group Policy
- Microsoft Entra ID
- Azure RBAC

**Cloud Technologies — Planned**
- Microsoft Azure
- Azure Virtual Machines
- Azure Virtual Networks
- Azure Storage
- Azure Monitor

**Automation — Planned**
- PowerShell
- Bash
- Azure CLI
- Microsoft Bicep

**Documentation**
- GitHub
- Technical Lab Documentation
- Troubleshooting Notes

---

## Career Objective

My professional background in enterprise IT operations and Major Incident Management has provided me with experience in incident troubleshooting, service availability, technical coordination, operational processes, and technical documentation.

I am building on this experience by developing practical technical skills in Linux, Windows Server, virtualisation, networking, Active Directory, and Microsoft Azure.

My goal is to transition into a Systems Administrator, Infrastructure Administrator, or Cloud Administrator position, focusing on hands-on technical work, system configuration, infrastructure operations, and continuous learning.

This repository serves as a record of my technical development and practical learning experience.

---

## Project Status

**Current Phase:** Month 1 — Linux Fundamentals

**Lab 01:** Ubuntu Server installation and SSH connectivity — Completed

**Current Focus:** Linux administration fundamentals

**Next Lab:** Linux service administration and web server configuration

**Future Milestones:**
- Windows Server and Active Directory lab
- Networking and PowerShell lab
- Microsoft Azure and Entra ID lab
- Azure infrastructure deployment
- Bicep infrastructure automation
- AZ-104 preparation and portfolio consolidation

---

*This repository is a personal learning portfolio. The projects document hands-on training and laboratory experience rather than professional production deployments.*
