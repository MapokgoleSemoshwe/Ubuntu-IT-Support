# Ubuntu-IT-Support-Capstone

![Status](https://img.shields.io/badge/Status-Completed-success)
![Project](https://img.shields.io/badge/Project-IT%20Support-blue)
![Security](https://img.shields.io/badge/Cybersecurity-Included-red)
![Documentation](https://img.shields.io/badge/Documentation-Complete-green)

## Project Overview

This repository contains the complete IT Support Capstone Project for Ubuntu Innovations (Pty) Ltd. The project demonstrates the planning, design, implementation, security, support, and documentation of a modern IT infrastructure solution for a growing technology company relocating to a new office in Cape Town, South Africa.

The purpose of this project is to apply IT Support best practices to create a secure, scalable, reliable, and cost-effective technology environment that supports daily business operations, protects company information, and ensures business continuity.

The project covers infrastructure planning, hardware and software recommendations, networking, system administration, cybersecurity, backup and disaster recovery, troubleshooting, and professional career readiness activities.

---

# Skills Demonstrated

- IT Support
- Network Design
- System Administration
- Cybersecurity
- Backup and Disaster Recovery
- Risk Management
- Incident Response
- Troubleshooting
- Linux Administration
- Technical Documentation
- Business Requirements Analysis

---

# Table of Contents

- [Project Overview](#project-overview)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Objectives](#project-objectives)
- [Company Information](#company-information)
- [Organizational Structure](#organizational-structure)
- [Business Requirements Analysis](#business-requirements-analysis)
- [Hardware Inventory](#hardware-inventory)
- [Software Inventory](#software-inventory)
- [Network Design](#network-design)
- [Project Screenshots](#project-screenshots)
- [IP Addressing Plan](#ip-addressing-plan)
- [User Permissions Matrix](#user-permissions-matrix)
- [Shared Folder Structure](#shared-folder-structure)
- [Software Deployment Plan](#software-deployment-plan)
- [Linux Administration Guide](#linux-administration-guide)
- [Backup and Disaster Recovery Plan](#backup-and-disaster-recovery-plan)
- [Cybersecurity Policy](#cybersecurity-policy)
- [Risk Assessment Matrix](#risk-assessment-matrix)
- [Incident Response Plan](#incident-response-plan)
- [Troubleshooting Documentation](#troubleshooting-documentation)
- [Career Readiness](#career-readiness)
- [Technologies and Concepts Used](#technologies-and-concepts-used)
- [Future Improvements](#future-improvements)
- [Project Outcomes](#project-outcomes)
- [Repository Structure](#repository-structure)
- [Author](#author)

---

# Project Objectives

The primary objective of this project is to design and document a complete IT infrastructure solution capable of supporting 25 employees across multiple departments.

The proposed solution aims to:

- Provide secure and reliable internet connectivity.
- Support communication and collaboration between employees.
- Protect sensitive business and employee information.
- Implement role-based access controls.
- Improve cybersecurity and reduce security risks.
- Establish backup and disaster recovery procedures.
- Create professional IT support documentation.
- Demonstrate practical networking, troubleshooting, and system administration skills.

---

# Company Information

## Organization Name

Ubuntu Innovations (Pty) Ltd

## Location

Cape Town, South Africa

## Industry

Technology and Software Development

## Total Employees

25 Employees

Ubuntu Innovations is a growing technology startup that requires a secure and scalable IT infrastructure to support software development, business operations, communication, collaboration, and data protection.

---

# Organizational Structure

| Department | Number of Employees |
|------------|--------------------|
| Executive Management | 3 |
| Finance | 4 |
| Human Resources | 3 |
| Sales & Marketing | 7 |
| Software Development | 8 |
| **Total** | **25** |

---

# Business Requirements Analysis

## Business Needs

The organization requires:

- Secure internet connectivity
- Wired and wireless networking
- Shared storage
- Shared printing services
- Department-based access controls
- Antivirus and endpoint protection
- Backup and disaster recovery capabilities
- Cybersecurity policies
- Technical documentation

## Security Requirements

To protect organizational assets, the company requires:

- Multi-Factor Authentication (MFA)
- Encryption
- Antivirus protection
- Firewall security
- User access controls
- Security awareness training
- Incident response procedures

## Operational Challenges

- Rapid business growth
- Cybersecurity threats
- Data loss risks
- Network downtime
- Access management complexity

---

# Hardware Inventory

| Asset | Quantity | Specification | Business Justification |
|---------|---------|---------|---------|
| Desktop PCs | 20 | Intel Core i5, 16GB RAM, 512GB SSD | Office productivity |
| Laptops | 5 | Intel Core i7, 16GB RAM | Management mobility |
| Router/Firewall | 1 | Business-grade firewall router | Internet security |
| Managed Switch | 1 | 24-Port Gigabit Managed Switch | Centralized connectivity |
| Wireless Access Points | 2 | Wi-Fi 6 | Wireless coverage |
| Network Printers | 2 | Laser Printers | Shared printing |
| NAS Storage | 1 | RAID-enabled NAS | Backup and storage |
| UPS Systems | 2 | 1500VA | Power protection |

---

# Software Inventory

## Company-Wide Software

| Software | Purpose |
|----------|----------|
| Windows 11 Pro | Operating System |
| Microsoft 365 | Productivity |
| Microsoft Teams | Collaboration |
| Zoom | Video Conferencing |
| Microsoft Defender | Security |
| Google Chrome | Web Access |

## Department-Specific Software

### Finance

- Sage Accounting
- Microsoft Excel

### Human Resources

- HR Management System

### Sales & Marketing

- CRM Software

### Software Development

- Visual Studio Code
- GitHub
- Docker

---

# Network Design

The network architecture was designed to provide secure, reliable, and scalable connectivity across the organization.

Traffic enters through a business-grade firewall router and is distributed through a managed switch to all network devices.

The architecture supports secure communication, centralized management, and future expansion.

---

# Project Screenshots

## Network Diagram

![Network Diagram](Network-Diagrams/network-diagram.png)

### Network Topology

```text
Internet (ISP)
      │
Router / Firewall
      │
24-Port Managed Switch
      │
 ├── Desktop PCs
 ├── Laptops
 ├── Network Printers
 ├── NAS Storage
 └── Wireless Access Points
```

---

# IP Addressing Plan

| Network | Subnet | Purpose |
|----------|----------|----------|
| Servers & NAS | 192.168.10.0/24 | Backup and storage |
| User Devices | 192.168.20.0/24 | Employee workstations |
| Printers | 192.168.30.0/24 | Shared printing |
| Wireless Network | 192.168.40.0/24 | Wi-Fi devices |

### Benefits

- Improved security
- Easier troubleshooting
- Better traffic management
- Reduced congestion

---

# User Permissions Matrix

| Department | Security Group | Access Level |
|------------|------------|------------|
| Executive Management | mgmt_grp | Full Access |
| Finance | finance_grp | Finance Folder |
| Human Resources | hr_grp | HR Folder |
| Sales & Marketing | sales_grp | Sales Folder |
| Software Development | dev_grp | Development Folder |

---

# Shared Folder Structure

```text
/Company
├── Public
├── Finance
├── HR
├── Sales
├── Development
└── Management
```

---

# Software Deployment Plan

Deployment includes:

- Operating systems
- Security software
- Productivity software
- Department-specific applications

Updates are performed monthly while critical security patches are deployed within 48 hours.

---

# Linux Administration Guide

| Command | Purpose |
|----------|----------|
| pwd | Current directory |
| ls | List files |
| cd | Change directory |
| mkdir | Create folder |
| touch | Create file |
| chmod | Modify permissions |
| chown | Change ownership |
| ps | View processes |
| top | Monitor resources |
| apt install | Install software |

---

# Backup and Disaster Recovery Plan

## Backup Schedule

| Backup Type | Frequency |
|------------|------------|
| Incremental Backup | Daily |
| Full Backup | Weekly |
| Archive Backup | Monthly |
| Cloud Backup | Offsite |

## Recovery Objectives

**RTO:** 4 Hours

**RPO:** 24 Hours

---

# Cybersecurity Policy

Security controls include:

- Multi-Factor Authentication
- Password Policy
- Device Encryption
- Microsoft Defender Antivirus
- Firewall Protection
- Patch Management
- Security Awareness Training

---

# Risk Assessment Matrix

| Risk | Likelihood | Impact | Mitigation |
|---------|---------|---------|---------|
| Phishing | High | High | Awareness Training |
| Ransomware | Medium | High | Backups |
| Hardware Failure | Medium | Medium | Redundancy |
| Power Outage | Medium | High | UPS Systems |
| Data Breach | Medium | High | MFA & Encryption |

---

# Incident Response Plan

1. Detection
2. Reporting
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

---

# Troubleshooting Documentation

Documented scenarios include:

- Desktop Not Powering On
- No Internet Connectivity
- Printer Offline

Each guide contains:

- Problem Description
- Symptoms
- Root Causes
- Troubleshooting Procedures
- Resolution

---

# Career Readiness

Included in this project:

- Professional CV
- Cover Letter
- LinkedIn Post
- Interview Preparation

---

# Technologies and Concepts Used

## Operating Systems

- Windows 11 Pro
- Ubuntu Linux

## Networking

- TCP/IP
- DHCP
- DNS
- Network Segmentation
- VLAN Concepts

## Security

- MFA
- Encryption
- Microsoft Defender
- Firewall Management

## Productivity

- Microsoft 365
- Microsoft Teams

## Development Tools

- GitHub
- Visual Studio Code
- Docker

---

# Future Improvements

Future enhancements include:

- Active Directory
- VLAN Implementation
- Network Monitoring
- SIEM Integration
- Cloud Expansion
- Security Audits
- Disaster Recovery Testing

---

# Project Outcomes

This project demonstrates the ability to:

- Analyze business requirements
- Design secure network infrastructure
- Implement cybersecurity controls
- Develop backup and disaster recovery plans
- Assess risks
- Create troubleshooting procedures
- Produce professional technical documentation

The final solution provides Ubuntu Innovations with a secure, scalable, and reliable IT environment capable of supporting both current operations and future growth.

---

# Repository Structure

```text
Ubuntu-IT-Support-Capstone/
│
├── Documentation/
├── Hardware-Inventory/
├── Software-Inventory/
├── Network-Diagrams/
├── Security/
├── Backup-Recovery/
├── Troubleshooting/
├── Presentation/
├── Career-Readiness/
└── Final-Report/
```

---

# Author

**Ntando Badla**,**Semoshwe Mapokgole** & **Sibahle Lottering**
