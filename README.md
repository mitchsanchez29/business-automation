![Banner](readme-banner.svg)

[![Back to Profile](https://img.shields.io/badge/←_Back_to_Profile-0f172a?style=for-the-badge)](https://github.com/mitchsanchez29)
[![Portfolio](https://img.shields.io/badge/Portfolio-14b8a6?style=for-the-badge)](https://michelle-systems-studio.lovable.app)
[![Reporting & Analytics](https://img.shields.io/badge/Reporting_%26_Analytics-14b8a6?style=for-the-badge)](https://github.com/mitchsanchez29/reporting-analytics)
[![Finance & Operations](https://img.shields.io/badge/Finance_%26_Operations-14b8a6?style=for-the-badge)](https://github.com/mitchsanchez29/finance-operations)

---

##  Featured Projects

| # | Project | Type | Tech Stack |
|---|---------|------|------------|
| 01 | [Lead Operations Management System](#lead-operations-management-system) |  Work Project | Google Sheets · Apps Script |
| 02 | [Slack Payment Notification Automation](#slack-payment-notification-automation) |  Work Project | Zapier · Slack webhook |
| 03 | [Automated Quotation & CRM](#automated-quotation--crm-system) |  Portfolio Project | Apps Script · Gmail |
| 04 | [Lead Management Automation](#lead-management-automation) |  Portfolio Project | Airtable · Zapier |

---

## Lead Operations Management System

**Type:** Work Project

### Business Problem

The client managed leads through a 8-stage coordination process using multiple spreadsheets and manual updates. Tracking progress, assigning tasks, and ensuring every required step was completed became time-consuming and difficult to monitor.

### Business Goal

Create a centralized workflow that standardizes the coordination process, improves visibility, and keeps every lead moving through each stage consistently.

### My Solution

Built a Google Sheets and Apps Script workflow automation that manages the entire coordination process from lead approval to completion.

The system automatically:
- Creates a unique Sponsor ID for approved leads
- Generates a dedicated Google Drive folder for each lead
- Stores all records in a centralized Master Tracker
- Loads lead information into the Coordinator Workspace
- Guides coordinators through a standardized 8-stage checklist
- Updates the Master Tracker automatically as each stage is completed
- Provides a live dashboard showing the status of every lead in the pipeline

**Workflow**

<img width="901" height="1654" alt="ChatGPT Image Aug 13, 2026, 04_25_52 PM" src="https://github.com/user-attachments/assets/8fd6b19a-5ef6-4dca-b9cd-ed5c19edcaa0" />


### Key Features

- Google Form lead intake
- Duplicate lead validation
- Coordinator approval (Approve / Reject / Cancel)
- Automatic Sponsor ID generation
- Automatic Google Drive folder creation
- Centralized Master Tracker
- Coordinator Workspace with auto-populated lead details
- 8-stage checklist with automated stage progression
- Real-time dashboard for operational visibility


**Screenshots**

|  Coordinator Workspace |  System Overview |
|---|---|
| <img width="654" height="604" alt="Screenshot 2026-08-13 143641" src="https://github.com/user-attachments/assets/b5257624-a1bf-4416-8270-c641a204b7e2" /> | <img width="722" height="478" alt="Screenshot 2026-08-13 161632" src="https://github.com/user-attachments/assets/9c887ce6-a040-46af-8b6f-3cfc96bc4bab" /> |
| Coordinators manage and update leads from one workspace. | A guided entry point that organizes the system into clear operational areas, making it easier to navigate the Sponsor workflow from lead intake through final placement.|

| Lead & Sponsor Search | Sponsor Workspace Access | Questionnaire & Application |
|---|---|---|
| <img width="323" height="326" alt="Lead & Sponsor Search" src="https://github.com/user-attachments/assets/af43736e-7924-4936-8ea7-4557c7973b30" /> | <img width="323" height="326" alt="Sponsor Workspace Access" src="https://github.com/user-attachments/assets/af43736e-7924-4936-8ea7-4557c7973b30" /> | <img width="357" height="588" alt="Questionnaire & Application" src="https://github.com/user-attachments/assets/8f795229-94e4-402d-9f4e-018e24c39f9f" /> |

The sidebar provides a centralized navigation point for finding Leads and Sponsors, accessing Sponsor workspaces, checking workflow status, and sending the appropriate Questionnaire or Application based on the Sponsor's current stage.

|  Email received by the Client |  Email Notification to the Coordinator |
|---|---|
| <img width="923" height="517" alt="Screenshot 2026-08-13 144337" src="https://github.com/user-attachments/assets/3a396a67-054c-4925-9d30-7ac27a5b76b7" />| <img width="856" height="514" alt="Screenshot 2026-08-13 144502" src="https://github.com/user-attachments/assets/5fe555c8-fc28-497c-a706-e75fc26a28ba" />
| Automatically sends the Questionnaire or Application to the Sponsor via email. | Automatically notifies the Coordinator when the Sponsor submits a response. |


|  Auto Drive Folder |  Master Tracker |
|---|---|
| <img width="594" height="462" alt="Screenshot 2026-08-13 151147" src="https://github.com/user-attachments/assets/408cd077-9b20-4057-9cb8-c109f2cb16fe" /> | <img width="676" height="502" alt="Screenshot 2026-08-13 154833" src="https://github.com/user-attachments/assets/ccf99422-5f95-49b3-9688-ba267c5e56d0" />
| Automatically creates a Drive folder for every approved lead and save docs. | Displays real-time workflow progress and operational metrics. |


### Business Questions This System Answers

- Where is each lead in the workflow right now?
- Which stage requires coordinator action?
- Which records are delayed or waiting for completion?
- How many leads are currently active in each stage?

### Business Value

- Standardizes a complex 10-stage coordination process
- Reduces manual tracking and repetitive updates
- Improves visibility across the entire workflow
- Keeps all lead information synchronized in one source of truth
- Helps coordinators complete tasks consistently while giving management real-time pipeline visibility

### Tech Stack

`Google Sheets` `Google Apps Script` `Workflow Automation` `Dashboard`

[⬆ Back to Top](#business-automation)

---

# Slack Payment Notification Automation

Real-time Slack alerts for upcoming, overdue, and received payments—keeping the operations and sales team informed without manual updates.

## Business Problem

The team relied on manually checking payment trackers and sending status updates, causing delays in follow-ups and reducing visibility across the sales team.

## Business Goal

Automatically notify the team about payment updates, enabling faster collections and better visibility.

## My Solution

Built an automated workflow using Google Sheets, Google Apps Script, Zapier, and Slack. Payment status changes automatically trigger real-time Slack notifications for upcoming payments, overdue accounts, and payments received.

## Workflow
<img width="291" height="476" alt="Screenshot 2026-08-07 161939" src="https://github.com/user-attachments/assets/9f2e10e4-af2b-4267-8bf1-805a5505c3bb" />

## Key Features

- Real-time Slack notifications
- Upcoming, overdue, and payment received alerts
- Automated payment status monitoring
- Supports Setters, Dialers, Closers, and Operations

## Business Value

- Eliminated manual payment updates
- Improved team visibility
- Enabled faster payment follow-ups

## Tech Stack

`Google Sheets` · `Google Apps Script` · `Zapier` · `Slack`

[⬆ Back to Top](#business-automation)

---

## Automated Quotation & CRM

**Type:** CASE STUDY

**Business Problem:** Quotes were created manually, tracked in disconnected spreadsheets, and sent one by one — slow, easy to mess up, and hard to follow up on.

**Business Goal:** Remove the manual work from quote creation and give the team one place to track every quote's status.

**My Solution:** A fully automated pipeline triggered by a Google Form submission. Apps Script generates a unique quote number, fills in a Google Docs template, converts it to PDF, saves it in Drive, and emails it to the client through Gmail — with zero manual steps in between.

**Workflow**

<img width="692" height="258" alt="Screenshot 2026-06-05 181724" src="https://github.com/user-attachments/assets/6e47ecc1-7553-4847-84cb-87bd3fb6ab26" />

**Key Features:**
- Auto-generated sequential quote numbers
- Status tracking dashboard in Google Sheets
- PDFs stored and organized automatically in Google Drive
- Client email sent with the quote attached — no manual sending

**Screenshots**
##  System Walkthrough

|  Quotation Request Form |  Lead Tracker |
|---|---|
| <img width="317" height="693" alt="Screenshot 2026-08-07 154604" src="https://github.com/user-attachments/assets/643757d2-e905-43df-8bb9-dd594b6ebde4" />| <img width="600" alt="Lead Tracker" src="https://github.com/user-attachments/assets/f4f73371-54c9-4d2f-841e-1372d42445fc" /> |
| Clients submit quotation requests through a Google Form, automatically triggering the quotation workflow. | Centralized tracker that records every quotation, generates a unique quotation number, and monitors the status of each request. |

|  Dashboard Summary |  Automated Quote Delivery & Storage |
|---|---|
| <img width="600" alt="Dashboard Summary" src="https://github.com/user-attachments/assets/d1705835-5754-47bb-9624-3eac80989d28" /> | <img width="800" alt="Auto-generated Response and Drive Storage" src="https://github.com/user-attachments/assets/1ec987a5-3cb4-41c0-9b54-4807398515c7" /> |
| Provides a real-time overview of quotation activity, status, and overall workflow performance. | Automatically generates the quotation, converts it to PDF, stores it in Google Drive, and emails it to the client without manual intervention. |

**Business Questions Answered:**
- Which quotes have gone out, and what's their status?
- How many quotes are pending vs. sent this month?

**Business Value:** Fewer manual steps from quote to delivery, faster turnaround for clients, and one clean tracking system instead of scattered files.

**Tech Stack:** `Google Forms` `Apps Script` `Google Sheets` `Google Docs` `Drive` `Gmail` `PDF`

[⬆ Back to Top](#business-automation)

---

## Lead Management Automation

**Type:** Portfolio Project

### Business Problem

New leads were captured manually across different tools, making it difficult to organize lead information, track pipeline progress, and ensure the sales team was notified immediately. This increased the risk of delayed follow-ups and missed business opportunities.

### Business Goal

Create a centralized lead management workflow that automatically captures new leads, synchronizes data across business tools, and instantly notifies the sales team for faster follow-up.

### My Solution

Built a lead management automation using Airtable Forms, Zapier, Google Sheets, and Gmail.

The system automatically:
- Captures new leads through an Airtable Form
- Organizes leads in an Airtable pipeline
- Synchronizes lead information to Google Sheets for reporting and future automations
- Sends an automatic email notification to the sales manager whenever a new lead is received

**Workflow**

*(Workflow Diagram)*

### Key Features

- Airtable Form lead capture
- Centralized Airtable lead pipeline
- Automatic lead synchronization to Google Sheets
- Zapier automation connecting Airtable, Google Sheets, and Gmail
- Instant email notification for new leads
- Reporting-ready Google Sheets database

---

##  System Walkthrough

|  Airtable Lead Intake Form |  Airtable Lead Pipeline |
|---|---|
| <img width="438" height="662" alt="Screenshot 2026-08-07 144716" src="https://github.com/user-attachments/assets/01835830-431c-4ffa-9648-44917c5a5ac3" />| <img width="1163" height="327" alt="Screenshot 2026-08-07 144954" src="https://github.com/user-attachments/assets/f88b7118-5ff5-48dc-b320-577477afc975" /> |
| New leads are submitted through an Airtable Form and automatically added to the pipeline. | All submitted leads are organized in Airtable, providing a centralized view of every lead and its current stage. |

|  Google Sheets Reporting Database | ⚡ Zapier Automation Workflow |
|---|---|
| <img width="1325" height="243" alt="Screenshot 2026-08-07 150644" src="https://github.com/user-attachments/assets/9221e09d-bf9b-4570-8ebe-9f73fa0b8193" />| <img width="296" height="397" alt="Screenshot 2026-08-07 145552" src="https://github.com/user-attachments/assets/61b42b51-1106-42b0-8581-2bc494f6edeb" />|
| Lead information is automatically synchronized to Google Sheets, creating a centralized reporting database for analysis and future automations. | Zapier connects Airtable, Google Sheets, and Gmail, eliminating manual data entry and keeping lead information synchronized. |

|  New Lead Notification | |
|---|---|
| <img width="317" height="465" alt="Screenshot 2026-08-07 152745" src="https://github.com/user-attachments/assets/3536a2e4-6758-4b24-b317-8b1610074988" />| Automatically sends an email notification to the sales manager whenever a new lead is submitted, enabling faster follow-up and reducing the risk of missed opportunities. |

---

### Business Questions This System Answers

- How many new leads have been received?
- Where is each lead in the sales pipeline?
- Which leads require follow-up?
- Has the sales team been notified about every new lead?

### Business Value

- Eliminates manual lead entry across multiple platforms
- Keeps lead information synchronized automatically
- Improves visibility into the sales pipeline
- Enables faster response through instant email notifications
- Creates a scalable workflow that supports future reporting and automation

### Future Enhancements

The workflow was designed to support additional automations using Multi-Step Zap, including:

- Business-hours only email notifications
- Weekend notification scheduling
- Multi-step follow-up sequences
- Conditional notifications based on lead status

*Implementation was not completed due to Airtable and Zapier free-plan limitations.*

### Tech Stack

`Airtable` `Airtable Forms` `Zapier` `Google Sheets` `Gmail`

---
## Let's Talk

If you see a similar challenge in your business, I'd be happy to discuss ideas and possible solutions.

[![Email](https://img.shields.io/badge/📧_Email-14b8a6?style=for-the-badge)](mailto:sanchezmitch77@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michelle29/)

---
[![Back to Profile](https://img.shields.io/badge/←_Back_to_Profile-0f172a?style=for-the-badge)](https://github.com/mitchsanchez29)
[![Portfolio](https://img.shields.io/badge/Portfolio-14b8a6?style=for-the-badge)](https://michelle-systems-studio.lovable.app)
[![Reporting & Analytics](https://img.shields.io/badge/Reporting_%26_Analytics-14b8a6?style=for-the-badge)](https://github.com/mitchsanchez29/reporting-analytics)
[![Finance & Operations](https://img.shields.io/badge/Finance_%26_Operations-14b8a6?style=for-the-badge)](https://github.com/mitchsanchez29/finance-operations)
