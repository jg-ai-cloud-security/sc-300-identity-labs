\# Architecture — DR Taxi Identity Model



\## Overview

This architecture secures access to DR Taxi booking channels through identity control.



\## Components

\- Users (Drivers, Admins, Operations, Finance)

\- Microsoft Entra ID (Identity Layer)

\- RBAC Groups

\- Booking Channels (WhatsApp, Email, Phone, Facebook)



\## Design Approach

Identity is used as the control layer between users and business systems.



\## Key Insight

All access is governed through RBAC groups, not direct assignment.



\## Outcome

A scalable and secure identity architecture ready for Conditional Access and BYOD security.

