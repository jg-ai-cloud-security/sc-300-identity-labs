\# Implementation Guide — PIM \& Privileged Access



\## Objective



Implement Privileged Identity Management (PIM) within the DR Taxi environment to reduce exposure of privileged accounts and enforce controlled administrative access.



\---



\# Environment



\## Tenant

Tech Tenant (Microsoft Entra ID)



\## Administrative User

maria.miller



\## Security Focus

\- Privileged Identity Management (PIM)

\- Just-in-Time (JIT) access

\- MFA enforcement

\- Privileged access governance



\---



\# Implementation Steps



\## Step 1 — Access Microsoft Entra ID



\- Sign in to Microsoft Entra Admin Center

\- Navigate to:

&#x20; Identity Governance → Privileged Identity Management (PIM)



\### Purpose

Access the privileged access management platform used to control administrative permissions.



\---



\## Step 2 — Select Azure AD Roles



\- Open:

&#x20; Azure AD Roles



\### Purpose

Manage privileged administrative roles within the tenant environment.



\---



\## Step 3 — Select Administrative Role



\- Select:

&#x20; User Administrator (or Global Administrator if available)



\### Purpose

Define which privileged role will be controlled through PIM.



\---



\## Step 4 — Add Role Assignment



\- Select:

&#x20; Assignments → Add assignments



\### Configuration

\- Assignment type:

&#x20; Eligible

\- Assigned user:

&#x20; maria.miller



\### Purpose

Configure privileged access as eligible rather than permanently active.



\---



\## Step 5 — Configure Activation Settings



Configure the following settings:

\- Require MFA for activation

\- Require justification

\- Configure activation duration (example: 1 hour)



\### Purpose

Ensure privileged access is temporary, monitored, and protected through additional verification.



\---



\## Step 6 — Validate Role Activation



\- Validate eligible role assignment

\- Confirm activation workflow

\- Review MFA and justification requirements



\### Purpose

Ensure privileged access behaves according to security requirements.



\---



\# Validation



\## Validation Performed



\- Eligible role assignment verified

\- MFA enforcement validated

\- Privileged activation workflow reviewed

\- Time-bound activation confirmed



\---



\# Business Outcome



This implementation reduces the exposure of privileged accounts and improves administrative governance within the DR Taxi environment.



Privileged access is now controlled through Just-in-Time activation and stronger identity security controls.



\---



\# Security Benefits



\- Reduced attack surface

\- Controlled privileged access

\- Temporary administrative permissions

\- Improved privileged access governance

\- Alignment with Zero Trust principles



\---



\# Constraints



Some advanced PIM features may require Microsoft Entra ID P2 licensing.



Where licensing limitations exist, implementation steps are documented and simulated for governance and architecture purposes.



\---



\# Evidence Captured



\- Eligible role assignment

\- PIM activation settings

\- Privileged role activation workflow



\---



\# Conclusion



PIM implementation strengthens identity governance by ensuring administrative access is controlled, temporary, and monitored.



This reduces the security risk associated with permanently active privileged accounts.

