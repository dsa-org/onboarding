[Return to README](../README.md)

# Developer Onboarding

Welcome! Follow these steps in order. If anything is unclear, ask in `#development-discussion`.

---

## Slack (primary communications)
- Install Slack on **desktop** and **mobile** (required).
- Enable **2FA** in Slack (required).
- Join these channels:
  - `#development-discussion` — general dev chat / questions
  - `#development-staging-issues` — staging deploys & verifications
  - `#development-new-issues` — bug reports / regressions
  - `#product-development` — roadmaps & priorities

---

## Jira access
Email **scott@dsa-labs.com** and CC **bobby@dsa-labs.com** to request Jira + Kanban access.

**Subject:** `DSA Labs Jira Access`  
**Body:**
Please invite me to the DSA Labs Jira project and Kanban board.  
Name:  
Role:  
Preferred email:  

---

## Standup meetings
Email **scott@dsa-labs.com** to be added to **M/W/F 12:00 PM ET** standups (Google Calendar + Meet).

**Subject:** `Add me to Dev Standups (M/W/F 12PM ET)`  
**Body:**  
Please add me to the M/W/F 12PM ET dev standups.  
Name:  
Email (for invite):  
Time zone:  

---

## Required tools
- [VS Code](https://code.visualstudio.com/) — primary IDE  
- [Git](https://git-scm.com/) / [GitHub Desktop](https://desktop.github.com/download/) — version control  
- [Python](https://www.python.org/downloads/) (3.11+) — backend tooling & scripts  
- [DB Browser for SQLite](https://sqlitebrowser.org/) — local DB inspection  
- [pgAdmin](https://www.pgadmin.org/) — staging/prod Postgres access  
- [Docker](https://www.docker.com/) — local services; Django + websockets  
- [Microsoft Visual Studio C++ Build Tools](https://visualstudio.microsoft.com/downloads/?q=build+tools) — native deps on Windows

> Enable **2FA** on **GitHub** and **Google** before requesting repo access.

---

## Design reference
UI rehaul in progress (under construction). Ask Product for current mocks and component guidance.

---

## Tutorials (skim if new to stack)
- [Getting started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)  
- [How to set up a Django application](https://docs.djangoproject.com/en/4.2/intro/tutorial01/)  
- [Using DB Browser for SQLite](https://datacarpentry.org/sql-socialsci/02-db-browser.html)

---

## GitHub access request
After completing the steps above, email **bobby@dsa-labs.com** (CC **scott@dsa-labs.com**):

**Subject:** `StatLink GitHub Access`  
**Body:**  
Please invite me to the GitHub org and repos:  
- dsa (backend)  
- dsa-frontend (frontend)  

GitHub username:  
Email used for GitHub:  

---

## Repos & first steps

### `dsa` (backend)
- Open `/docs/README.md` in the repo and follow environment setup.  
- Ask in `#development-discussion` for the `.env` template. **Never commit secrets.**

### `dsa-frontend`
- Work in progress. Ask in `#development-discussion` for current setup and tasks.

---

## Conventions (must read)
- **Secrets:** Use `.env` files or approved secrets managers. **Do not** commit secrets.  
- **Branches:** `feature/<short-name>`, `bugfix/<short-name>`, `hotfix/<short-name>`  
- **Commits:** Conventional style (`feat: …`, `fix: …`, `chore: …`) + include JIRA ticket (e.g., `feat: add player filter [DL-123]`)  
- **PRs:** Small, focused; include description, screenshots for UI, testing notes, and linked JIRA ticket  
- **Reviews:** ≥1 reviewer; verify on **staging** before merge to `main`

---

## Need help?
Post in `#development-discussion` or email **scott@dsa-labs.com**.

---

_Last updated: April 23, 2026_  
_Maintained by: Scott Krotee (Head of Product, DSA Labs)_