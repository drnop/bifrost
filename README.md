# bifrost

The purpose of Bifrost is to act as a bridge between internet cloud applications, such as SecureX Orcchestrator, and internal systems, such as ISE or Active Directory.

Apart from translating potentially complex and different APIs (ISE pxGrid, or Active Directory LDAP) to REST APIs, bifrost also provides some security features such as 
- verification of source IP
- verification of Authorization header, which needs to match generated token
- Duo MFA for administrators

## Installation

On a system with docker and docker-compose installed, download docker-compose.yml and run **docker-compose up**.
