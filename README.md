# Active Directory Help Desk Lab

## Project Summary

This home lab demonstrates foundational Tier 1 IT support and Windows domain administration using Windows Server 2022, Active Directory Domain Services (AD DS), DNS, Group Policy, and Oracle VirtualBox. The project focuses on user-account support, access troubleshooting, security-group management, account-lockout testing, and clear technical documentation.

## Skills Demonstrated

- Windows Server 2022 installation and configuration
- Active Directory Domain Services and DNS
- Organizational units, domain users, and security groups
- Password resets and account enable/disable actions
- Account-lockout testing and account unlocking
- Group Policy configuration
- Tier 1 issue investigation and documentation
- Windows networking and domain-connectivity troubleshooting

## Lab Environment

| Component | Configuration |
|---|---|
| Hypervisor | Oracle VirtualBox |
| Domain controller | Windows Server 2022 (`DC01`) |
| Directory services | Active Directory Domain Services |
| Name resolution | DNS |
| Client | Windows 11 test client for domain authentication and policy validation |

## Work Completed

1. Installed and configured Windows Server 2022 in VirtualBox.
2. Promoted `DC01` to a domain controller and configured AD DS and DNS.
3. Created organizational units, test users, and security groups.
4. Practiced common Tier 1 tasks, including password resets, account enable/disable actions, lockout testing, account unlocking, and group-membership changes.
5. Configured a five-attempt account-lockout policy through Group Policy.
6. Documented support scenarios, troubleshooting steps, and results.

## Support Scenarios

The lab includes documented simulations for:

- Forgotten passwords
- Locked user accounts
- Disabled accounts
- Password-expiration and access issues
- Security-group membership requests
- Domain login and connectivity checks

See [Help Desk Scenarios](docs/help-desk-scenarios.md) for the ticket-style documentation.

## Troubleshooting Approach

For each issue, I:

1. Identified the user’s symptoms and expected result.
2. Checked account status, credentials, group membership, and relevant policies.
3. Applied the least disruptive approved correction.
4. Tested access after the change.
5. Documented the actions taken, result, and any required follow-up.

See [Troubleshooting Log](docs/troubleshooting-log.md) for examples.

## Screenshots

Public screenshots are intentionally omitted until every image has been reviewed and redacted. The evidence checklist is available in [screenshots/README.md](screenshots/README.md).

## Current Status

- Server and Active Directory configuration: Completed
- User and group administration exercises: Completed
- Account-lockout policy: Completed
- Windows 11 domain-user login and connectivity validation: Completed in the private lab

## What I Learned

This project strengthened my understanding of how identity, authentication, DNS, Group Policy, and user access work together in a Windows domain. It also reinforced the importance of verifying account status, testing changes, documenting each action, and communicating solutions clearly before closing a support request.

## Repository Structure

```text
active-directory-help-desk-lab/
├── README.md
├── SECURITY.md
├── docs/
│   ├── help-desk-scenarios.md
│   ├── lab-overview.md
│   └── troubleshooting-log.md
└── screenshots/
    └── README.md
```
