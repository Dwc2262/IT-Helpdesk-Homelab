
# HD-001 — Active Directory Password Reset

## Ticket Overview
- **Ticket ID:** HD-001 (homelab reference)
- **Category:** Identity and Access Management
- **Priority:** Medium
- **Status:** Resolved
- **Environment:** Windows Server 2025, Active Directory, Windows 11 Pro

## Problem Description
A simulated employee, John Smith (`CORP\jsmith`), reported being unable to access his domain-joined Windows 11 workstation after forgetting his password.

**Affected workstation:** HD-CLIENT01  
**Domain controller:** HD-SERVER01  
**Domain:** corp.helpdesklab.test

## Troubleshooting and Resolution
1. Reproduced a failed sign-in attempt on HD-CLIENT01 using an incorrect password.
2. Opened Active Directory Users and Computers on HD-SERVER01.
3. Located the `jsmith` domain user account.
4. Selected **Reset Password** and configured a temporary password.
5. Enabled **User must change password at next logon**.
6. Returned to HD-CLIENT01 and authenticated with the temporary password.
7. Completed the required password change.

## Verification
Confirmed successful domain authentication on HD-CLIENT01 by running:

```cmd
whoami
```

Expected result:

```text
corp\jsmith
```

## Outcome
The simulated employee's domain access was restored. The issue was documented and closed in Jira Service Management.

## Skills Demonstrated
- Active Directory user account administration
- Password reset procedures
- Windows domain authentication
- Account access troubleshooting
- Jira Service Management ticket documentation

## Evidence
Screenshots documenting the troubleshooting and resolution process will be added below.

## Lab Disclaimer
This ticket represents a simulated support scenario performed in a personal IT homelab. No production user accounts were affected.
  
