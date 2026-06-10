# Lab 7: Manage Network Zones

## Overview

This lab demonstrates how to configure and manage Okta Network Zones to enforce authentication policies based on user location, IP address, and network risk.

## Objectives

- Create an IP Network Zone for a corporate network
- Create a Dynamic Zone for allowed countries
- Enable Okta Verify Push Notification
- Configure authentication policy rules using Network Zones
- Test public and corporate network access
- Block Tor anonymizer traffic

## Technologies Used

- Okta Workforce Identity Cloud
- Network Zones
- Dynamic Zones
- Authentication Policies
- Okta Verify
- System Log

## Skills Demonstrated

- Okta Administration
- Identity and Access Management (IAM)
- Conditional Access
- MFA Enforcement
- Zero Trust Security
- Authentication Policy Configuration

## Screenshots

## Screenshots

### Security Networks Page
![Security Networks Page](screenshots/01-security-networks-page.png)

Navigated to Security > Networks to begin configuring Okta Network Zones.

### Add IP Zone
![Add IP Zone](screenshots/02-add-ip-zone.png)

Created an IP Network Zone for the corporate network.

### System Log Country Lookup
![System Log Country Lookup](screenshots/03-system-log-country.png)

Reviewed authentication activity in the System Log to identify the country/region for the Allowed Countries Dynamic Zone.

### Add Dynamic Zone
![Add Dynamic Zone](screenshots/04-add-dynamic-zone.png)

Created a Dynamic Network Zone for allowed countries.

### Okta Verify Settings
![Okta Verify Settings](screenshots/05-okta-verify-settings.png)

Opened the Okta Verify authenticator settings to modify available verification methods.

### Okta Verify Enabled Options
![Okta Verify Enabled Options](screenshots/06-okta-verify-enabled-options.png)

Enabled TOTP, Push Notification, and Okta FastPass for Okta Verify.

### Okta Dashboard Policy
![Okta Dashboard Policy](screenshots/07-okta-dashboard-policy.png)

Opened the Okta Dashboard authentication policy to configure network-based access rules.

### Restricted Countries Rule
![Restricted Countries Rule](screenshots/08-restricted-countries-rule.png)

Created a Restricted Countries rule to deny access when Pilot Users sign in from outside the Allowed Countries zone.
## Lessons Learned

This lab strengthened my understanding of how Okta uses Network Zones and authentication policies to enforce location-based access controls and reduce authentication risk.
