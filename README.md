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

## Coordinator Workflow Automation

**Type:** WORK PROJECT

**Business Problem:** A client-facing coordination process ran through 10 separate manual stages, with no structured way to track where each record was in the process.

**Business Goal:** Replace stage-by-stage manual tracking with one structured system that moves records through each stage automatically.

**My Solution:** A 10-stage coordinator workflow built in Google Sheets and Apps Script, with a dashboard layer on top to show where every record sits in the pipeline.

**Workflow**

*Future Workflow Diagram*

**Key Features:**
- 10-stage pipeline structure matching the client's actual process
- Automated stage tracking in Google Sheets
- Dashboard view for at-a-glance pipeline status
- Apps Script logic to move records through the pipeline

**Screenshots**
<img width="401" height="531" alt="Screenshot 2026-08-07 112835" src="https://github.com/user-attachments/assets/3d06b76c-d585-41d2-acdc-55eabae10451" />
<img width="987" height="560" alt="Screenshot 2026-08-07 121832" src="https://github.com/user-attachments/assets/691789f0-2b40-48d5-9ef4-6ec465d92d3c" />
<img width="698" height="562" alt="Screenshot 2026-08-07 121512" src="https://github.com/user-attachments/assets/d27e2214-6d1f-4ca2-b840-d2e2871ec59e" />
<img width="1418" height="156" alt="Screenshot 2026-08-07 121407" src="https://github.com/user-attachments/assets/88ab6e0d-1906-4b79-b36b-52294c38508a" />

*Form - Leads save to sheets- auto create Folder of Leads - Master Tracker - Coordinator Workspace*

**Business Questions Answered:**
- Where is each record in the 10-stage process right now?
- Which stage is creating the biggest bottleneck?

**Business Value:** Replaces a manual, stage-by-stage process with a structured system that's easy to track at a glance.

**Honest note:** This system was fully built and delivered under a real contract. The handoff was never completed — the client wasn't given system access before communication stopped, so it was never put into use or paid out. Shown here as real, contracted work rather than a system currently in active client use.

**Tech Stack:** `Google Sheets` `Google Apps Script` `Workflow Automation` `Dashboard`

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

| **Lead Tracker (Sheets)** | **Dashboard Summary** |
|---|---|
| <img width="600" alt="Lead Tracker" src="https://github.com/user-attachments/assets/f4f73371-54c9-4d2f-841e-1372d42445fc" /> | <img width="600" alt="Dashboard Summary" src="https://github.com/user-attachments/assets/d1705835-5754-47bb-9624-3eac80989d28" /> |

**Auto-generated Response & Google Drive Storage**

<img width="800" alt="Auto-generated Response and Drive Storage" src="https://github.com/user-attachments/assets/1ec987a5-3cb4-41c0-9b54-4807398515c7" />

**Business Questions Answered:**
- Which quotes have gone out, and what's their status?
- How many quotes are pending vs. sent this month?

**Business Value:** Fewer manual steps from quote to delivery, faster turnaround for clients, and one clean tracking system instead of scattered files.

**Tech Stack:** `Google Forms` `Apps Script` `Google Sheets` `Google Docs` `Drive` `Gmail` `PDF`

---

## Lead Management Automation

**Type:** CASE STUDY

**Business Problem:** Lead data lived in a flat spreadsheet with no structured pipeline — no clear way to see which stage each lead was at.

**Business Goal:** Give leads a clear, visual pipeline from first contact to close.

**My Solution:** A lead management system built around a five-stage Airtable pipeline: **Airtable Forms → Zapier → Google Sheets → Gmail.** New leads come in through an Airtable Form, Zapier pushes the data into Google Sheets, and Gmail handles follow-up notifications.

**Workflow**

*Future Workflow Diagram*

**Key Features:**
- Five-stage lead pipeline in Airtable
- Airtable Forms for lead intake
- Zapier automation moving data into Google Sheets
- Gmail-based follow-up notifications
*(automations partially limited by Airtable's free-plan restrictions)*

**Screenshots**

*Screenshot Coming Soon*

**Business Questions Answered:**
- Which stage is each lead currently sitting in?
- How many leads are stuck at a given stage?

**Business Value:** A visual, structured pipeline instead of a flat spreadsheet — easier to see where leads are getting stuck.

**Tech Stack:** `Airtable` `Airtable Forms` `Zapier` `Google Sheets` `Gmail`

---

## ChatGPT Email Automation

**Type:** CASE STUDY *(planned — not yet built)*

**Business Problem:** Drafting context-aware client emails by hand takes time, especially at volume.

**Planned Solution:** Integrate the ChatGPT API with Google Apps Script to generate context-aware email drafts automatically — the script would read data from Sheets, build a prompt, call the OpenAI API, and create a Gmail draft for human review before sending.

**Status:** Still learning this one — it needs a paid OpenAI API key that hasn't been set up yet, so this hasn't actually been built.

**Screenshots**

*Screenshot Coming Soon*

**Tech Stack (Planned):** `ChatGPT API` `Google Apps Script` `Gmail` `OpenAI API`

---

[⬅ Back to Profile](https://github.com/mitchsanchez29) · [📊 Reporting & Analytics](../reporting-analytics) · [💰 Finance & Operations](../finance-operations)
