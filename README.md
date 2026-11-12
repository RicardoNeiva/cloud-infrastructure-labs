# Cloud Infrastructure Labs

## About This Project

I am an IT professional with over 10 years of experience in enterprise IT operations, technical support, and Major Incident Management.

I am currently expanding my technical skills in Systems Administration and Microsoft Azure Cloud Infrastructure, with a focus on hands-on learning and practical experience.

This repository documents my learning journey through practical labs involving operating systems, virtualisation, networking, server configuration, and troubleshooting.

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

## Learning Roadmap

### Month 1 — Linux Fundamentals
- Ubuntu Server installation and configuration
- Linux terminal commands
- User and file management
- SSH and remote administration
- Linux services and basic troubleshooting

### Month 2 — Windows Server and Networking
- Windows Server administration
- Virtualisation
- TCP/IP networking
- DNS and DHCP fundamentals
- PowerShell basics

### Month 3 — Microsoft Azure Fundamentals
- Introduction to cloud computing
- Azure Virtual Machines
- Azure networking
- Azure storage
- Azure resource management

### Month 4 — Azure Infrastructure Administration
- Deploying Azure resources
- Virtual networks and connectivity
- Virtual machine administration
- Monitoring and troubleshooting

### Month 5 — Infrastructure Automation
- PowerShell scripting
- Bash scripting
- Azure CLI
- Introduction to Infrastructure as Code

### Month 6 — Portfolio Development
- Advanced infrastructure labs
- Microsoft Azure Administrator (AZ-104) preparation
- Technical documentation
- Cloud administration portfolio projects

## Career Objective

My professional background in enterprise IT operations and Major Incident Management has provided me with experience in incident troubleshooting, service availability, technical coordination, and operational processes.

I am building on this experience by developing practical technical skills in Linux, Windows Server, virtualisation, and Microsoft Azure.

My goal is to move into a Systems Administrator, Infrastructure Administrator, or Cloud Administrator position, focusing on hands-on technical work, infrastructure configuration, and continuous learning.

## Project Status

**Lab 01:** Ubuntu Server installation and SSH connectivity — Completed

**Current Focus:** Linux administration fundamentals

**Next Lab:** Linux service administration and web server configuration
