# IT Service Desk Support Simulations

This repository documents hands-on service desk simulations I completed to practice structured troubleshooting, user support, identity and access tasks, Windows endpoint support, networking, security-conscious support procedures, and professional ticket documentation.

The scenarios are designed to reflect common situations an entry-level Help Desk, Service Desk, Desktop Support, or junior IT Support technician may encounter.

> **Portfolio Note:** These scenarios were completed in a service desk simulation for hands-on learning. They do not represent professional production IT experience.

## Featured Service Desk Scenarios

### 1. DNS Misconfiguration & Network Connectivity Failure

Troubleshot a Windows workstation that could no longer access internet or internal resources after the user manually changed the DNS configuration.

Reviewed the scope of the issue, identified the incorrect DNS settings, referenced company documentation for the approved DNS servers, corrected the configuration, and verified connectivity with the user.

➡️ [View Ticket 13 – DNS Misconfiguration & Network Connectivity Failure](Ticket-13-DNS-Network-Connectivity/README.md)

---

### 2. Intermittent VPN & Remote Connectivity

Investigated a remote user's intermittent VPN, Remote Desktop, web browsing, and video-call connectivity problems.

Because multiple services and other devices on the user's home Wi-Fi were affected, the troubleshooting process focused on the underlying home network or internet connection rather than assuming the corporate VPN itself was the cause.

➡️ [View Ticket 12 – Intermittent VPN & Remote Connectivity](Ticket-12-Intermittent-Remote-Connectivity/README.md)

---

### 3. MFA Authentication Issue

Handled an authentication issue where a user could not complete MFA.

Verified the correct account and required authorization before performing the simulator's MFA reset process, then had the user re-enroll and confirmed that authentication worked successfully.

➡️ [View Ticket 06 – MFA Authentication Issue](Ticket-06-MFA-Authentication-Issue/README.md)

---

### 4. BitLocker Recovery & Laptop Lockout

Handled a security-sensitive endpoint recovery scenario involving a laptop that stopped at a drive-encryption recovery screen before Windows could start.

Completed identity verification before retrieving the recovery information, followed the simulator's BitLocker recovery workflow, and confirmed that normal laptop access was restored.

➡️ [View Ticket 09 – BitLocker Recovery & Laptop Lockout](Ticket-09-BitLocker-Recovery/README.md)

---

### 5. Management Access After User Promotion

Completed an approved access-provisioning request for an employee whose responsibilities changed after a promotion.

Verified authorization, located the correct identity, updated the user's Management group membership, and confirmed that the required access became available.

➡️ [View Ticket 04 – Management Access Provisioning](Ticket-04-Management-Access-Provisioning/README.md)

---

### 6. Browser Redirect & Performance Issue

Investigated unexpected browser redirects, excessive advertisements, and degraded workstation performance.

Compared installed browser extensions against approved-software documentation, removed an unapproved extension and unwanted application, ran a security scan, remediated an additional detected threat in the simulator, reset the browser, and verified normal operation.

➡️ [View Ticket 07 – Browser Redirect & Performance Issue](Ticket-07-Browser-Redirect-Performance/README.md)

---

### 7. Network Printer Not Responding

Troubleshot a network printer that appeared offline on a user's Windows workstation even though the physical printer was powered on.

Used printer documentation to verify the correct IP address, recreated the printer connection, printed a successful test page, and confirmed the resolution with the user.

➡️ [View Ticket 05 – Network Printer Troubleshooting](Ticket-05-Network-Printer-Troubleshooting/README.md)

## Skills Practiced

- Service desk ticket ownership
- Windows endpoint troubleshooting
- DNS and TCP/IP troubleshooting
- VPN and remote connectivity troubleshooting
- MFA and authentication support
- Identity verification
- BitLocker recovery fundamentals
- User and group administration
- Access provisioning
- Joiner-Mover-Leaver concepts
- Network printer configuration
- Remote desktop support
- Browser and application troubleshooting
- Endpoint security fundamentals
- Internal technical documentation usage
- User communication
- Resolution verification
- Ticket documentation
- Appropriate escalation awareness

## Troubleshooting Approach

Across these scenarios, I practiced following a repeatable troubleshooting process:

**Understand the issue → Determine scope → Gather evidence → Check likely causes → Use documentation → Make a controlled change → Test → Confirm with the user → Document**

A major focus of these simulations was avoiding assumptions.

For example:

- A user reporting "no internet" does not automatically mean the network is down.
- A VPN disconnecting does not automatically mean the VPN service is broken.
- A blue screen does not automatically mean Windows experienced a BSOD.
- A printer showing offline does not automatically mean the physical printer failed.
- A browser redirect should not automatically be treated as only a search-engine preference issue.
- A request for additional access should not automatically result in access being granted without authorization.

## Documentation Approach

Each scenario includes:

- Ticket context and business impact
- Troubleshooting or support workflow
- Selected screenshots showing meaningful evidence
- Resolution verification
- Technical concepts practiced
- Key lessons from the scenario

I intentionally selected only the screenshots that help tell the technical story rather than documenting every navigation click.

## Career Focus

I am currently building hands-on skills for entry-level roles including:

- Help Desk
- IT Support
- Service Desk
- Desktop Support
- Junior Systems Administration
- Microsoft / Identity Support

I am especially interested in continuing to develop skills in Windows administration, Microsoft technologies, troubleshooting, and Identity & Access Management.
