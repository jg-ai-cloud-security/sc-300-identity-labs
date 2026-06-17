\# Day 21 Detection Queries



\## Authentication Method Changes



AuditLogs

| where ActivityDisplayName contains "Authentication"



\---



\## FIDO2 Registration Events



AuditLogs

| where ActivityDisplayName contains "FIDO"



\---



\## Passwordless Authentication Events



SigninLogs

| where AuthenticationRequirement contains "passwordless"



\---



\## Windows Hello Sign-ins



SigninLogs

| where AuthenticationMethodsUsed contains "Windows Hello"

