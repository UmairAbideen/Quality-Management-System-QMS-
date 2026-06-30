# Quality-Management-System-QMS
A web-based Quality Management System developed for an imported Medical Device Distributor to comply with ISO 9001 quality processes.
Designed for organizations managing controlled documents, complaints, CAPA, audits, employee training, product recalls, and regulatory workflows.

## Features
KPI Dashboard
Charts & Metrics for:
Complaint statistics
Customer Feedback
CAPAs Open
<img width="1902" height="637" alt="image" src="https://github.com/user-attachments/assets/a3ae3637-531a-4e8e-a2ab-3cf06e67c384" />

## User Management
Multi-user system
Create Single User
Create Multiple Users thorugh excel
Role-based permissions
Department allocation
Approve new user


<img width="1900" height="832" alt="Blur_2- User1" src="https://github.com/user-attachments/assets/e06658bd-0647-45f6-896a-c5bd4e390441" />

<img width="1912" height="792" alt="image" src="https://github.com/user-attachments/assets/ead8df8e-2513-4a74-99a1-59d407082915" />

## Document Management
Policy Documents
SOP Repository - Department Wise visibility
Version Control
PDF Uploads
Document Download

<img width="1903" height="823" alt="Blur_Screenshot 2026-06-30 110306" src="https://github.com/user-attachments/assets/54f2a795-3e5a-44a3-8eec-21de5963dbe7" />

<img width="1912" height="822" alt="Blur_Screenshot 2026-06-30 110401" src="https://github.com/user-attachments/assets/7ee7b6af-5ede-4d9d-8bfa-976cc9683942" />

**Complaint Handling**
Complaint Form
Complaint Register
PDF Report

<img width="1876" height="885" alt="Blur_Screenshot 2026-06-30 110830 (1)" src="https://github.com/user-attachments/assets/04a3bb98-e722-4b3b-a12b-55eb850c2fda" />

---
<br>

## 📦 Modules

### 1. Core System
1. Dashboard  
2. User Management  
3. Document Management  
4. Document Control  

### 2. Quality Management
5. Complaint Handling  
6. Customer Feedback  
7. CAPA (Corrective & Preventive Action)  
8. Deviation Management  
9. Change Control  

### 3. Compliance & Risk
10. Risk Assessment  
11. Internal Audit  
12. Product Recall  

### 4. Operations
13. Employee Training  
14. Management Review Meeting  

---
<br>

## Modules Explanation

## Complaint Handling
Forms
Complaint Form
Complaint Log
Features
Complaint registration
Investigation workflow
Status tracking
PDF generation
Approval workflow
Electronic signature
Email notification

---
<br>

## Business Workflows

Complaint Raised

        ↓

QA Review

        ↓

Investigation

        ↓

Corrective Action

        ↓

Director Approval

        ↓

Complaint Closed

---
<br>

## User Roles

| Role | Responsibilities |
|------|------------------|
| Admin / QA | Complete system administration & QA Approvals |
| Director | Final approvals |
| Manager | Department approvals |
| Officer | Data entry & submissions |

---
<br>


## Departments

| Department |
|------------|
| QA |
| Supply Chain |
| Technical Service |
| Sales |

---
<br>

## ✨ Functionalities

### 🔐 Security
-  Authentication
-  Authorization
-  Role-based Access Control (RBAC)
-  Electronic Signature

### 📄 Document Management
-  PDF Upload
-  PDF Download
-  Document Search

### 📊 Reporting & Analytics
-  Dashboard
-  Charts & Metrics
-  Excel Export
-  PDF Reports

### ⚡ Productivity
-  Email Notifications
-  Pagination
-  Search & Filters
-  Multi-level Approval Workflow

### 💻 Technical Features
-  Laravel 10
-  MySQL Database
-  Eloquent ORM Relationships
-  PDF Generation
-  Excel Import & Export
-  Responsive User Interface
-  Production Deployment

---
<br>

## 🏗️ System Architecture

                                
                                               ┌────────────────────────────┐
                                               │           USERS            │
                                               │    QA | Manager| Director  │
                                               │          Officer           |
                                               └─────────────┬──────────────┘
                                                             │
                                                             ▼
                                        ┌─────────────────────────────────────────┐
                                        │            PRESENTATION LAYER           │
                                        │    Web UI (Dashboard, Forms, Reports)   │
                                        └────────────────────┬────────────────────┘
                                                             │
                                                             ▼
                                        ┌─────────────────────────────────────────┐
                                        │        APPLICATION LAYER (Laravel 10)   │
                                        │                                         │
                                        │  • Authentication & (RBAC)              │
                                        │  • SOP Modules                          │
                                        │  • Workflow / Approval                  │
                                        │  • CAPA / Audit / Complaint System      │
                                        │  • Document Control System              │
                                        │  • Notifications (Email)                │
                                        │  • Reporting (PDF / Excel / Charts)     │
                                        └────────────────────┬────────────────────┘
                                                             │
                                                             ▼
                                        ┌─────────────────────────────────────────┐
                                        ▼                                         ▼
                                 ┌────────────┐                            ┌──────────────┐     
                                 │ MySQL DB   │                            │ File Storage │     
                                 │ (Records)  │                            │ (PDFs/SOPs)  │     
                                 └────────────┘                            └──────────────┘                                                                                  │
                                       └─────────────────────┬────────────────────┘
                                                             │
                                                             ▼
                                        ┌─────────────────────────────────────────┐
                                        │        EXTERNAL SERVICES                │
                                        │  SMTP Email Server                      │
                                        │  Laravel Excel (Import/Export)          │
                                        │  DOMPDF (PDF Generation)                │
                                        └─────────────────────────────────────────┘

---
<br>

## 🛠️ Technologies Used

### Backend
- Laravel 10
- PHP 8

### Frontend
- Bootstrap
- JavaScript
- jQuery
- HTML5
- CSS3

### Database
- MySQL

### Libraries & Packages
- Laravel Excel
- DOMPDF

### Communication
- SMTP Mail

### Version Control
- Git
- GitHub
