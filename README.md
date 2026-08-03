# TalentBridge HR Recruitment Automation

An end-to-end recruitment workflow built using **Google Forms, Google Sheets, Gmail, Trello, and Zapier** to automate the candidate application and hiring process.

---

## Project Overview

TalentBridge HR Recruitment Automation streamlines the recruitment lifecycle by eliminating repetitive manual tasks. Candidates submit applications through a Google Form, receive an automated confirmation email, and are automatically added to a Trello recruitment pipeline where HR can manage each stage of the hiring process.

This project demonstrates practical business process automation using no-code tools commonly adopted by HR teams, recruitment agencies, and small businesses.

---

## Business Scenario

TalentBridge HR Solutions receives dozens of applications daily for multiple positions.

Previously, recruiters had to:

- Manually review application emails
- Copy candidate details into spreadsheets
- Send confirmation emails individually
- Create Trello cards manually
- Track candidates through the recruitment pipeline

This solution automates the entire intake process, reducing administrative effort while improving consistency and candidate experience.

---

## Objectives

- Automate candidate application intake
- Eliminate manual data entry
- Provide instant confirmation emails
- Automatically organize applicants in Trello
- Improve recruitment workflow visibility
- Standardize candidate tracking

---

# Technology Stack

| Tool | Purpose |
|-------|----------|
| Google Forms | Candidate application form |
| Google Sheets | Response database |
| Gmail | Automated email confirmations |
| Trello | Recruitment pipeline |
| Zapier | Workflow automation |

---

# Recruitment Workflow

```text
Candidate
      │
      ▼
Google Form
      │
      ▼
Google Sheets
      │
      ├────────────► Gmail
      │                 │
      │                 ▼
      │       Confirmation Email
      │
      ▼
Zapier
      │
      ▼
Trello
(New Applications)
```

---

# Automation Overview

### Application Intake Automation

**Trigger**

- Candidate submits Google Form

**Actions**

- Save application in Google Sheets
- Send confirmation email
- Create Trello recruitment card

---

### Phone Screening Automation

**Trigger**

Candidate moved to **Phone Screening**

**Actions**

- Create Google Calendar interview
- Add "Phone Screen Scheduled" label
- Move candidate to Interview Scheduled

---

### Interview Tracking Automation

**Trigger**

Candidate moved to **Interviewed**

**Actions**

- Update Google Sheets
- Add interview notes to Trello

---

### Offer Management Automation

**Trigger**

Candidate moved to **Offer Sent**

**Actions**

- Apply Offer Sent label
- Send offer email automatically

---

### Employee Onboarding Automation

**Trigger**

Candidate moved to **Hired**

**Actions**

- Add onboarding checklist
- Apply Hired label
- Move card to Hired list

---

# Features

- End-to-end recruitment automation
- Automated email confirmations
- Applicant Tracking System (ATS)
- Interview scheduling
- Candidate pipeline management
- Automated status updates
- No-code workflow implementation
- Scalable recruitment process

---

# Repository Structure

```
talentbridge-hr-recruitment-automation
│
├── README.md
├── documentation
│
├── screenshots
│
└── assets
```

---

# Documentation

Detailed implementation guides are available in the **documentation** folder.

These guides explain:

- Business requirements
- Solution design
- Google Form configuration
- Zapier workflows
- Trello configuration
- Gmail automation
- Testing
- Lessons learned

---

# Screenshots

Project screenshots demonstrating each implementation step are available in the **screenshots** folder.

---

# Skills Demonstrated

- Business Process Automation
- Workflow Design
- Zapier Automation
- Trello Administration
- Google Workspace
- Process Improvement
- HR Operations
- Recruitment Operations
- Documentation
- Systems Implementation

---

# Outcome

This solution demonstrates how modern no-code automation tools can transform a manual recruitment process into an efficient, scalable workflow that improves both recruiter productivity and candidate experience.

---

## Author

**Chika Blessing**

Business Operations | Workflow Automation | Project Management | CRM
