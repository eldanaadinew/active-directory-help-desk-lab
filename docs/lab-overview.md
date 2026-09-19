# Lab Overview

## Objective

Build a small Windows domain environment and practice the identity and account-support tasks commonly handled by a Tier 1 help desk technician.

## Architecture

- Oracle VirtualBox hosts the virtual machines.
- Windows Server 2022 runs as domain controller `DC01`.
- AD DS stores domain users, organizational units, and security groups.
- DNS supports domain name resolution.
- Group Policy applies the account-lockout requirement.
- A Windows 11 test client validates domain login, DNS connectivity, and applied policy.

## Administrative Tasks Practiced

- Created and organized domain users.
- Created security groups and changed group membership.
- Reset passwords and applied account-access changes.
- Enabled, disabled, locked, and unlocked test accounts.
- Configured a five-attempt account-lockout policy.
- Reviewed authentication and connectivity symptoms using a structured troubleshooting process.

## Tools

- Windows Server 2022
- Active Directory Users and Computers
- Group Policy Management
- DNS Manager
- Server Manager
- Oracle VirtualBox
- Windows 11

## Validation Completed

The completed workflow verified that the Windows 11 client:

1. Used the domain controller for DNS.
2. Reached the domain controller by name and IP address.
3. Joined the domain.
4. Accepted a test domain-user login.
5. Received the expected Group Policy settings.
