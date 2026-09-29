# Phase 6 - Project Testing

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Testing Objective
To verify that the configured ACLs provide the required access to authorized users and restrict unauthorized access.

## Test Case 1 – EEE User

User with the bb1 role is impersonated and the Student Records list is opened.

Expected Result:
The user can view the permitted EEE branch records.

## Test Case 2 – User Without Required Role

A user without the required role is tested.

Expected Result:
The user cannot view the restricted records.

## Test Case 3 – Admin User

The Admin user is tested.

Expected Result:
Admin can view all records regardless of branch.

## Test Case 4 – Create Access

A user with bb1 and bb2 roles is tested.

Expected Result:
The user can view the permitted EEE records and access the New button.

## Test Case 5 – Write Access

A user with bb1, bb2 and bb3 roles is tested.

Expected Result:
The user can view and edit the permitted EEE branch records.

## Test Case 6 – Delete Access

A user with bb1, bb2, bb3 and bb4 roles is tested.

Expected Result:
The user can view, create, edit and delete the permitted EEE branch records.

## Testing Result
The ACL configuration was tested with different users and roles to verify record access and permissions.
