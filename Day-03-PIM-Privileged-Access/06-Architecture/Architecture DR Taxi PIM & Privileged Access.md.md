\# SC-300 Day 03 — PIM \& Privileged Access Architecture



\## Overview



This architecture demonstrates how privileged administrative access is controlled within the DR Taxi environment using Privileged Identity Management (PIM).



The design follows Zero Trust and least privilege principles to reduce exposure of privileged accounts and improve administrative governance.



\---



\# Components



\## Users

\- Administrators

\- Operations staff

\- Security administrators



\## Microsoft Entra ID

Central identity provider responsible for authentication and role management.



\## Privileged Identity Management (PIM)

Controls privileged administrative access using:

\- Eligible role assignments

\- Just-in-Time activation

\- MFA enforcement

\- Time-bound administrative access



\## Security Controls

\- Multi-Factor Authentication (MFA)

\- Justification requirement

\- Temporary privileged activation

\- Role governance



\---



\# Architecture Flow



User

↓

Microsoft Entra ID

↓

Privileged Identity Management (PIM)

↓

MFA + Justification

↓

Temporary Administrative Access

↓

Automatic Expiry



\---



\# Key Security Principles



\- Least privilege access

\- Zero Trust security model

\- Controlled administrative access

\- Reduced privileged exposure

\- Governance and accountability



\---



\# Constraints



Microsoft Entra ID P2 licensing was not available within the tenant.



The implementation was therefore documented as an architectural and governance design aligned with enterprise privileged access management best practices.



\---



\# Business Outcome



The privileged access model reduces the risk of permanent administrative exposure and strengthens identity governance within the DR Taxi environment.

