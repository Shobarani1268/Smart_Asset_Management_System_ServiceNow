# Smart Asset Management System using ServiceNow

## Overview

The Smart Asset Management System is a ServiceNow application developed to automate the asset request and allocation process within an organization. Employees can request laptops through the Service Portal, while administrators can manage inventory, approvals, and asset assignments efficiently.

## Features

- Asset Inventory Management
- Asset Request Management
- Service Portal Record Producer
- Email Notifications
- Business Rules Automation
- Asset Availability Validation
- Warranty Expiry Check
- Automatic Asset Assignment Management

## Technologies Used

- ServiceNow
- App Engine Studio
- Service Portal
- Record Producer
- Flow Designer
- Business Rules
- Email Notifications

## Modules

### Asset Inventory
Stores all asset details such as Asset ID, Asset Name, Brand, Model, Status, Assigned To, Purchase Date, and Warranty Expiry.

### Asset Request
Stores employee requests for company assets.

### Service Portal
Employees can request a laptop using a user-friendly form.

## Business Rules

### 1. Prevent Asset Reassignment
Prevents users from requesting an asset that is already assigned.

### 2. Clear Assigned User
Automatically clears the Assigned To field when the asset status becomes Available.

### 3. Warranty Expiry Check
Automatically changes the asset status to Maintenance when the warranty has expired.

## Workflow

Employee
↓
Service Portal
↓
Record Producer
↓
Asset Request Created
↓
Business Rules Executed
↓
Email Notification Sent
↓
Administrator Reviews Request
↓
Asset Assigned

## Project Screenshots

- Service Portal
- Asset Inventory
- Asset Request
- Business Rules
- Email Notification
  https://drive.google.com/drive/folders/1k3ZeVLoMzrI1SFPXk6p7IUef6bZ6JY8w?usp=sharing
## Future Enhancements

- Manager Approval Workflow
- Asset Return Process
- Dashboard and Reports
- SLA Integration
- Mobile Access

## Developed By

**Arnipalli Shobarani**

 ServiceNow CSA Certified | ServiceNow CAD Certified | Aspiring ServiceNow Developer
