# Phase 5 - Project Development

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Development Implementation

### 1. User Creation
Created an EEE test user in ServiceNow.

### 2. Role Creation
Created the following custom roles:
- bb1
- bb2
- bb3
- bb4

Assigned the required roles to the test user.

### 3. Table Creation
Created the custom table:

u_institution_details

### 4. Field Creation
Added the following fields:
- Student Roll Number – Auto Number
- Student Name – Reference (User)
- Faculty Name – Reference (User)
- Branch – Choice (ECE, EEE, CSE)
- Email – String
- Phone Number – String
- Description – Multi String

### 5. Record Creation
Created multiple records with different Branch values:
- ECE
- EEE
- CSE

### 6. READ ACL
Created a record-level READ ACL for u_institution_details.

The ACL uses the bb1 role and restricts access according to the project requirement.

### 7. CREATE ACL
Created a record-level CREATE ACL for u_institution_details using the bb2 role.

### 8. WRITE ACL
Created a record-level WRITE ACL for u_institution_details using the bb3 role.

### 9. DELETE ACL
Created a record-level DELETE ACL for u_institution_details using the bb4 role.

### 10. Implementation Screenshots
Screenshots of the ServiceNow implementation are included as supporting evidence for this phase.
