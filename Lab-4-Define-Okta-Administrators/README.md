# Lab 4: Define Okta Administrators

## Objective
Assign standard and custom administrator roles in Okta using role-based access control (RBAC), group assignments, custom admin roles, and resource sets.

---

## Skills Practiced

- Okta administrator management
- Role-Based Access Control (RBAC)
- Least privilege access control
- Group-based role assignments
- Custom administrator roles
- Resource sets
- Administrative auditing
- System Log review

---

## Scenario

The IT Help Desk team requires limited administrative permissions to support users without receiving full Super Admin access.

This lab demonstrates how to:

- Assign Help Desk Administrator roles
- Delegate permissions through groups
- Create custom administrator roles
- Configure resource sets
- Audit administrative privileges

---

## Tasks Completed

### Standard Administrator Roles
- Reviewed Help Desk Administrator permissions
- Assigned Help Desk Administrator role to the Help Desk group
- Verified inherited administrator access for Kim Sun
- Tested delegated administrative access

### Administrative Auditing
- Reviewed Administrator Overview dashboard
- Generated admin role assignment reports
- Reviewed System Log administrative events

### Custom Administrator Roles
- Created custom Suspend and Unsuspend Users role
- Configured All Users resource set
- Assigned custom role to Help Desk group
- Tested suspend and unsuspend permissions

---

## Screenshots

## Screenshots

### Step 1 — Create Help Desk Group

Created a Help Desk group for delegated administrator access.

![Image Alt][(./screenshots/00-create-help-desk-group.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/00-create-help-desk-group.png)

---

### Step 2 — Verify Group Creation

Verified the Help Desk group was successfully created in Okta.

![Image Alt][(./screenshots/01-help-desk-group-created.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/01-help-desk-group-created.png)

---

### Step 3 — Administrator Overview Page

Reviewed the Okta Administrators dashboard and administrative controls.

![Image Alt][(./screenshots/02-administrator-page.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/02-administrator-page.png)

---

### Step 4 — Assign Help Desk Administrator Role

Assigned the Help Desk Administrator role to the Help Desk group.

![Image Alt][(./screenshots/03-help-desk-admin-role-assigned.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/04-admin-role-assignments-report-settings.png)

---

### Step 5 — Configure Admin Role Assignment Report

Configured report settings for auditing administrator role assignments.

![Image Alt][(./screenshots/04-admin-role-assignments-report-settings.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/05-custom-role-created.png)

---

### Step 6 — Create Custom Administrator Role

Created a custom role for suspend and unsuspend user permissions.

![Image Alt][[(./screenshots/05-custom-role-created.png)](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/05-custom-role-created.png)](https://github.com/Kuhho/otka-iam-labs/blob/d9d5cf8fa3009f3d58b042dc158ad5b816057dc9/Lab-4-Define-Okta-Administrators/screenshots/05-custom-role-created.png)
![Image Alt](

---

### Step 7 — Configure Resource Set

Configured a resource set to scope delegated administrative access.

![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/d9d5cf8fa3009f3d58b042dc158ad5b816057dc9/Lab-4-Define-Okta-Administrators/screenshots/06-create-resource-set.png)
---

### Step 8 — Audit Administrative Changes

Reviewed exported administrator role assignment and audit event logs.

![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/6a4e05a1ac618f5643d50c2cd10da41b3a5f0460/Lab-4-Define-Okta-Administrators/screenshots/09-admin-changes-recent-events.png)
