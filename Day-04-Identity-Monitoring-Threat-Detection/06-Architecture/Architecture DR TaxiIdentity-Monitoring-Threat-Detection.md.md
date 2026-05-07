\# SC-300 Day 04 — Identity Monitoring \& Threat Detection Architecture



\## Overview



This architecture demonstrates how authentication activity and sign-in events are monitored within the DR Taxi environment using Microsoft Entra ID visibility and authentication monitoring processes.



The implementation improves visibility into suspicious authentication behaviour and supports threat investigation workflows aligned with Zero Trust security principles.



\---



\# Components



\## Users

\- Drivers

\- Operations staff

\- Administrative users



\## Microsoft Entra ID

Central identity provider responsible for authentication, sign-in visibility, and authentication monitoring.



\## Authentication Events

User authentication activity generated during access to cloud services and administrative resources.



\## Sign-In Logs

Authentication monitoring platform used to review:

\- Successful sign-ins

\- Failed sign-ins

\- Administrative authentication activity

\- IP address visibility

\- Application access events



\## Monitoring \& Investigation

Processes used to analyse suspicious authentication activity and investigate identity-related security events.



\## Threat Detection

Authentication analysis used to identify suspicious sign-in behaviour and improve identity security monitoring.



\---



\# Architecture Flow



Users

↓

Microsoft Entra ID

↓

Authentication Events

↓

Sign-In Logs

↓

Monitoring \& Investigation

↓

Threat Detection



\---



\# Key Security Principles



\- Authentication visibility

\- Identity monitoring

\- Threat detection

\- Security event investigation

\- Zero Trust monitoring



\---



\# Constraints



Some advanced Microsoft Entra Identity Protection capabilities may require additional licensing.



The implementation was completed using available authentication monitoring and sign-in visibility features within the tenant environment.



\---



\# Business Outcome



The identity monitoring implementation improves authentication visibility and strengthens threat detection capabilities within the DR Taxi environment.

