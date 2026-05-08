# Lab 2: Define Your Users in Okta

## Objective

Create and manage users in Okta by configuring custom user attributes, creating user accounts, managing account lifecycle statuses, and testing profile attribute mappings.

---

## Steps Performed

- Added a custom Region attribute to the Okta user profile
- Created a new Okta user account
- Updated user profile attributes
- Activated the user account
- Viewed user lifecycle activity
- Reset a user password
- Created a temporary password
- Expired a user password
- Suspended and deactivated a user account
- Reviewed Okta profile mappings
- Tested attribute synchronization between Okta and Okta Workflows

---

## Key IAM Concepts

- User provisioning
- Custom user attributes
- Identity lifecycle management
- Password reset workflows
- Account status management
- User suspension and deactivation
- Attribute mapping
- Identity synchronization
- Source of truth behavior

---

## Screenshots

### Custom Attribute Creation

![Region Attribute Creation](screenshots/01-region-attribute-creation.png)

![Region Attribute Created](screenshots/02-region-attribute-created.png)

---

### User Creation and Activation

![Add User Form](screenshots/03-add-user-form.png)

![Pending User Action](screenshots/04-pending-user-action.png)

![User Profile Details](screenshots/05-user-profile-details.png)

![Email Activation](screenshots/06-email-activation.png)

![Active User Status](screenshots/07-active-user-status.png)

---

### User Lifecycle Activity

 ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/06ca3b8bebcfedecb4562ade2f790b31bcdf9419/Lab-2-Define-Users/screenshots/08%20-%20User%20-%20lifecycle%20-%20activity%20.png)

---

### Password and Account Status Management

![Password Reset Workflow](screenshots/09-password-reset-workflow.png)

 ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/394b7dcf14b5d9dbeca82d2ff4034af124979a50/Lab-2-Define-Users/screenshots/10-%20password-reset-status.png)

![Temporary Password](screenshots/11-temporary-password.png)

![Password Expired Status](screenshots/12-password-expired-status.png)

---

### Suspension and Deactivation

![User Suspended](screenshots/13-user-suspended.png)

![User Deactivated](screenshots/14-user-deactivated.png)

---

### Attribute Mapping and Synchronization

![Profile Mapping](screenshots/15-profile-mapping.png)

 ![Image Alt](https://github.com/Kuhho/otka-iam-labs/blob/a2f0166e5889f058de4574724052629fe3444ebd/Lab-2-Define-Users/screenshots/16-workflows-sync--success.png)

---

## What I Learned

- Custom attributes help structure identity data for users in Okta.
- User lifecycle statuses show where an identity is in the onboarding, recovery, or offboarding process.
- Password reset and temporary password workflows are common IAM support operations.
- Suspending and deactivating users helps reduce access risk during offboarding.
- Attribute mappings control how identity data syncs between Okta and connected applications.
- Okta can act as a source of truth for downstream identity data.

---

## Real-World Use Case

Organizations use Okta user management to:

- Onboard employees into centralized identity systems
- Assign user attributes for access control and automation
- Recover user accounts through password reset workflows
- Lock, suspend, or deactivate accounts for security reasons
- Synchronize identity data across connected applications
- Support secure user lifecycle management
