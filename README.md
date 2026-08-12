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
