\# SC-300 Day 01 — Identity Foundation (GitHub Summary)



\## Objective

To design and implement a structured identity architecture for DR Taxi to secure access across multiple booking channels.



\---



\## What Was Delivered

\- Business-aligned user identities created

\- Role-Based Access Control (RBAC) implemented

\- Security groups defined for Drivers, Admins, Operations, and Finance

\- Users assigned to groups based on business roles



\---



\## Business Context

DR Taxi currently operates without a central booking system and relies on:

\- WhatsApp

\- Email (booking@drtaxi.co.uk)

\- Phone

\- Facebook

\- Calendar scheduling



This increases the need for controlled identity access.



\---



\## Outcome

\- Eliminated reliance on shared identities

\- Established structured access control

\- Improved visibility over user access

\- Created a scalable foundation for Conditional Access and BYOD security



\---



\## Architecture Insight

Identity acts as the control layer between users and business systems, ensuring all access is governed through RBAC rather than direct assignment.

