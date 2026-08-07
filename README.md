# 🔁 Business Automation

Systems that remove repetitive manual work — quote generation, lead pipelines, notifications, and workflow tracking.

[⬅ Back to Profile](https://github.com/mitchsanchez29) · [📊 Reporting & Analytics](https://github.com/mitchsanchez29/reporting-analytics) · [💰 Finance & Operations](https://github.com/mitchsanchez29/finance-operations)

---

## What's In This Repository

| Project | Type |
|---|---|
| Coordinator Workflow Automation | WORK PROJECT |
| Slack Notification Automation | WORK PROJECT |
| Automated Quotation & CRM | CASE STUDY |
| Lead Management Automation | CASE STUDY |
| ChatGPT Email Automation | CASE STUDY (planned) |

---

## Lead Operations Management System

**Type:** Work Project

### Business Problem

The client managed leads through a 10-stage coordination process using multiple spreadsheets and manual updates. Tracking progress, assigning tasks, and ensuring every required step was completed became time-consuming and difficult to monitor.

### Business Goal

Create a centralized workflow that standardizes the coordination process, improves visibility, and keeps every lead moving through each stage consistently.

### My Solution

Built a Google Sheets and Apps Script workflow automation that manages the entire coordination process from lead approval to completion.

The system automatically:
- Creates a unique Sponsor ID for approved leads
- Generates a dedicated Google Drive folder for each lead
- Stores all records in a centralized Master Tracker
- Loads lead information into the Coordinator Workspace
- Guides coordinators through a standardized 10-stage checklist
- Updates the Master Tracker automatically as each stage is completed
- Provides a live dashboard showing the status of every lead in the pipeline

**Workflow**

<img width="1283" height="680" alt="Screenshot 2026-08-07 144146" src="https://github.com/user-attachments/assets/9549f823-c8cd-4130-94a5-d78b027d2fc6" />

### Key Features

- Google Form lead intake
- Duplicate lead validation
- Coordinator approval (Approve / Reject / Cancel)
- Automatic Sponsor ID generation
- Automatic Google Drive folder creation
- Centralized Master Tracker
- Coordinator Workspace with auto-populated lead details
- 10-stage checklist with automated stage progression
- Real-time dashboard for operational visibility


**Screenshots**
| 📁 Auto Drive Folder | 📊 Master Tracker |
|---|---|
| <img width="401" height="531" alt="Screenshot 2026-08-07 112835" src="https://github.com/user-attachments/assets/3d06b76c-d585-41d2-acdc-55eabae10451" /> | <img width="1418" height="156" alt="Screenshot 2026-08-07 121407" src="https://github.com/user-attachments/assets/88ab6e0d-1906-4b79-b36b-52294c38508a" />
| Automatically creates a Drive folder for every approved lead. | Central source of truth for lead data, Sponsor ID, and workflow status. |

| 👩‍💼 Coordinator Workspace | ✅ Stage Checklist |
|---|---|
| <img width="698" height="562" alt="Screenshot 2026-08-07 121512" src="https://github.com/user-attachments/assets/d27e2214-6d1f-4ca2-b840-d2e2871ec59e" /> | <img width="566" height="525" alt="Screenshot 2026-08-07 140733" src="https://github.com/user-attachments/assets/bca5b3fb-bec3-4d23-830c-7099dbe1da36" /> |
| Coordinators manage and update leads from one workspace. | Checklist ensures each stage is completed before moving to the next. |

| 📈 Dashboard Summary | |
|---|---|
| <img width="987" height="560" alt="Screenshot 2026-08-07 121832" src="https://github.com/user-attachments/assets/691789f0-2b40-48d5-9ef4-6ec465d92d3c" />| Displays real-time workflow progress and operational metrics. |


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

---

## Slack Notification Automation

**Type:** WORK PROJECT

**Business Problem:** Status updates (form submissions, sheet edits) required someone to manually message the team.

**Business Goal:** Get the team real-time updates without anyone having to type a message.

**My Solution:** Apps Script listens for trigger events and sends real-time notifications to a Slack channel via Incoming Webhooks, eliminating manual status update messages.

**Workflow**

<img width="697" height="267" alt="Screenshot 2026-06-05 181556" src="https://github.com/user-attachments/assets/2dcf9943-c06b-4aba-80a0-c86fdc0be2cb" />

**Key Features:**
- Listens for form submissions and sheet edits
- Sends real-time Slack notifications via Incoming Webhooks
- No manual messaging required

**Screenshots**

*Screenshot Coming Soon*

**Business Questions Answered:**
- Has this trigger event already been flagged to the team?

**Business Value:** Faster team visibility into updates, with zero manual messaging required.

**Tech Stack:** `Google Apps Script` `UrlFetchApp` `Slack Incoming Webhooks` `REST API` `JSON`

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
## 📸 System Walkthrough

| 📝 Quotation Request Form | 📊 Lead Tracker |
|---|---|
| <img width="317" height="693" alt="Screenshot 2026-08-07 154604" src="https://github.com/user-attachments/assets/643757d2-e905-43df-8bb9-dd594b6ebde4" />
 | <img width="600" alt="Lead Tracker" src="https://github.com/user-attachments/assets/f4f73371-54c9-4d2f-841e-1372d42445fc" /> |
| Clients submit quotation requests through a Google Form, automatically triggering the quotation workflow. | Centralized tracker that records every quotation, generates a unique quotation number, and monitors the status of each request. |

| 📈 Dashboard Summary | 📁 Automated Quote Delivery & Storage |
|---|---|
| <img width="600" alt="Dashboard Summary" src="https://github.com/user-attachments/assets/d1705835-5754-47bb-9624-3eac80989d28" /> | <img width="800" alt="Auto-generated Response and Drive Storage" src="https://github.com/user-attachments/assets/1ec987a5-3cb4-41c0-9b54-4807398515c7" /> |
| Provides a real-time overview of quotation activity, status, and overall workflow performance. | Automatically generates the quotation, converts it to PDF, stores it in Google Drive, and emails it to the client without manual intervention. |

**Business Questions Answered:**
- Which quotes have gone out, and what's their status?
- How many quotes are pending vs. sent this month?

**Business Value:** Fewer manual steps from quote to delivery, faster turnaround for clients, and one clean tracking system instead of scattered files.

**Tech Stack:** `Google Forms` `Apps Script` `Google Sheets` `Google Docs` `Drive` `Gmail` `PDF`

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

## 📸 System Walkthrough

| 📝 Airtable Lead Intake Form | 📋 Airtable Lead Pipeline |
|---|---|
| <img width="438" height="662" alt="Screenshot 2026-08-07 144716" src="https://github.com/user-attachments/assets/01835830-431c-4ffa-9648-44917c5a5ac3" />
 | <img width="1163" height="327" alt="Screenshot 2026-08-07 144954" src="https://github.com/user-attachments/assets/f88b7118-5ff5-48dc-b320-577477afc975" /> |
| New leads are submitted through an Airtable Form and automatically added to the pipeline. | All submitted leads are organized in Airtable, providing a centralized view of every lead and its current stage. |

| 📊 Google Sheets Reporting Database | ⚡ Zapier Automation Workflow |
|---|---|
| <img width="1325" height="243" alt="Screenshot 2026-08-07 150644" src="https://github.com/user-attachments/assets/9221e09d-bf9b-4570-8ebe-9f73fa0b8193" />
 | <img width="296" height="397" alt="Screenshot 2026-08-07 145552" src="https://github.com/user-attachments/assets/61b42b51-1106-42b0-8581-2bc494f6edeb" />
 |
| Lead information is automatically synchronized to Google Sheets, creating a centralized reporting database for analysis and future automations. | Zapier connects Airtable, Google Sheets, and Gmail, eliminating manual data entry and keeping lead information synchronized. |

| 📧 New Lead Notification | |
|---|---|
| <img width="317" height="465" alt="Screenshot 2026-08-07 152745" src="https://github.com/user-attachments/assets/3536a2e4-6758-4b24-b317-8b1610074988" />
 | Automatically sends an email notification to the sales manager whenever a new lead is submitted, enabling faster follow-up and reducing the risk of missed opportunities. |

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

[⬅ Back to Profile](https://github.com/mitchsanchez29) · [📊 Reporting & Analytics](../reporting-analytics) · [💰 Finance & Operations](../finance-operations)
