# Lab 5: Implement Security Policies in Okta

## Overview
This lab focused on implementing layered security controls in Okta using authentication policies, network zones, MFA enrollment rules, session management, and password policies.

The objective was to strengthen organizational security posture by enforcing conditional access based on location, authentication methods, and device trust.

---

## Technologies Used
- Okta Admin Console
- Okta Verify
- Google Authenticator
- Network Zones
- Authentication Policies
- Authenticator Enrollment Policies
- Password Policies
- System Log Monitoring

---

## Security Policies Implemented

### Network Zones
- Corporate Network IP Zone
- Allowed Countries Dynamic Zone

### MFA & Authenticators
- Google Authenticator
- Okta Verify
- Device verification enforcement

### Enrollment Policies
- Allowed enrollment from approved countries
- Denied enrollment outside approved locations

### Authentication Policies
- Restricted country access blocking
- Public network MFA enforcement
- Corporate network conditional access

### Session Security
- 12-hour session lifetime
- 30-minute idle timeout
- Disabled persistent session cookies

### Password Security
- Minimum 12-character passwords
- Password history enforcement
- Common password restriction
- Account lockout protection
- Self-service password recovery controls

---

## Screenshots

| Screenshot | Description |
|---|---|
| ![](screenshots/corporate-network-zone-config.png) | Shows the configuration of the Corporate Network IP Zone and gateway IP setup. |
| ![](screenshots/corporate-network-zone-active.png) | Shows the Corporate Network zone successfully created and active. |
| ![](screenshots/authentication-country-region.png) | Shows authentication activity used to identify the current country/region for Allowed Countries configuration. |
| ![](screenshots/allowed-countries-config.png.png) | Shows the configuration of the Allowed Countries dynamic network zone. |
| ![](screenshots/allowed-countries-active.png) | Shows the Allowed Countries zone active in Okta Networks. |
| ![](screenshots/google-authenticator-added.png) | Shows Google Authenticator added as an authenticator in Okta. |
| ![](screenshots/default-enrollment-policy.png) | Shows the default authenticator enrollment policy configuration. |
| ![](screenshots/okta-verify-user-verification-settings.png) | Shows Okta Verify configuration with user verification settings enabled. |
| ![](screenshots/okta-verify-enrollment-policy.png) | Shows the Okta Verify Enrollment Policy configuration. |
| ![](screenshots/allow-enrollment-allowed-countries-rule.png) | Shows the enrollment rule allowing authentication enrollment from approved countries. |
| ![](screenshots/deny-enrollment-rule.png) | Shows the deny enrollment rule blocking enrollment outside approved countries. |
| ![](screenshots/enrollment-policy-rule-priority.png) | Shows enrollment policy rule priority and processing order. |
| ![](screenshots/add-rule-session-policy-standard.png) | Shows the Standards Global Session Policy rule configuration before creation. |
| ![](screenshots/global-session-policy-standards-config.png) | Shows session management settings including lifetime and idle timeout configuration. |
| ![](screenshots/global-session-policy-standards-active.png.png) | Shows the Standards Global Session Policy active in Okta. |
| ![](screenshots/restricted-countries-rule.png) | Shows authentication policy denying access from restricted countries. |
| ![](screenshots/public-network-rule.png) | Shows authentication policy enforcing stronger MFA on public networks. |
| ![](screenshots/corporate-network-rule.png) | Shows authentication policy allowing trusted corporate network access with MFA requirements. |
| ![](screenshots/password-policy-employees.png) | Shows the employee password policy enforcing strong password requirements. |
| ![](screenshots/allow-self-service-recovery-rule.png) | Shows the rule allowing self-service account recovery from approved countries. |
| ![](screenshots/block-self-service-recovery-rule.png) | Shows the rule blocking self-service account recovery from restricted locations. |
| ![](screenshots/password-policy-rule-priority.png) | Shows password policy rule order and recovery policy prioritization. |

---

## What I Learned
- How network zones influence authentication decisions
- How MFA policies differ between trusted and untrusted networks
- How Okta evaluates sign-on policy rules
- How session and password policies improve identity security
- How authentication policies support Zero Trust security models

---

## Real-World Use Case
Organizations use these security controls to enforce MFA, reduce unauthorized access, protect accounts from risky sign-ins, and implement location-aware authentication policies.
## Pending Validation / Follow-Up

### Device Registration Testing

This section was reviewed conceptually but full validation was not completed during the initial walkthrough due to unavailable preconfigured training users and enrolled devices.

### Planned Follow-Up
- Create test user
- Assign Okta access
- Enroll Okta Verify
- Register device
- Test device removal and re-enrollment
- Review Directory → Devices
- Validate Reset Authenticators workflow

### Status
⚠️ Pending Hands-On Validation

## Pending Validation

### Okta Dashboard Authentication Policy Testing

Policy rules were successfully configured but full validation testing was deferred due to the absence of a dedicated pilot test user with enrolled MFA and dashboard access.

### Planned Validation
- Create pilot test user
- Assign Okta Dashboard access
- Add user to Pilot Users group
- Enroll Okta Verify
- Test Public Network rule
- Test Corporate Network rule
- Validate System Log policy evaluation events

### Status

⚠️ Pending Hands-On Validation
## Password Policy Validation

Validated password policy behavior and self-service recovery controls.

### Password Policy Testing

Tested password requirements by:

- Signing in with a test account
- Accessing Security Settings
- Performing a password reset
- Confirming password requirements were enforced
- Verifying password policy restrictions

### Self-Service Recovery Testing

Reviewed account recovery workflow by:

- Triggering failed sign-in attempts
- Reviewing account lockout behavior
- Validating self-service unlock and recovery controls
- Confirming location-aware recovery restrictions
