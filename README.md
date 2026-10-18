
# IT Help Desk & Active Directory Homelab

## Project Overview
This project documents a simulated enterprise IT support environment built to develop practical experience in Windows administration, Active Directory, networking, and help desk troubleshooting.

The lab uses Windows Server 2025 and Windows 11 virtual machines connected through Oracle VirtualBox. Support scenarios are tracked in Jira Service Management and documented with troubleshooting steps, verification, and screenshots.

## Technologies & Tools
- Windows Server 2025 Standard Evaluation
- Windows 11 Pro
- Active Directory Domain Services (AD DS)
- DNS and TCP/IP networking
- Oracle VirtualBox and NAT Network
- Jira Service Management
- Windows Command Prompt and PowerShell

## Lab Environment
| Component | Configuration |
|---|---|
| Domain | corp.helpdesklab.test |
| Domain Controller | HD-SERVER01 |
| Client Workstation | HD-CLIENT01 |
| Network | Helpdesk-Lab (192.168.50.0/24) |
| Domain Controller IP | 192.168.50.10 |
| Operating Systems | Windows Server 2025 / Windows 11 Pro |

## Implemented Infrastructure
- Installed and configured Windows Server 2025 and Windows 11 virtual machines.
- Configured a shared VirtualBox NAT Network.
- Installed Active Directory Domain Services and promoted HD-SERVER01 to a domain controller.
- Configured and validated internal DNS resolution.
- Joined HD-CLIENT01 to the Active Directory domain.
- Created and authenticated a simulated domain user account.
- Verified network connectivity and domain authentication using command-line tools.

## Help Desk Ticket Documentation
| Ticket | Scenario | Status |
|---|---|---|
| HD-001 | Active Directory Password Reset | Completed — documentation pending |

Each ticket will include the reported issue, troubleshooting process, resolution, verification, and supporting screenshots.

## Skills Demonstrated
- Active Directory user account administration
- Windows domain authentication
- DNS troubleshooting and network connectivity testing
- Windows Server administration
- Virtual machine deployment and configuration
- IT service ticket documentation

## Project Disclaimer
This is an independently built, simulated IT support lab for hands-on learning and professional development. All employees, support requests, and incidents are fictional.
  
