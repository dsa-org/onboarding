# 🧱 DSA Labs – Offboarding Guide

**Purpose:**  
This document outlines the standard offboarding process for DSA Labs contributors across products (StatLink, ImpactCap, Walter Camp, etc.).  
It ensures security, smooth handoff, and proper documentation of all transitions.

---

## 1. Communication & Transition

- [ ] Confirm final working day.  
- [ ] Announce departure in `#dsa-labs` and `#general`.  
- [ ] Schedule 15–20 minute handoff call.  
- [ ] Collect scripts, notebooks, or documents into.  
- [ ] Record key workflows or dependencies.  
- [ ] Export any API keys, credentials, or environment details for transition.

---

## 2. Code & Data Access

### GitHub
- [ ] Reassign open PRs or issues.  
- [ ] Remove from private repos and org access.  
- [ ] Preserve commit history and documentation.  

### AWS / S3
- [ ] Remove IAM credentials.  
- [ ] Archive any owned data folders.

### Databases
- [ ] Disable access credentials (Postgres, Render, Supabase).  
- [ ] Transfer table or schema ownership.  

### Analytics Scripts
- [ ] Collect `.py`, `.ipynb`, `.csv` files. 
- [ ] Note dependencies.

---

## 3. Platform Permissions

### Slack
- [ ] Announce departure and express thanks.  
- [ ] Convert to *Guest* (for short-term collaboration) or deactivate.  

### Email (Google Workspace)
- [ ] Set auto-reply:  
  “This account is no longer active. For support, contact support@dsa-labs.com”  
- [ ] Forward to relevant team inbox for 30 days, then disable.  

### Internal Platforms
- [ ] Remove from StatLink, ImpactCap, etc. admin dashboards.  
- [ ] Reassign managed teams, API keys, and analytics uploads.  

### Partner / Client Access
- [ ] Revoke API tokens for external.  
- [ ] Update credentials registry if applicable.

---

## 4. Admin & Documentation

- [ ] Update team roster and internal org chart.
- [ ] Update website /resources/team.
- [ ] Remove from recurring meetings (stand-ups, sprint reviews, QA, etc.).  
- [ ] Archive Slack threads or project notes related to ongoing tasks.  
- [ ] Store all handoff materials.  
- [ ] Send thank-you and farewell message to team.  

---

## 5. Optional: Alumni / Retainer Access

If the person will stay on in a consulting or hobbyist capacity:
- [ ] Add to `#alumni` Slack channel.  
- [ ] Keep read-only GitHub access if needed.  
- [ ] Add to monthly product updates or internal newsletter.

---

## ✅ Final Confirmation

When all steps are complete:
- [ ] Confirm offboarding with @scott and @chip.  
- [ ] Update `/docs/TEAM_TRACKER.md`.  
- [ ] Mark account as fully deactivated.

---

_Last updated: October 2025_  
_Contact: Scott Krotee – Head of Product, DSA Labs_
