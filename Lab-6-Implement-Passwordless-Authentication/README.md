# Lab 6 – Implement Passwordless Authentication

## Overview
This lab focused on implementing passwordless authentication and strengthening identity security using Okta Verify and Okta FastPass.

The lab included configuring authenticator settings, dynamic network zones, enrollment policies, device management, session policies, and authentication rules to support phishing-resistant and Zero Trust authentication.

---

## Objectives
- Configure Okta Verify enrollment requirements
- Create dynamic network zones
- Implement authenticator enrollment policies
- Manage registered devices
- Configure global session policies
- Enable Okta FastPass
- Create authentication policy rules
- Test passwordless authentication
- Review authentication activity in system logs

---

## Skills Practiced
- Passwordless Authentication
- Okta FastPass
- Okta Verify Configuration
- Dynamic Network Zones
- Authentication Policies
- Global Session Policies
- Conditional Access
- Device Management
- MFA Enforcement
- Authentication Monitoring
- System Log Analysis
- Zero Trust Security Concepts

---

## Technologies Used
- Okta Admin Console
- Okta Verify
- Okta FastPass
- Authentication Policies
- Network Zones
- GitHub Documentation

---

## Lab Activities

### 1. Enforce User Verification
Configured Okta Verify to require biometric or device passcode verification during enrollment.

### 2. Dynamic Network Zones
Created an Allowed Countries dynamic network zone to support location-based access policies.

### 3. Authenticator Enrollment Policy
Configured an enrollment policy for Pilot Users and enforced location-based enrollment permissions.

### 4. Device Management
Managed and reviewed registered devices connected to Okta Verify.

### 5. Global Session Policy
Configured session standards including session lifetime and inactivity timeout.

### 6. Enable Okta FastPass
Enabled FastPass to support phishing-resistant passwordless authentication.

### 7. Restricted Countries Rule
Configured an authentication rule to deny dashboard access from unauthorized countries.

### 8. Okta FastPass Authentication Rule
Created a phishing-resistant authentication rule requiring Okta FastPass.

### 9. Authentication Testing and Logs
Tested passwordless authentication and reviewed system logs to validate policy behavior.

---

## Screenshots

### Okta Verify User Verification
<img width="900" alt="Okta Verify User Verification" src="screenshots/01-okta-verify-verification.png">

---

### Allowed Countries Dynamic Zone
<img width="900" alt="Allowed Countries Dynamic Zone" src="screenshots/02-allowed-countries-zone.png">

---

### Enrollment Policy Configuration
<img width="900" alt="Enrollment Policy Configuration" src="screenshots/03-enrollment-policy.png">

---

### Device Management
<img width="900" alt="Device Management" src="screenshots/04-device-management.png">

---

### Global Session Policy
<img width="900" alt="Global Session Policy" src="screenshots/05-global-session-policy.png">

---

### FastPass Enabled
<img width="900" alt="FastPass Enabled" src="screenshots/06-fastpass-enabled.png">

---

### Restricted Countries Rule
<img width="900" alt="Restricted Countries Rule" src="screenshots/07-restricted-countries-rule.png">

---

### Okta FastPass Rule
<img width="900" alt="Okta FastPass Rule" src="screenshots/08-fastpass-rule.png">

---

### Authentication Testing
<img width="900" alt="Authentication Testing" src="screenshots/09-authentication-testing.png">

---

### System Log Validation
<img width="900" alt="System Log Validation" src="screenshots/10-system-log-validation.png">

---

## What I Learned
Passwordless authentication reduces dependence on passwords while improving security and user experience. Okta FastPass and authentication policies support phishing-resistant authentication and help organizations implement Zero Trust identity security models.

This lab reinforced how policy-based authentication, network conditions, and device trust work together to protect access.

---

## Real-World Relevance
Organizations implement passwordless authentication to:

- Reduce password-based attacks
- Improve user authentication experience
- Enforce phishing-resistant access
- Support Zero Trust security strategies
- Strengthen identity and access management controls

### 4. Device Management
Reviewed Okta device registration and authenticator reset workflows.

**Note:** Full device re-enrollment testing was deferred due to test-user enrollment and device registration requirements within the current lab environment. Administrative device inventory and authenticator reset processes were reviewed conceptually.
