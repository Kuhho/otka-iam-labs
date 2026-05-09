# Lab 3 - Manual Group Assignment & Group Rules

## Overview
This lab focused on managing Okta groups through both manual user assignment and automated group rules based on user attributes.

The objective was to understand how organizations use groups to organize users, automate access management, and simplify identity administration across enterprise environments.

---

## Skills Demonstrated
- Creating and managing Okta groups
- Manually assigning users to groups
- Creating group membership rules
- Configuring user attribute-based automation
- Understanding automated access provisioning
- Basic troubleshooting of group rule conditions

---

## Key IAM Concepts
### Role-Based Access Control (RBAC)
Users can inherit permissions and application access through group membership instead of receiving permissions individually.

### Attribute-Based Access Control (ABAC)
Access decisions can be automated using user attributes such as:
- Department
- Employee Type
- Job Title

### Identity Automation
Okta group rules automatically place users into groups when profile conditions match configured rules.

---

## Lab Activities Completed
- Created new Okta groups
- Assigned users manually to groups
- Verified group membership
- Created automated group rules
- Configured user attribute conditions
- Activated and tested group assignment rules
- Reviewed automated membership behavior

---

## Real-World Use Case
Organizations use group rules to automate onboarding and access management processes.

Example:
- If a user's department is set to "Finance"
- Okta automatically assigns the user to the Finance group
- The user then receives access to required applications and resources

This reduces manual administration and improves scalability in large enterprise identity environments.

---

## Screenshots

| Screenshot | Description |
|---|---|
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/01-groups-page.png) | Shows the Okta Groups page used to begin group management. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/02-create-group.png) | Shows the creation of a new group in Okta. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/03-assign-users.png) | Shows users manually assigned to the Executives group. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/04-groups-rules-membership.png) | Shows additional groups created for rule-based group membership. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/05-adding-rules-group.png) | Shows a group rule being configured based on existing group membership. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/06-verify-rules-group.png) | Shows the activated group rule and verification of the rule logic. |
|  ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6b737fe22fb3e7688b9c297c44b4032e5b2d4d5c/Lab-3-Manual-Group-Assignment/07-finance-accounting-group-rule.png) | Shows an advanced attribute-based rule using department values for Finance and Accounting users. |
---

## Outcome
This lab strengthened my understanding of how identity platforms like Okta automate access management using groups, rules, and user attributes within enterprise IAM environments.
