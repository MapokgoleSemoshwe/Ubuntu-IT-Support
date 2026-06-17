# Ubuntu-IT-Support-Capstone
# Table of Contents

- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Company Information](#company-information)
- [Organizational Structure](#organizational-structure)
- [Business Requirements Analysis](#business-requirements-analysis)
- [Hardware Inventory](#hardware-inventory)
- [Software Inventory](#software-inventory)
- [Network Design](#network-design)
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
- [Project Outcomes](#project-outcomes)
- [Repository Structure](#repository-structure)
- [Author](#author)

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

This project also serves as evidence of technical competency in IT Support, Network Administration, Cybersecurity, and Business Technology Management.

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

Each department has unique technology requirements and access permissions that must be considered when designing the IT infrastructure.

---

# Business Requirements Analysis

## Business Needs

Ubuntu Innovations requires a modern technology environment capable of supporting daily business operations while maintaining security, efficiency, and reliability.

The organization requires:

- Secure internet connectivity
- Wired and wireless networking
- Shared storage and file access
- Shared printing services
- Department-based access controls
- Antivirus and endpoint protection
- Backup and disaster recovery capabilities
- Cybersecurity policies
- Professional IT documentation

## Security Requirements

The company handles confidential employee records, financial information, business documents, and software development projects.

To protect these assets, the organization requires:

- Multi-Factor Authentication (MFA)
- Encryption of sensitive data
- Antivirus protection
- Firewall security
- User access controls
- Security awareness training
- Incident response procedures

## Operational Challenges

Potential operational challenges include:

### Rapid Business Growth

As the company expands, additional users, devices, and services will increase demand on IT resources.

### Cybersecurity Threats

Modern organizations face threats such as phishing attacks, ransomware, malware infections, and unauthorized access attempts.

### Data Loss Risks

Hardware failures, accidental deletions, and cyberattacks may result in loss of critical business information.

### Network Downtime

Internet outages and equipment failures can impact employee productivity and customer service.

The proposed infrastructure is designed to address these challenges while supporting future growth.

---

# Hardware Inventory

The following hardware is recommended to support business operations.

| Asset | Quantity | Specification | Business Justification |
|---------|---------|---------|---------|
| Desktop PCs | 20 | Intel Core i5, 16GB RAM, 512GB SSD | Supports office productivity and daily business operations |
| Laptops | 5 | Intel Core i7, 16GB RAM, SSD | Provides mobility for Executive Management |
| Router/Firewall | 1 | Business-grade firewall router | Secures network traffic and internet access |
| Managed Switch | 1 | 24-Port Gigabit Managed Switch | Supports centralized network connectivity and future VLAN implementation |
| Wireless Access Points | 2 | Wi-Fi 6 Access Points | Provides secure wireless coverage throughout the office |
| Network Printers | 2 | Laser Printers | Enables shared printing services |
| NAS Storage | 1 | RAID-enabled NAS Device | Centralized file storage and backup management |
| UPS Systems | 2 | 1500VA UPS | Protects critical equipment from power outages |

## Hardware Justification

### Desktop Computers

Twenty desktop computers are recommended for employees who primarily perform office-based tasks. The Intel Core i5 processor, 16GB RAM, and SSD storage provide sufficient performance for productivity applications, collaboration tools, and business operations.

### Laptops

Five laptops are allocated to Executive Management to provide flexibility and support remote work, travel, and meetings outside the office.

### Managed Switch

A 24-Port Managed Gigabit Switch was selected to provide centralized connectivity, network monitoring, traffic management, and future scalability through VLAN implementation.

### NAS Storage

The NAS device serves as centralized storage for company files and backups, ensuring data availability and supporting disaster recovery operations.

---

# Software Inventory

The organization requires both company-wide and department-specific software solutions.

## Company-Wide Software

| Software | Purpose | License Type |
|----------|----------|----------|
| Windows 11 Pro | Operating System | Per Device |
| Microsoft 365 | Productivity Suite | Subscription |
| Microsoft Teams | Communication and Collaboration | Subscription |
| Zoom | Video Conferencing | Subscription |
| Microsoft Defender | Antivirus Protection | Included |
| Google Chrome | Web Browsing | Free |

### Microsoft 365

Microsoft 365 provides Word, Excel, PowerPoint, Outlook, Teams, and OneDrive. These applications support communication, collaboration, document management, and cloud storage.

### Microsoft Teams

Microsoft Teams enables messaging, video conferencing, collaboration, and file sharing across departments.

---

## Department-Specific Software

### Finance Department

- Sage Accounting
- Microsoft Excel

Purpose:
- Payroll processing
- Financial reporting
- Budget management
- Expense tracking

### Human Resources

- HR Management System

Purpose:
- Employee records
- Leave management
- Recruitment tracking
- Performance management

### Sales & Marketing

- CRM Software

Purpose:
- Customer relationship management
- Sales tracking
- Lead management

### Software Development

- Visual Studio Code
- GitHub
- Docker

Purpose:
- Software development
- Version control
- Collaboration
- Application deployment

---

# Network Design

The network architecture was designed to provide secure and reliable communication between all devices within the organization.

Network connectivity begins with the Internet Service Provider (ISP) connection.

Traffic passes through a firewall-enabled router that protects the organization from external threats while managing internet access.

A 24-Port Managed Gigabit Switch connects:

- Desktop computers
- Laptops
- Network printers
- NAS storage
- Wireless access points

Wireless Access Points provide secure Wi-Fi access to employees while supporting future guest network implementation.

The NAS device provides centralized file storage and backup services.

## Network Topology


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


### Network Design Benefits

- Improved security
- Centralized management
- Scalability for future growth
- Efficient resource sharing
- Simplified troubleshooting

---

# IP Addressing Plan

Network segmentation has been implemented to improve security, traffic management, and troubleshooting efficiency.

| Network | Subnet | Purpose |
|----------|----------|----------|
| Servers & NAS | 192.168.10.0/24 | Storage and backup systems |
| User Devices | 192.168.20.0/24 | Employee workstations and laptops |
| Printers | 192.168.30.0/24 | Shared printing devices |
| Wireless Network | 192.168.40.0/24 | Wi-Fi connected devices |

## Benefits of Network Segmentation

- Improved security
- Easier troubleshooting
- Reduced network congestion
- Better traffic management
- Simplified administration

---

# User Permissions Matrix

Role-Based Access Control (RBAC) is implemented to ensure employees only access information required for their job responsibilities.

| Department | Security Group | Access Level |
|------------|------------|------------|
| Executive Management | mgmt_grp | Full Access |
| Finance | finance_grp | Finance Folder |
| Human Resources | hr_grp | HR Folder |
| Sales & Marketing | sales_grp | Sales Folder |
| Software Development | dev_grp | Development Folder |

### Access Control Benefits

- Protects sensitive information
- Reduces insider threats
- Supports compliance requirements
- Simplifies user management

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

Each department has access only to authorized folders while all employees may access the Public folder.

This structure improves organization, security, and collaboration.

---

# Software Deployment Plan

Software deployment will be managed centrally to ensure consistency across all company devices.

The deployment process includes:

- Operating system installation
- Productivity software installation
- Antivirus deployment
- Department-specific applications
- Security updates

## Update Strategy

- Critical security patches: Within 48 hours
- Monthly maintenance updates
- Automatic antivirus signature updates

This approach ensures systems remain secure and up to date.

---

# Linux Administration Guide

The following Linux commands are commonly used by system administrators:

| Command | Purpose |
|----------|----------|
| pwd | Display current directory |
| ls | List files and folders |
| cd | Change directory |
| mkdir | Create directories |
| touch | Create files |
| chmod | Modify permissions |
| chown | Change ownership |
| ps | View running processes |
| top | Monitor system performance |
| apt install | Install software packages |

These commands assist with file management, software installation, user administration, and system monitoring.

---

# Backup and Disaster Recovery Plan

Data protection is critical to business continuity.

## Backup Strategy

### Daily Incremental Backups

Only changed files are backed up each day, reducing storage requirements and backup times.

### Weekly Full Backups

A complete copy of organizational data is created every week.

### Monthly Archive Backups

Long-term backups are retained for historical and compliance purposes.

### Offsite Cloud Backup

Backup copies are stored in cloud storage to protect against physical disasters affecting the office.

## Recovery Objectives

### Recovery Time Objective (RTO)

4 Hours

The maximum acceptable downtime before systems are restored.

### Recovery Point Objective (RPO)

24 Hours

The maximum acceptable amount of data loss.

## Recovery Procedure

1. Identify the incident.
2. Verify available backups.
3. Restore affected systems.
4. Validate data integrity.
5. Resume business operations.
6. Document recovery actions.

---

# Cybersecurity Policy

Cybersecurity controls are implemented to protect systems, users, and business information.

## Password Policy

- Minimum 12 characters
- Uppercase letters
- Lowercase letters
- Numbers
- Special characters
- Password changes every 90 days

## Multi-Factor Authentication

MFA is required for:

- Email accounts
- Administrative accounts
- Remote access systems

## Encryption

Sensitive information is encrypted:

- During storage
- During transmission
- On company laptops

## Antivirus Protection

Microsoft Defender provides:

- Real-time threat detection
- Malware protection
- Ransomware protection
- Automatic updates

## Patch Management

- Critical patches within 48 hours
- Monthly system updates
- Regular vulnerability remediation

---

# Risk Assessment Matrix

| Risk | Likelihood | Impact | Mitigation |
|---------|---------|---------|---------|
| Phishing Attack | High | High | Security Awareness Training |
| Ransomware | Medium | High | Backups and Antivirus |
| Hardware Failure | Medium | Medium | Redundant Equipment |
| Power Outage | Medium | High | UPS Systems |
| Data Breach | Medium | High | MFA and Encryption |
| Internet Outage | Medium | Medium | ISP Redundancy |

Risk management reduces business disruption and improves operational resilience.

---

# Incident Response Plan

The organization follows a structured incident response process.

## Stages

### 1. Detection

Identify unusual or suspicious activity.

### 2. Reporting

Report incidents to IT support immediately.

### 3. Containment

Prevent further damage.

### 4. Eradication

Remove the threat.

### 5. Recovery

Restore systems and services.

### 6. Lessons Learned

Review the incident and improve security controls.

---

# Troubleshooting Documentation

Standardized troubleshooting procedures help IT staff quickly resolve common technical issues.

## Documented Scenarios

### Desktop Not Powering On

Includes:
- Symptoms
- Causes
- Diagnostic procedures
- Resolution

### No Internet Connectivity

Includes:
- Symptoms
- Causes
- Troubleshooting steps
- Resolution

### Printer Offline

Includes:
- Symptoms
- Causes
- Troubleshooting steps
- Resolution

These procedures reduce downtime and improve support efficiency.

---

# Career Readiness

This project also includes professional career development materials:

- Professional Resume (CV)
- Cover Letter
- LinkedIn Summary
- LinkedIn Project Post
- Interview Preparation Questions and Answers

These materials demonstrate readiness for entry-level IT Support roles.

---

# Project Outcomes

This project successfully demonstrates the ability to:

- Analyze business requirements
- Design network infrastructure
- Recommend hardware and software solutions
- Implement access control strategies
- Develop cybersecurity policies
- Create backup and disaster recovery plans
- Assess organizational risks
- Develop incident response procedures
- Troubleshoot common IT issues
- Create professional technical documentation

The final solution provides Ubuntu Innovations with a secure, scalable, and reliable IT environment capable of supporting both current operations and future business growth.

---

# Repository Structure


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


---

# Author

**Ntando Badla**,**Semoshwe Mapokgole** & **Sibahle Lottering**



