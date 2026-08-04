# Zapier Workflow

## Objective

Zapier serves as the automation engine connecting the recruitment tools used in the TalentBridge HR Recruitment Automation project.

It coordinates data transfer between Google Forms, Google Sheets, Gmail, Trello, and Google Calendar without requiring manual intervention.

---

## Core Application Intake Workflow

### Trigger

A candidate submits the TalentBridge HR Job Application Form.

### Actions

1. Retrieve the submitted candidate information.
2. Send a personalized confirmation email through Gmail.
3. Create a Trello card in the New Applications list.
4. Update the Trello card with structured candidate details.

---

## Candidate Data Mapped

The workflow uses dynamic fields from the Google Form, including:

- Full Name
- Email Address
- Phone Number
- Position Applied For
- Years of Experience
- Preferred Work Arrangement
- Available Start Date
- Resume Link
- Candidate Summary

---

## Trello Card Configuration

Each new Trello card contains:

- Candidate name and position in the card title
- Email address
- Phone number
- Experience level
- Work arrangement
- Available start date
- Resume link
- Candidate statement

This creates a centralized candidate record for the recruitment team.

---

## Additional Automations

The project also includes separate Zaps for:

- Phone screening scheduling
- Interview tracking
- Offer management
- Employee onboarding

These workflows use Trello list movements as triggers for the next recruitment action.

---

## Business Benefits

- Eliminates repetitive data entry
- Connects multiple business applications
- Standardizes recruitment processing
- Reduces administrative delays
- Improves workflow visibility
- Supports scalable hiring operations

---

## Outcome

A complete candidate application can move from Google Forms into Gmail and Trello automatically, giving recruiters an organized record without manually copying information.

---

## Related Screenshots

### Successful Application Intake Workflow

![Application Intake Workflow](https://raw.githubusercontent.com/cbmaduka/talentbridge-hr-recruitment-automation/main/screenshots/07-zap-tested-successfully.png)

### Trello Card Creation Configuration

![Trello Card Creation](https://raw.githubusercontent.com/cbmaduka/talentbridge-hr-recruitment-automation/main/screenshots/08-trello-new-application-card.png)
