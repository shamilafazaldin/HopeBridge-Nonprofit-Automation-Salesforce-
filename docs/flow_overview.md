# Flow Documentation – HopeBridge CRM

This file summarizes all Flows created during the project and explains how each one supports automation for HopeBridge Outreach.

---

## 1. Follow-Up Task for New Donation

- **Flow Name:** Donation Follow-Up Task
- **Type:** Record-Triggered Flow
- **Trigger:** When a new Opportunity (Donation) is created
- **Criteria:** Opportunity Type = "Donation"
- **Action:** Create Task assigned to admin for donor follow-up
- **Purpose:** Ensures no donor is ignored; promotes personal outreach
- **Test Result:** Task is created successfully upon donation creation

---

## 2. Re-Engage Inactive Donors

- **Flow Name:** Inactive Donor Follow-Up
- **Type:** Scheduled Flow
- **Trigger Frequency:** Monthly
- **Criteria:** Contacts with no related donation in the last 6 months
- **Action:** Create a follow-up Task and assign to admin
- **Purpose:** Helps revive lapsed donors and maintain engagement
- **Test Result:** Tasks were created for inactive donors as expected

---

## 3. Reminder Email for Upcoming Events

- **Flow Name:** Event Reminder Email
- **Type:** Record-Triggered Flow
- **Trigger:** When a Contact’s Follow-Up Date = Today
- **Criteria:** Follow-Up Date field matches current date
- **Action:** Send email alert using Email Template
- **Purpose:** Remind volunteers/donors about scheduled events
- **Test Result:** Email sent to contact successfully

---

## Notes

- All Flows were tested in the Developer Org
- Where possible, flows were built using standard Salesforce elements to maintain compatibility with NPSP
- All flows are visible under Process Automation → Flows in Setup
