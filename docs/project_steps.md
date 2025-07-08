# Project Build Log – HopeBridge CRM (Salesforce)

This document tracks each major implementation step in the HopeBridge nonprofit CRM project. It follows the configuration of Salesforce Nonprofit Success Pack (NPSP), automation using Flows, reporting, and AI enhancements.

---

## Step 1 – Developer Org Setup

- Signed up for a Salesforce Developer Org at developer.salesforce.com
- Created username and logged into the Lightning Experience successfully
- Verified access to standard objects: Leads, Contacts, Opportunities

---

## Step 2 – Install Nonprofit Success Pack (NPSP)

- Installed NPSP via official Salesforce.org link
- Selected “Install for All Users” and approved third-party access
- Confirmed installation complete
- Verified NPSP-specific tabs: Donations, Households, Affiliations, etc.


## Confirm NPSP Installation

After installing the Nonprofit Success Pack, verify that it appears in the App Launcher with the correct tabs.

![NPSP Installed](./screenshots/npsp-installed.png)

---

## Step 3 – Customize Contact Object

- Added custom fields:
  - Constituent Role (Donor, Volunteer, Client, Staff)
  - Service Type (Food, Wellness, Both)
  - Follow-Up Date (Date field)
- Updated Contact Page Layout to display new fields

---

## Step 4 – Create Record-Triggered Flow: Follow-Up Task for New Donation

- Triggered on new Opportunity record where Type = Donation
- Automatically creates Task for assigned user to follow up
- Flow tested and verified using a sample donation

---

## Step 5 – Create Scheduled Flow: Re-Engagement for Inactive Donors

- Scheduled monthly run
- Finds Contacts with no donation in the past 6 months
- Creates Task for admin to re-engage with donor

---

## Step 6 – Campaigns and Event Tracking

- Created sample Campaigns for:
  - Food Drive – August
  - Wellness Workshop – September
- Added sample Contacts to Campaigns
- Verified Campaign Member statuses (Planned, Responded, Attended)

---

## Step 7 – Record-Triggered Flow: Reminder Email for Upcoming Events

- Flow triggered when Follow-Up Date = Today
- Sends email reminder to assigned Contact using Email Alert
- Custom Email Template created for reminder message

---

## Step 8 – Reports and Dashboards

- Created report types:
  - Donations by Campaign
  - Volunteer Participation
  - Overdue Tasks by Assigned User
- Built a dashboard with 4 components using the above reports

---

## Step 9 – Optional Add-On: Einstein 1 Agent Assistant

- Enabled and added Einstein 1 Agent to App
- Configured 3 sample prompts:
  - "Show top donors this month"
  - "List all upcoming events"
  - "Create follow-up task for new contact"
- Verified responses via Einstein UI

---

## Step 10 – Final Testing and Demo Preparation

- Created 2 test Contacts, 2 sample Donations, and 1 Campaign
- Ran all Flows and verified outcomes
- Final screenshots and Loom walkthroughs created for portfolio
