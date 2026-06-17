\# Investigation Findings 4 – Phishing-Resistant MFA Strength Review



\## Overview



The Phishing-Resistant MFA Authentication Strength was reviewed to evaluate the highest level of authentication protection available within Microsoft Entra ID.



\## Findings



The Authentication Strength only permits authentication methods that are resistant to phishing attacks and credential harvesting.



Supported methods include:



\- Windows Hello for Business

\- Passkeys (FIDO2)

\- Certificate-Based Authentication



These methods use cryptographic authentication rather than passwords, making them significantly more secure than traditional MFA methods.



\## Security Assessment



This Authentication Strength provides the highest authentication assurance level available within Microsoft Entra ID.



\## Recommendation



Require Phishing-Resistant MFA for:



\- Global Administrators

\- Security Administrators

\- Privileged Role Administrators

\- Critical business applications

\- Sensitive organizational resources



\## Conclusion



Phishing-Resistant MFA aligns with Microsoft's Zero Trust model and provides the strongest protection against modern identity-based attacks.

