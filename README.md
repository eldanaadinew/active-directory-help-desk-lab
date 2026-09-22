# Active Directory Help Desk Lab

## Project Summary

This home lab documents a completed Windows domain and Tier 1 support environment built with Windows Server 2022, Active Directory Domain Services (AD DS), DNS, Group Policy, Windows 11, and Oracle VirtualBox. The lab was used to practice account administration, access troubleshooting, security-group management, domain authentication, and technical documentation.

The original local virtual machines were retired after the lab was completed to reclaim storage for schoolwork. This repository preserves the configuration, support scenarios, troubleshooting process, and skills demonstrated during the project.

## Skills Demonstrated

- Windows Server 2022 installation and configuration
- Active Directory Domain Services (AD DS) and DNS
- Organizational units, domain users, and security groups
- Password resets and account enable/disable actions
- Account-lockout testing and account unlocking
- Group Policy configuration
- Windows 11 domain joining and domain-user authentication
- Tier 1 troubleshooting and technical documentation
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
4. Practiced common Tier 1 tasks including password resets, account enable/disable actions, account unlocking, and group-membership changes.
5. Configured a five-attempt account-lockout policy through Group Policy.
6. Joined a Windows 11 test client to the domain and completed domain-user authentication.
7. Documented troubleshooting steps, support scenarios, results, and lessons learned.

## Help Desk Scenarios

The lab includes ticket-style documentation for:

- Forgotten passwords
- Locked user accounts
- Disabled accounts
- Security-group access requests
- Account-lockout policy configuration
- Domain login and connectivity troubleshooting

See [Help Desk Scenarios](docs/help-desk-scenarios.md) and [Troubleshooting Log](docs/troubleshooting-log.md).

## Troubleshooting Approach

For each issue, I:

1. Identified the symptoms and expected result.
2. Checked account status, credentials, group membership, DNS/connectivity, and relevant policies.
3. Applied the appropriate correction in the lab.
4. Tested the result after the change.
5. Documented the action, result, and lessons learned.

## Project Evidence

The original lab environment was completed locally and later retired to reclaim limited SSD capacity for schoolwork. The repository therefore focuses on written technical documentation rather than retaining large virtual-machine files.

Screenshots are not required to reproduce the documented workflow. Any screenshots added later will be reviewed for passwords, account details, or other sensitive information before publication.

## What I Learned

This project strengthened my understanding of how identity, authentication, DNS, Group Policy, and user access work together in a Windows domain. It also reinforced a structured support process: verify the user's account and symptoms, isolate the likely cause, make the least disruptive correction, test the result, and document the resolution.

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

## Note

Virtual-machine images, Windows installation media, passwords, and other sensitive or licensed files are intentionally not included in this repository.
