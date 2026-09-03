# Microsoft Entra ID Identity & Access Management Lab

## Project Overview

This repository documents hands-on Microsoft Entra ID labs completed in a personal cloud environment to build practical skills in identity administration, access management, authentication troubleshooting, privileged access, and user provisioning.

The scenarios focus on tasks relevant to IT Support, junior systems administration, cloud support, and Identity & Access Management (IAM), including investigating sign-in problems, managing administrative roles, delegating administrative responsibilities, and provisioning users.

> **Note:** All scenarios in this repository were completed in a personal lab environment for hands-on learning and do not represent professional production experience.

## Environment & Technologies

- Microsoft Entra ID
- Microsoft Entra admin center
- Microsoft Entra administrative roles
- Privileged Identity Management (PIM)
- Administrative Units
- Sign-in logs
- Authentication and MFA
- Bulk user provisioning
- Microsoft Excel / CSV
- Test tenant: Williamson Technology Group

## Featured Labs

### 1. Administrative Units & Delegated Administration

Created Administrative Units to organize identities by location and practiced delegating administrative responsibilities within a defined scope.

This lab reinforced the difference between placing users inside an Administrative Unit and assigning an administrative role scoped to that unit.

➡️ [View Lab 10 – Administrative Units & Delegated Administration](Lab-10-Administrative-Units/README.md)

### 2. Account Lockout Investigation

Investigated a test account that became temporarily blocked after repeated failed authentication attempts.

Used Microsoft Entra sign-in logs to identify the affected account, review error information including error code **50053**, isolate the relevant sign-in activity, and perform a password reset as a remediation step.

➡️ [View Lab 06 – Account Lockout Investigation](Lab-06-Account-Lockout/README.md)

### 3. Administrative Roles & RBAC

Reviewed Microsoft Entra administrative roles, examined the User Administrator role, assigned the role to a test user through the privileged role-assignment workflow, and verified the resulting active assignment.

This lab reinforced the distinction between role-based access concepts and Privileged Identity Management (PIM), as well as the importance of selecting targeted administrative privileges instead of unnecessarily broad access.

➡️ [View Lab 09 – Administrative Roles & RBAC](Lab-09-Entra-Roles-RBAC/README.md)

### 4. Interrupted Sign-In & MFA Investigation

Investigated an interrupted Microsoft Entra sign-in using authentication, device, and access information from the sign-in logs.

The evidence showed that the password authentication step succeeded but the MFA portion of the authentication process did not complete successfully.

This scenario reinforced the importance of reviewing multiple pieces of sign-in evidence before determining why an authentication attempt failed.

➡️ [View Lab 07 – Interrupted Sign-In & MFA Investigation](Lab-07-Interrupted-Sign-In-MFA/README.md)

### 5. Bulk User Provisioning with CSV

Prepared a structured CSV containing ten test identities and used Microsoft Entra's bulk user creation workflow to provision the accounts.

Verified the results by reviewing the user directory after the operation and confirming that the additional test identities appeared.

➡️ [View Lab 11 – Bulk User Provisioning](Lab-11-Bulk-User-Provisioning/README.md)

## Skills Demonstrated

- Microsoft Entra ID administration
- Identity and Access Management (IAM) fundamentals
- User provisioning and account administration
- Authentication troubleshooting
- Sign-in log investigation
- Multi-Factor Authentication (MFA) troubleshooting
- Administrative role management
- Role-Based Access Control (RBAC) concepts
- Privileged Identity Management (PIM) concepts
- Administrative Units
- Delegated administration
- Least-privilege principles
- Bulk user provisioning
- CSV-based identity administration
- Technical troubleshooting and documentation

## Troubleshooting Approach

Across these labs, I practiced approaching identity and access issues as a troubleshooting process rather than simply completing configuration steps.

My general workflow was:

**Identify the issue → Gather evidence → Review identity/access configuration → Determine the likely cause or required change → Take action → Verify the result → Document the process**

This approach helped me connect Microsoft Entra administration with the type of structured troubleshooting used in IT support and identity-focused roles.

## Key Takeaways

Working through these scenarios strengthened my understanding of how identity administration extends beyond simply creating users and resetting passwords.

I gained hands-on practice with:

- Investigating authentication and account-access problems
- Reviewing sign-in evidence before reaching a conclusion
- Understanding how administrative roles delegate permissions
- Distinguishing RBAC concepts from privileged role management
- Delegating administration within defined scopes
- Provisioning multiple identities efficiently
- Applying least-privilege thinking when assigning administrative access

These labs also reinforced the importance of verifying results and documenting only what the available evidence supports.
