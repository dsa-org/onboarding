[Return to README](../README.md)

# Product Team Onboarding

Welcome! Follow these steps to get connected with the Product, Sales, and Operations teams at DSA Labs.

---

## Slack (primary communication)

- Install Slack on **desktop** and **mobile** (required).
- Enable **2FA** in Slack.
- Bookmark the workspace and enable notifications.

### Join these channels

- `#development-staging-issues`
- `#development-new-issues`
- `#product-development`
- `#sales-business-development`
- `#customer-acquisition`
- `#ux-product-design`
- `#onboarding-clients`
- `#competitors`

---

## Reporting an Issue on Slack

Use the channel `#development-new-issues` and follow this format:

**Email of Account:** [Email affected]  
**Which Team or Profile:** [Team or profile affected]  
**Screen Name and Path:** [Page] > [Subpage] > [Section]  
**Motive:** [User’s intention or goal]  
**Description of Issue:** [Describe what’s happening]  
**Expected Behavior:** [Describe what should happen]  
**Date/Time:** [mm/dd/yyyy hh:mm AM/PM time zone]

📎 [See an example here](./docs/ops/SlackReportingFormat.md)

---

## Product Documentation Templates (PRD / Intake / Build-No-Build)

Use these templates **before** creating new Jira epics/features so we stay consistent on scope, success metrics, and tradeoffs.

### Templates (Google Drive)

📁 https://drive.google.com/drive/folders/1fqvH7R0npvqKUzYt2NAwG7vXEjG5CPLh

Includes:
- **PRD Template (Full)**
- **PRD Template (Lightweight)**
- **Product Intake Template**
- **Build / No-Build Decision Template**

### When to use what

- **Product Intake** → initial request capture (problem, user, urgency, expected outcome)
- **Build/No-Build** → quick decision gate (ROI, effort, risks, dependencies)
- **Light PRD** → small/medium features (1–2 sprints)
- **Full PRD** → major features / new modules (multi-sprint, cross-team impact)

> After approval: translate the PRD into an Epic + tickets in Jira using the ticket format below.

---

## Jira Access

Email **scott@dsa-labs.com** to request access to Jira and the Kanban board.

**Subject:** `DSA Labs Jira Access`  
**Body:**  
Please invite me to the DSA Labs Jira Project and Kanban board.  
Name:  
Role:  
Email:

---

## Creating a Jira Ticket — Format

Use the format below when creating tickets. At a minimum, include **Description**, **Location**, and **Acceptance Criteria.**

**Description:** [Brief summary of issue or feature]  
**Location of Issue:** [Path or URL]  
**Email of Account:** [If applicable]  
**Which Team or Profile:** [Team or account]  
**Screen Name and Path:** [Page hierarchy]  
**Motive:** [User’s motivation or reason]  
**Description of Issue:** [Details of what occurred]  
**Expected Behavior:** [What should happen]  
**Date/Time:** [mm/dd/yyyy hh:mm AM/PM time zone]  
**Feature:** [Feature affected]  
**User Impact:** [Describe user impact]  
**Acceptance Criteria:** [How we’ll know it’s fixed or complete]  
**Screenshots / Recordings:** [Attach any visuals]

📎 [See an example here](./docs/ops/JiraTicketReportingFormat.md)

> When creating a Jira ticket, **always select the Priority and Parent Issue.**

**Tip:**  
You can use ChatGPT to help you create Jira tickets quickly.  
Create a new project (name it “Jira Tickets”) and prompt ChatGPT:  
> “I am a Product Manager at DSA Labs. This project is dedicated to creating Jira Tickets. Use the provided Jira Ticket Template as the master guide.”  
Then describe your issue or idea — ChatGPT will help generate consistent Jira tickets.

---

## Jira Kanban Workflow

The Kanban board has six columns:
1. `READY FOR DEVELOPMENT`
2. `IN PROGRESS`
3. `ENGINEERING REVIEW`
4. `NEEDS TESTING`
5. `PENDING DEPLOYMENT`
6. `DONE`

### Flow Overview

- PM moves ticket → **READY FOR DEVELOPMENT**
- Developer moves ticket → **IN PROGRESS**
- Once complete → move to **ENGINEERING REVIEW** (senior dev review)
- After approval → move to **NEEDS TESTING**
  - PM tests on `staging.statlink.io`
  - If successful → move to **PENDING DEPLOYMENT**
- Once deployed to production → move to **DONE**

---

## Sales, Ops, and Marketing Meetings

Email **beau@dsa-labs.com** and CC **chip@dsa-labs.com** to be added to Sales, Ops, and Marketing meetings.  
We use **Google Calendar** and **Google Meet** for all sessions.

---

## Tools and Domains

| Tool / Platform | Description |
|-----------------|-------------|
| [StatLink](https://statlink.io/) | Production environment |
| [StatLink – Staging](https://staging.statlink.io/login/) | Testing/staging environment |
| [Jira](https://dsalabs.atlassian.net/jira/your-work/) | Project management & issue tracking |
| [Pipedrive](https://www.pipedrive.com/) | CRM for leads, deals, and pipeline |
| [Google Analytics](https://analytics.google.com/) | Website and platform analytics |
| [DSA Labs](https://www.dsa-labs.com/) | Company website |
| [StatLink Admin Panel](https://api.statlink.io/administration/dashboard) | Admin tools: manage teams, players, and subscriptions |
| [Canva](https://www.canva.com/) | Preferred design tool for sales, marketing, and social media graphics |

---

## DSA Labs Sales Guide

Reference the [StatLink & ImpactCap Sales Package (PDF)](./StatLinkandImpactCapSalesPackage.pdf) regularly for standardized outreach, pitch, demo, and benchmarking.

Reference the [Sales & Customer Success Manual (PDF)](./SalesCustomerSuccessManual.pdf) regularly for scripts, pitches, and workflows.

---

_Last updated: April 23, 2026_  
_Maintained by: Scott Krotee (Head of Product, DSA Labs)_
