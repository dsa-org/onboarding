[Return to README](../README.md)

# Developer Onboarding

Welcome! This guide will get you set up and contributing to DSA Labs as quickly as possible.

If anything is unclear, ask in `#development-discussion`.

---

## 🎯 Your Focus (Developer)

As a developer at DSA Labs, your role is to:

- Build and improve StatLink and ImpactCap features
- Resolve bugs and maintain system reliability
- Collaborate with Product on scoped tickets
- Ship clean, tested code to staging and production

---

## Slack (Primary Communication)

- Install Slack on **desktop** and **mobile** (required)
- Enable **2FA**
- Join these channels:

- `#development-discussion` — questions, blockers, coordination  
- `#development-staging-issues` — deploys & verification  
- `#development-new-issues` — bugs & regressions  
- `#product-development` — roadmap & priorities  

---

## Jira Access

Email **scott@dsa-labs.com** and CC **bobby@dsa-labs.com** to request access.

**Subject:** `DSA Labs Jira Access`  
**Body:**  
Please invite me to the DSA Labs Jira project and Kanban board.  
Name:  
Role:  
Preferred email:  

---

## Standup Meetings

Email **scott@dsa-labs.com** to be added to:

- **M/W/F 12:00 PM ET** (Google Calendar + Meet)

**Subject:** `Add me to Dev Standups (M/W/F 12PM ET)`  
**Body:**  
Please add me to dev standups.  
Name:  
Email:  
Time zone:  

---

## Required Tools

- [VS Code](https://code.visualstudio.com/) — primary IDE  
- [Git](https://git-scm.com/) / [GitHub Desktop](https://desktop.github.com/download/) — version control  
- [Python](https://www.python.org/downloads/) (3.11+) — backend  
- [DB Browser for SQLite](https://sqlitebrowser.org/) — local DB  
- [pgAdmin](https://www.pgadmin.org/) — staging/prod DB  
- [Docker](https://www.docker.com/) — local services  
- [MS C++ Build Tools](https://visualstudio.microsoft.com/downloads/?q=build+tools) — Windows dependencies  

> Enable **2FA** on GitHub and Google before requesting access.

---

## GitHub Access

After completing setup, email **bobby@dsa-labs.com** (CC **scott@dsa-labs.com**):

**Subject:** `StatLink GitHub Access`  

**Body:**  
Please invite me to the GitHub org and repos:  
- dsa (backend)  
- dsa-frontend (frontend)  

GitHub username:  
Email:  

---

## Repos & First Steps

### `dsa` (backend)

- Open `/docs/README.md` and complete environment setup  
- Request `.env` template in Slack (**never commit secrets**)  
- Confirm you can:
  - Run the backend locally  
  - Hit core endpoints  

---

### `dsa-frontend`

- Work in progress  
- Ask in `#development-discussion` for:
  - Setup steps  
  - Current priorities  

---

## 🚀 First Task (Do This Early)

Before taking on large work:

- Pick a **small Jira ticket**
- Run through:
  - Branch → commit → PR → review → staging
- Confirm you can:
  - Push code  
  - Open a PR  
  - See changes in staging  

👉 This validates your full workflow end-to-end.

---

## Conventions (Must Follow)

- **Secrets:** Use `.env` or approved managers. Never commit secrets  
- **Branches:** `feature/<short-name>`, `bugfix/<short-name>`, `hotfix/<short-name>`  
- **Commits:**  
  - Use conventional style (`feat:`, `fix:`, `chore:`)  
  - **Include JIRA ticket ID**  
  - Example: `fix: resolve ranking bug [DL-123]`  

- **PRs:**  
  - Small and focused  
  - Include:
    - Description  
    - Screenshots (if UI)  
    - Testing notes  
    - Linked JIRA ticket  

- **Reviews:**  
  - ≥1 reviewer required  
  - Must verify on **staging** before merge  

---

## Design + Product Alignment

UI is evolving. Before building:

- Confirm designs with Product
- Align on expected behavior
- Avoid building based on assumptions

---

## Tutorials (Optional)

- [Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)  
- [Django Tutorial](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)  
- [SQLite Browser Guide](https://datacarpentry.org/sql-socialsci/02-db-browser.html)

---

## Need Help?

- Post in `#development-discussion`
- Or email **scott@dsa-labs.com**

---

_Last updated: April 23, 2026_  
_Maintained by: Scott Krotee (Head of Product, DSA Labs)_