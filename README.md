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
Example Users
User	Username	Department	Title
Jordan Kim	jkim	Product Support	Product Support Specialist
Riley Moore	rmoore	Product Support	Application Support Analyst
Ari Bennett	abennett	IT	IT Support Technician
Chris Davis	cdavis	IT	Desktop Support Technician
Sam Brooks	sbrooks	Finance	Finance Analyst
Taylor Reed	treed	Product Support	Product Support Specialist
Marcus Lee	mlee	Client Success	Client Success Associate
Dana Wright	dwright	Implementation	Implementation Specialist
Example Security Groups
Group	Purpose
GG-Product-Support	Product Support team access
GG-Remote-Users	Remote access workflow group
GG-Zendesk-Users	Standard support platform access
GG-Zendesk-Admins	Elevated support platform access
GG-SQL-ReadOnly	Read-only troubleshooting access
GG-Helpdesk-Password-Reset	Help desk delegation model
Skills Practiced
Windows Server setup
Active Directory Domain Services
Domain controller configuration
Organizational Unit design
User account management
Security group management
Group membership verification
Bulk onboarding with PowerShell
Access audit exports
Privileged access review
Help desk delegation modeling
Password/account policy review
Support documentation
Support/Admin Workflows Practiced
Created simulated users by department
Assigned users to access groups based on job function
Verified Product Support group membership
Created bulk onboarding users from CSV-style input
Exported user access audit data
Exported group membership audit data
Reviewed privileged support access groups
Created a help desk password-reset delegation group
Reviewed domain password policy
Evidence

Screenshots are stored in the screenshots folder.

CSV exports are stored in the evidence folder.

Example evidence files:

user_access_audit.csv
group_membership_audit.csv
privileged_support_access_review.csv
bulk_onboarding_users.csv
helpdesk_delegation_group.csv
