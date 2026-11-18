# INC-004: Shared Folder Access Denied

## 1. Incident Description

A fictional employee named Anna from the Accounting department reported that she could not access the shared folder:

`\\SERVER01\Accounting`

Windows displayed an "Access Denied" error.

## 2. Initial Investigation

- Confirmed the folder path and error message.
- Asked whether other employees could access the folder.
- Confirmed that another Accounting employee, Maria, could access it.
- Identified that the issue might be related to user permissions.

## 3. Technical Investigation

Compared the Active Directory group memberships of Anna and Maria.

- Anna was a member of Domain Users.
- Maria was a member of Domain Users and Accounting.
- Anna was not a member of the required Accounting security group.

## 4. Root Cause

Anna was missing the required Accounting security group membership.

## 5. Resolution

After approval from the manager, an authorized administrator added Anna to the Accounting security group.

Anna signed out and signed in again to refresh her logon session.

## 6. Verification

- Anna successfully accessed the shared Accounting folder.
- She could read and edit files according to her assigned permissions.
- The access issue was resolved.

## 7. Skills and Concepts Practised

- NTFS permissions
- Share permissions
- Active Directory concepts
- Security groups and group membership
- Principle of Least Privilege
- Access-denied troubleshooting
- Incident investigation and documentation

## 8. Learning Notes

When investigating folder access problems, check the user's group membership and the relevant Share and NTFS permissions before making changes.

Always follow the authorization process and verify access after a change.

*Note: This is a simulated IT Support scenario. No real Active Directory environment or company accounts were modified.*