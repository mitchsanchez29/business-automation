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

<svg viewBox="0 0 1400 620" xmlns="http://www.w3.org/2000/svg" font-family="Arial, Helvetica, sans-serif">
  <defs>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="8" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#5b7cad"/>
    </marker>
  </defs>

  <rect width="1400" height="620" fill="#ffffff"/>

  <!-- Title -->
  <text x="700" y="42" text-anchor="middle" font-size="24" font-weight="bold" fill="#1c2b4a">Sponsor Workspace — Automated Intake &amp; Pipeline System</text>
  <text x="700" y="66" text-anchor="middle" font-size="13" fill="#6b7688">Google Forms → Sheets → Apps Script, end to end</text>

  <!-- Row 1: Intake -->
  <g>
    <rect x="40" y="110" width="200" height="90" rx="14" fill="#eaf1fb" stroke="#4a86e8" stroke-width="1.5"/>
    <text x="140" y="145" text-anchor="middle" font-size="14" font-weight="bold" fill="#1c4587">📋 Google Form</text>
    <text x="140" y="165" text-anchor="middle" font-size="11" fill="#3c5a8a">Sponsor submits inquiry</text>
    <text x="140" y="182" text-anchor="middle" font-size="11" fill="#3c5a8a">Name · Email · Phone · Source</text>
  </g>

  <line x1="240" y1="155" x2="290" y2="155" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>

  <g>
    <rect x="292" y="110" width="220" height="90" rx="14" fill="#fdf3e3" stroke="#f1c232" stroke-width="1.5"/>
    <text x="402" y="138" text-anchor="middle" font-size="14" font-weight="bold" fill="#8a6d1a">🔍 New Leads Queue</text>
    <text x="402" y="158" text-anchor="middle" font-size="11" fill="#8a6d1a">Auto duplicate check</text>
    <text x="402" y="175" text-anchor="middle" font-size="11" fill="#8a6d1a">(matches existing email/phone)</text>
    <text x="402" y="192" text-anchor="middle" font-size="11" fill="#8a6d1a">Lead ID auto-assigned</text>
  </g>

  <line x1="512" y1="155" x2="562" y2="155" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>

  <g>
    <rect x="564" y="110" width="230" height="90" rx="14" fill="#eef7ec" stroke="#38761d" stroke-width="1.5"/>
    <text x="679" y="135" text-anchor="middle" font-size="14" font-weight="bold" fill="#38761d">🧑‍💼 Coordinator Review</text>
    <text x="679" y="156" text-anchor="middle" font-size="11" fill="#3c6b2e">Approve · Reject · Undo</text>
    <text x="679" y="173" text-anchor="middle" font-size="11" fill="#3c6b2e">One click, with confirmation</text>
    <text x="679" y="190" text-anchor="middle" font-size="11" fill="#3c6b2e">prompt before any action</text>
  </g>

  <!-- down arrow to Master Tracker -->
  <line x1="679" y1="200" x2="679" y2="255" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>

  <!-- Row 2: Master Tracker + Drive -->
  <g>
    <rect x="480" y="257" width="400" height="100" rx="14" fill="#eaf1fb" stroke="#1c4587" stroke-width="1.5"/>
    <text x="680" y="285" text-anchor="middle" font-size="15" font-weight="bold" fill="#1c4587">🧾 Master Tracker</text>
    <text x="680" y="306" text-anchor="middle" font-size="11" fill="#3c5a8a">Auto-generated Sponsor ID · System of record</text>
    <text x="680" y="323" text-anchor="middle" font-size="11" fill="#3c5a8a">Stage · Status · Coordinator · Next steps</text>
    <text x="680" y="340" text-anchor="middle" font-size="11" fill="#3c5a8a">Color-coded by pipeline stage</text>
  </g>

  <!-- branch to Drive folder -->
  <line x1="880" y1="307" x2="960" y2="307" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>
  <g>
    <rect x="962" y="262" width="200" height="90" rx="14" fill="#fdf3e3" stroke="#f1c232" stroke-width="1.5"/>
    <text x="1062" y="292" text-anchor="middle" font-size="14" font-weight="bold" fill="#8a6d1a">📁 Drive Folder</text>
    <text x="1062" y="312" text-anchor="middle" font-size="11" fill="#8a6d1a">Auto-created per Sponsor</text>
    <text x="1062" y="329" text-anchor="middle" font-size="11" fill="#8a6d1a">Named &amp; organized automatically</text>
  </g>

  <!-- down arrow to Sponsor Workspace -->
  <line x1="680" y1="357" x2="680" y2="412" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>

  <!-- Row 3: Sponsor Workspace -->
  <g>
    <rect x="420" y="414" width="520" height="110" rx="14" fill="#eef7ec" stroke="#38761d" stroke-width="1.5"/>
    <text x="680" y="440" text-anchor="middle" font-size="15" font-weight="bold" fill="#38761d">🗂 Sponsor Workspace (Coordinator's daily view)</text>
    <text x="680" y="462" text-anchor="middle" font-size="11" fill="#3c6b2e">Auto-pulls contact info, stage, and notes from Master Tracker</text>
    <text x="680" y="479" text-anchor="middle" font-size="11" fill="#3c6b2e">Stage-specific checklist appears automatically</text>
    <text x="680" y="496" text-anchor="middle" font-size="11" fill="#3c6b2e">Check off tasks → click Advance Stage → next stage's checklist loads</text>
    <text x="680" y="513" text-anchor="middle" font-size="11" fill="#3c6b2e">Master Tracker updates in the same click — fully in sync</text>
  </g>

  <!-- loop arrow back to Master Tracker -->
  <path d="M 940 470 C 1050 470, 1050 300, 885 300" fill="none" stroke="#9aa7bd" stroke-width="1.8" stroke-dasharray="5,4" marker-end="url(#arrow)"/>
  <text x="1010" y="392" font-size="10" fill="#8a94a6">syncs back automatically</text>

  <!-- down arrow to dashboard -->
  <line x1="680" y1="524" x2="680" y2="558" stroke="#5b7cad" stroke-width="2" marker-end="url(#arrow)"/>

  <g>
    <rect x="500" y="560" width="360" height="50" rx="12" fill="#1c4587"/>
    <text x="680" y="591" text-anchor="middle" font-size="13" font-weight="bold" fill="#ffffff">📊 Executive Dashboard — updates live, no manual work</text>
  </g>
</svg>

**Key Features:**
- 10-stage pipeline structure matching the client's actual process
- Automated stage tracking in Google Sheets
- Dashboard view for at-a-glance pipeline status
- Apps Script logic to move records through the pipeline

**Screenshots**
Form - Leads save to sheets- 

image is 
auto create Folder of Leads
<img width="401" height="531" alt="Screenshot 2026-08-07 112835" src="https://github.com/user-attachments/assets/3d06b76c-d585-41d2-acdc-55eabae10451" />

Master Tracker
<img width="1418" height="156" alt="Screenshot 2026-08-07 121407" src="https://github.com/user-attachments/assets/88ab6e0d-1906-4b79-b36b-52294c38508a" />

Coordinator Workspace
<img width="987" height="560" alt="Screenshot 2026-08-07 121832" src="https://github.com/user-attachments/assets/691789f0-2b40-48d5-9ef4-6ec465d92d3c" />

Dashboard Summary
<img width="698" height="562" alt="Screenshot 2026-08-07 121512" src="https://github.com/user-attachments/assets/d27e2214-6d1f-4ca2-b840-d2e2871ec59e" />
stage summary
<img width="566" height="525" alt="Screenshot 2026-08-07 140733" src="https://github.com/user-attachments/assets/bca5b3fb-bec3-4d23-830c-7099dbe1da36" />

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
