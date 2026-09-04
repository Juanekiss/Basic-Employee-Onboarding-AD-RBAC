# Basic-Employee-Onboarding-AD-RBAC

## Problem Statement

Northstar Medical Group, a healthcare company with 200+ employees, previously relied on a managed service provider (MSP) that left their identity infrastructure disorganized. User accounts were provisioned manually with no consistent naming convention, no organizational unit (OU) structure, and inconsistent security group memberships. This created HIPAA compliance exposure and made access control difficult to audit or manage at scale.

## Solution Overview

Built the NMG.com domain from scratch on Windows Server, designed a department-based OU structure covering four business units (Finance, HR, IT, Operations), and implemented Role-Based Access Control (RBAC) using security groups mapped to each department. Provisioned 15 user accounts with standardized naming conventions and attribute consistency. Diagnosed and resolved a real-world multi-cause access incident involving incorrect OU placement and missing security group membership.

## Video Walkthrough

[Video walkthrough](https://www.loom.com/share/757aa2d440bb41668a4f2e9f1876f172)

## Tools Used
- Windows Server
- Active Directory Domain Services
- Group Policy
- VirtualBox
- RBAC
- GitHub

## Project Timeline
- *Day 1:* Domain creation and domain controller promotion
- *Day 2:* Organizational unit and security group design
- *Day 3:* User provisioning and RBAC implementation
- *Day 4:* Incident response and resolution (NMG-0047)
- *Day 5:* Documentation and case study packaging

## Key Accomplishments
- Built the NMG.com domain from scratch, including domain controller promotion (NMG-DC01) with a static IP configuration
- Designed a department-based OU structure covering four business units (Finance, HR, IT, Operations)
- Implemented RBAC with security groups mapped to each department
- Provisioned 15 user accounts with consistent naming conventions and attribute standards
- Diagnosed and resolved a multi-cause access issue (incorrect OU placement + missing security group membership)
- Documented the full incident resolution with root cause analysis

## Repository Structure
- /Documentation — Domain configuration notes, security group documentation, user list documentation, and RBAC structure mapping
- /Screenshots — Visual proof of each build stage: domain creation, OU structure, security groups, user provisioning, and incident resolution
- /Incident-Reports — Full resolution report for ticket NMG-0047
- RBAC-Structure.md — Table mapping each department to its OU, security group, assigned users, and access permissions
