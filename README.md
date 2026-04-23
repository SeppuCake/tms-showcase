# Tenant Management System (TMS)

## Overview

Tenant Management System (TMS) is a web-based platform designed to manage tenants, payments, and maintenance operations for residential properties.

## Purpose

To replace fragmented manual processes with a centralized system that improves visibility, financial tracking, and communication between management and tenants.

## Key Features

- Tenant registration and management
- Unit-based billing and payment tracking
- Maintenance and complaint request system
- Dashboard with statistics and summaries
- Automated notifications (SMS & WhatsApp)
- Announcements and notices
- Report generation (PDF)

## Tech Stack

- Laravel (PHP Framework)
- MySQL
- JavaScript (jQuery, AJAX)
- Bootstrap

## My Role

- Sole developer (client-commissioned project)
- Gathered requirements directly from client
- Designed system workflows and database structure
- Developed full backend and frontend
- Integrated external APIs (SMS & WhatsApp)
- Delivered complete working system

## Impact

- Improved tracking of maintenance fees and payments
- Reduced manual administrative workload
- Automated tenant communication
- Increased efficiency in property management operations

---

## Screenshots

### Dashboard / Main Navigation

A centralized interface that gives management quick access to tenant, billing, complaint, and reporting modules.

![Dashboard](images/tms-dashboard.png)

---

### Maintenance Requests

A complaint and maintenance management view used to track tenant-reported issues and follow-up actions.

![Maintenance Requests](images/tms-complaints.png)

---

### Billing & Payments

A payment management module used to monitor charges, balances, and payment records by unit.

![Billing & Payments](images/tms-billing-payments.png)

---

### Reports Overview

A reporting screen that helps management review payment, occupancy, and operational summaries.

![Reports Overview](images/tms-reports-overview.png)

---

### Report Generation

A module for generating exportable management reports for billing and operational review.

![Report Generation](images/tms-report-generator.png)

---

### Notifications Module

A communication module used to send SMS and WhatsApp messages directly from the system.

![Notifications Module](images/tms-notifications.png)

---

### Mobile View

A responsive mobile navigation view showing accessibility across smaller devices.

![Mobile View](images/tms-mobile-view.png)

---

## System Flow

Tenant submits request → System records data → Management reviews → Action assigned → Status updates → Completion & reporting

## Challenges & Solutions

**Challenge:** Manual tracking of payments and tenants  
**Solution:** Built structured database with unit-based billing system

**Challenge:** Slow communication with tenants  
**Solution:** Integrated SMS and WhatsApp notification system

**Challenge:** Managing multiple roles and permissions  
**Solution:** Implemented role-based access control (RBAC)

## Key Design Decisions

- Used Laravel MVC for maintainability and scalability
- Designed role-based system for multiple user types
- Integrated external APIs for automated communication
- Structured database for unit-based financial tracking

## Before vs After

Before:

- Manual records
- No centralized tracking
- Slow communication with tenants

After:

- Fully digital system
- Real-time tracking
- Automated messaging and reporting

## Testing Approach

- Manual testing across different user roles
- Validation of billing and payment flows
- Testing of notification delivery (SMS & WhatsApp)
- Edge case testing for maintenance workflows

## Project Structure (Conceptual)

- Frontend (UI & user interaction)
- Backend (Laravel business logic)
- Database (tenant, billing, maintenance data)
- API layer (SMS & WhatsApp integration)

**Features:** Tenant Management · Billing System · Maintenance Workflow · Notifications · Reporting

## Future Improvements

- Migrate frontend to modern framework (Vue/React)
- Improve performance for larger datasets
- Add mobile-friendly enhancements
- Introduce real-time notifications

## 🔒 Confidentiality Notice

This project was developed for a client.  
All sensitive data and source code are intentionally omitted due to NDA.
