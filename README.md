# DOMAIN HARDENING GPOs LAB

## Objective

The Domain hardening GPOs lab was done to build on group, account policy management and reduce vulnerabilities. The primary objective was to harden the system with calculated measures to ensure the group policy objectives were being met.

### Skills Learned

- Advanced understanding of group and account policy management.
- Creating Group policy objects.
- Creating and applying powershell scripts.
- Reducing vulnerabilties on windows machines.
- Understanding Azure machines.

### Tools Used

- Windows server machine.
- Windows 10 machine.
- Azure Windows RDP Host machine.
- Powershell for scripting.

## Steps

1. Creating a GPO to disable Local Link Multicast Name Resolution (LLMNR) 

Disabling LLMNR as it can accept any response as authentic allowing attackers to posion or spoof LLMNR responses.

2. Creating a GPO to setup account lockout 

Defending against brute force attacks with account lockouts.

3. Creating a GPO to enable verbose Powershell logging and transcription

Disabling powershell on a workstation VM to migitate protential threats from using it.

4. Scripting access control lists (ACLS)

Scripting ACL to manage which principals can access which resources.
