# Active Directory Home Lab

## Overview

This project demonstrates the deployment and administration of a Windows Server Active Directory environment in a virtualised cybersecurity home lab.

The objective was to gain practical experience with identity and access management, Windows domain administration, user and group management, Organizational Units, Group Policy, and domain-joined client systems.

## Objectives

- Deploy a Windows Server domain controller
- Configure an Active Directory domain
- Create and manage users
- Create security groups
- Organise users using Organizational Units
- Configure Group Policy
- Join a Windows client machine to the domain
- Apply security policies to domain users and computers
- Test authentication and domain access
- Document the environment and configuration

## Lab Environment

| Component | Technology |
|---|---|
| Server | Windows Server |
| Client | Windows |
| Directory Service | Active Directory Domain Services |
| Virtualization | VirtualBox |
| Network | Private virtual network |
| Domain Controller | Windows Server |
| Management | Active Directory Users and Computers |
| Policy Management | Group Policy Management |

## Lab Architecture

The lab consists of a Windows Server configured as the Active Directory Domain Controller and a Windows client joined to the domain.

```text
                 Active Directory Domain
                         |
                  Windows Server
                  Domain Controller
                         |
                  Private Network
                         |
                  Windows Client
                  Domain Joined


## Active Directory Configuration


The following tasks were completed as part of the Active Directory home lab:

### 1. Domain Controller

Configured Windows Server as an Active Directory Domain Controller and established the foundation for the Windows domain environment.

### 2. Domain Configuration

Created and configured the Active Directory domain and verified domain services were operating correctly.

### 3. User Management

Created domain user accounts and configured user properties and access within the Active Directory environment.

### 4. Group Management

Created security groups and assigned users according to their roles to demonstrate centralized access management.

### 5. Organizational Units

Created Organizational Units (OUs) to logically organise users and computers within the domain.

### 6. Group Policy

Configured Group Policy settings to demonstrate centralized security, configuration management, and administrative controls across domain-joined systems.

### 7. Domain Join

Configured a Windows client and successfully joined it to the Active Directory domain.

### 8. Authentication Testing

Tested domain authentication using domain credentials and verified that users could authenticate against the Active Directory environment.

---

## Security Concepts Demonstrated

This project demonstrates practical knowledge of:

- Identity and Access Management (IAM)
- Active Directory
- Authentication
- Authorization
- Role-Based Access Control (RBAC)
- Security Groups
- Group Policy
- Windows Server Administration
- Domain Controllers
- Organizational Units (OUs)
- Endpoint Administration
- Network Configuration
- Basic Windows Security

---

## Skills Demonstrated

- Windows Server
- Active Directory
- Group Policy
- User and Group Administration
- Identity and Access Management
- Windows Networking
- VirtualBox
- Troubleshooting
- Cybersecurity Administration

---

## Project Evidence

Screenshots documenting the Active Directory configuration, security policies, domain joining, user management, and authentication testing are available in the `Documentation` directory.

The screenshots provide evidence of the practical implementation and testing performed within the isolated lab environment.

---

## Project Outcome

Successfully built and configured a functional Active Directory environment in a virtualised home lab.

The project provided hands-on experience with identity and access management, Windows domain administration, centralised security policies, user and group management, endpoint administration, and domain authentication.

## Disclaimer

This project was completed in an isolated virtualised home lab for educational and portfolio purposes. No production or organisational systems were used.
