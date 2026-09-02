# Microsoft Entra ID Identity & Access Management Lab

## Project Overview

This project documents my hands-on practice with Microsoft Entra ID in a personal cloud lab environment. The scenarios focus on identity administration, delegated administration, role-based access control, authentication troubleshooting, and user provisioning.

The labs demonstrate both the administrative and support sides of identity management—from assigning appropriate administrative access to investigating authentication problems and managing user identities.

> **Note:** This is a personal hands-on lab created for learning and skill development. It does not represent professional production experience.

---

## Technologies & Tools

- Microsoft Entra ID
- Microsoft Entra admin center
- Microsoft Azure portal
- Entra roles and role assignments
- Privileged Identity Management (PIM)
- Administrative Units
- Sign-in logs
- Authentication methods
- CSV bulk user provisioning

---

## Skills Practiced

- User and group administration
- Microsoft Entra role assignment
- Role-Based Access Control (RBAC) concepts
- Privileged role eligibility and activation concepts
- Delegated administration using Administrative Units
- Authentication and sign-in troubleshooting
- Account lockout investigation
- MFA-related sign-in investigation
- Bulk user provisioning
- Identity and access troubleshooting
- Reviewing sign-in logs and authentication details

---

## Featured Scenarios

### 1. Administrative Units & Delegated Administration

Configured Administrative Units to organize users by location and practiced delegating administrative responsibilities within a limited scope.

**Key skills:** Administrative Units, scoped administration, User Administrator role, delegated access

### 2. Account Lockout Investigation

Investigated a user account lockout using Microsoft Entra sign-in information, identified repeated authentication failures, and performed account recovery steps.

**Key skills:** Sign-in troubleshooting, account lockout investigation, authentication logs, user support

### 3. Interrupted Sign-In & MFA Investigation

Analyzed an interrupted Microsoft Entra sign-in and reviewed authentication details to understand why access was not completed.

**Key skills:** Sign-in logs, MFA troubleshooting, authentication analysis, device and sign-in context

### 4. Microsoft Entra Roles & Privileged Access

Practiced assigning a Microsoft Entra administrative role and explored the difference between eligible and active privileged access.

**Key skills:** Entra roles, RBAC concepts, Privileged Identity Management, least privilege

### 5. Bulk User Provisioning

Used CSV-based bulk user creation to practice provisioning multiple Microsoft Entra user accounts efficiently.

**Key skills:** User provisioning, CSV import, identity administration

---

## Key Concepts Reinforced

This project helped reinforce several important identity and access concepts:

- **Group membership does not automatically grant resource access.** A group must be connected to an appropriate role, permission, or resource assignment.
- **RBAC and PIM serve different purposes.** RBAC determines what permissions a role provides, while PIM can control how privileged access is made eligible or active.
- **Authentication method registration is different from MFA enforcement.**
- **Sign-in failures require context.** A failed or interrupted authentication attempt does not automatically mean malicious activity.
- **Administrative Units define administrative scope, while scoped role assignments determine what an administrator can do within that scope.**

---

## Repository Structure

This repository contains selected Microsoft Entra ID lab scenarios that demonstrate identity administration, access management, and authentication troubleshooting. Each scenario includes focused documentation and supporting screenshots.

---

## What I Learned

Working through these scenarios strengthened my understanding of how cloud identity administration connects to everyday IT support and security. I gained hands-on practice managing identities, investigating authentication issues, working with administrative roles, delegating access, and documenting the results of identity-related tasks.

The labs also reinforced the importance of verifying what a configuration actually does rather than assuming that a group name, role assignment, authentication event, or security setting provides a specific level of access.
