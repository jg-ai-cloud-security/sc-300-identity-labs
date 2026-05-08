\# SC-300 Day 05 — Identity Governance \& Access Reviews Architecture



\## Overview



This architecture demonstrates how identity governance and access review processes improve visibility into user permissions and administrative access assignments within the DR Taxi environment.



The implementation strengthens least privilege access management and supports Zero Trust identity governance principles.



\---



\# Components



\## Users

\- Drivers

\- Operations staff

\- Administrative users



\## Microsoft Entra ID

Central identity platform used for RBAC governance, access visibility, and administrative role management.



\## Security Groups

Role-based security groups used to manage user access assignments.



Examples:

\- DRTaxi-Drivers

\- DRTaxi-Admins

\- DRTaxi-Operations

\- DRTaxi-Finance



\## RBAC Assignments

Administrative and role-based permissions assigned using Microsoft Entra ID governance controls.



\## Access Reviews

Governance processes used to review:

\- User permissions

\- Group memberships

\- Administrative assignments

\- Least privilege validation



\## Governance Monitoring

Visibility into user access and privileged assignments used to strengthen identity governance processes.



\---



\# Architecture Flow



Users

↓

Security Groups

↓

Microsoft Entra ID

↓

RBAC Assignments

↓

Access Reviews

↓

Governance Monitoring

↓

Least Privilege Access



\---



\# Key Security Principles



\- Identity governance

\- Least privilege access

\- RBAC governance

\- Access visibility

\- Zero Trust identity security



\---



\# Constraints



Some advanced Microsoft Entra Governance and Access Review capabilities may require additional licensing depending on business requirements.



The implementation was completed using Microsoft 365 Business Premium governance and identity security capabilities.



\---



\# Business Outcome



The governance implementation improves visibility into user permissions and strengthens administrative access management within the DR Taxi environment.

