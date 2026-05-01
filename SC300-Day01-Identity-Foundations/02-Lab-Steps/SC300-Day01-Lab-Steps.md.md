\# SC300 Day 01 — Identity Foundation (Entra ID + RBAC)



\## Overview

This lab implements identity foundation using Microsoft Entra ID.  

Users, groups, and RBAC roles are configured to establish secure, centralised access aligned with least privilege principles.



\---



\## Objectives



\- Create users in Microsoft Entra ID  

\- Create security groups  

\- Assign users to groups  

\- Assign RBAC roles  

\- Validate access configuration  

\- Capture evidence  



\---



\## Step 1 — Access Microsoft Entra ID



1\. Go to Azure Portal  

2\. Navigate to:

&#x20;  → Microsoft Entra ID  



\---



\## Step 2 — Create Users



1\. Go to:

&#x20;  → Users → New user  



2\. Create:



\- sc300.user1@azurelab.fun  

\- sc300.user2@azurelab.fun 



3\. Set password and create  



\---



\## Step 3 — Create Groups



1\. Go to:

&#x20;  → Groups → New group  



2\. Create:



\- Name: SG-IT-Users  

\- Type: Security  



\---



\## Step 4 — Add Users to Group



1\. Open:

&#x20;  → SG-IT-Users  



2\. Click:

&#x20;  → Members → Add members  



3\. Add:

&#x20;  - sc300.user1  

&#x20;  - sc300.user2  



\---



\## Step 5 — Assign RBAC Roles



1\. Go to:

&#x20;  → Microsoft Entra ID → Roles and administrators  



2\. Assign role:



\- Role: User Administrator  

\- Assign to: SG-IT-Users  



\---



\## Step 6 — Validate Configuration



Check:



\- Users exist  

\- Group membership is correct  

\- Role assignment is applied  



\---



\## Step 7 — Capture Evidence



Take screenshots:



\- Users created  

\- Group created  

\- Group members  

\- Role assignment  



\---



\## Naming Convention



SC300-Day01-01-Users-Created.png  

SC300-Day01-02-Group-Created.png  

SC300-Day01-03-Group-Members.png  

SC300-Day01-04-Role-Assigned.png  



\---



\## What This Lab Demonstrates



\- Identity centralisation using Entra ID  

\- Role-based access control (RBAC)  

\- Group-based permission management  

\- Implementation of least privilege  



\---



\## Notes



\- Avoid assigning roles directly to users  

\- Use groups for scalable access management  

\- Apply least privilege principle  



!\[Users Created](../03-Evidence/SC300-Day01-01-User1-Created.png)

