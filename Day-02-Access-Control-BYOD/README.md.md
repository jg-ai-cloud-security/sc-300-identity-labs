\# SC-300 Day 02 — Access Control \& BYOD Security (DR Taxi)



\## Overview

This stage builds on the identity foundation established in Day 01 by implementing secure access controls for DR Taxi.



The solution focuses on protecting access to business systems across multiple booking channels, including WhatsApp, email, phone, Facebook, and calendar scheduling.



\---



\## What This Stage Covers

\- Multi-Factor Authentication (MFA)

\- Conditional Access policies

\- Legacy authentication blocking

\- Location-based access control

\- BYOD (Bring Your Own Device) security approach



\---



\## Architecture Approach

Access to DR Taxi systems is secured using Microsoft Entra ID by enforcing identity verification through MFA and Conditional Access policies.



Users must authenticate and meet defined security conditions before accessing business systems.



\---



\## Key Implementation

\- MFA enabled for all users

\- Conditional Access policies applied to role-based groups

\- Legacy authentication blocked

\- Access restricted based on security conditions



\---



\## Business Context

DR Taxi operates using multiple communication channels for bookings, with staff accessing systems from personal devices.



This introduces risks such as:

\- Unauthorised access

\- Weak authentication

\- Data exposure



\---



\## Outcome

\- Strong authentication enforced

\- Controlled access to business systems

\- Reduced risk from unmanaged devices

\- Secure foundation for future device compliance and app protection



\---



\## Final Statement

This implementation introduces a Zero Trust access model, ensuring that all access to DR Taxi systems is verified, controlled, and protected regardless of device or location.

