# Active Directory Support Lab
# Active Directory Support Lab

## Overview
Built a Windows Server Active Directory lab using VirtualBox on an Intel Mac to practice IT support, help desk, product support, and identity/access management workflows.

This project simulates a small company environment with departments, users, security groups, group memberships, access audits, and support-style documentation.

## Environment
- Host: 2020 Intel Mac
- Virtualization: Oracle VirtualBox
- Guest OS: Windows Server 2025 Standard Evaluation
- Server Name: DC01
- Domain: taddley.local
- Directory Service: Active Directory Domain Services

## What I Built
- Installed Windows Server in a virtual machine
- Renamed the server to DC01
- Installed Active Directory Domain Services
- Promoted the server to a domain controller
- Created the domain `taddley.local`
- Created a simulated company structure using Organizational Units
- Created users across multiple departments
- Created security groups for access management
- Assigned users to department and application-style access groups
- Created CSV exports for user and group access review
- Practiced bulk onboarding with PowerShell
- Reviewed password/account policy settings

## Simulated Company Structure

```text
LabCorp
├── Users
│   ├── IT
│   ├── Product Support
│   ├── Client Success
│   ├── Finance
│   └── Implementation
├── Groups
├── Computers
├── Disabled Users
└── Service Accounts
