# Phase 3 - Project Design

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Table Design

Table Name:
u_institution_details

## Fields

- Student Roll Number – Auto Number
- Student Name – Reference (User)
- Faculty Name – Reference (User)
- Branch – Choice (ECE, EEE, CSE)
- Email – String
- Phone Number – String
- Description – Multi String

## Role and ACL Design

- bb1 – Read access
- bb2 – Create access
- bb3 – Write access
- bb4 – Delete access
- Admin – Full access

## Access Flow

User → Role → ACL → Branch/Record → Access Granted or Denied
