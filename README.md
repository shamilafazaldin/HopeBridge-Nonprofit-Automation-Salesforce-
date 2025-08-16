# HopeBridge Nonprofit CRM + Automation (Salesforce Portfolio Project)

This is a portfolio project demonstrating a complete Salesforce CRM implementation for a fictional nonprofit organization, HopeBridge Outreach. The system is built using the Salesforce Nonprofit Success Pack (NPSP) to streamline the management of donors, volunteers, and clients, while automating key tasks using Salesforce Flows.

## Project Purpose

Nonprofits often struggle to manage donor relationships, volunteer engagement, and service delivery using spreadsheets or disconnected tools. This demo CRM centralizes all key operations and introduces automation to reduce manual admin tasks.

## Project Overview

HopeBridge Outreach is a nonprofit serving communities by providing food access and mental wellness support. This project configures Salesforce to manage the nonprofit's activities, such as tracking donations, volunteers, client services, and automating administrative tasks. The implementation utilizes NPSP for managing contacts, donations, and campaigns, with additional automation provided through Salesforce Flows.

The project focuses on building an easy-to-use Salesforce system for nonprofits with limited technical capacity, aimed at reducing administrative overhead and improving engagement tracking. This CRM implementation can help HopeBridge Outreach run more efficiently by automating tasks such as donor follow-ups, event reminders, and campaign reporting.

## Key Features

### CRM Configuration
- **Custom Contact Fields:** Track constituents by role (Donor, Volunteer, Client, Staff), service type (Food Access, Wellness Support, Both), and follow-up dates.
- **Opportunities:** Manage and track donations.
- **Campaigns:** Used for food drives and wellness workshops.
- **Tasks:** For follow-up actions and reminders related to donations, events, and volunteer management.

### Flow Automation
- **Record-Triggered Flows:** Automatically create tasks when donations are recorded or when a new contact is added to a campaign.
- **Scheduled Flows:** Automate reminder emails for upcoming events and check-ins with inactive donors.
- **Email Templates:** Send automated thank-you emails for donations and reminders for upcoming events.

### Reports & Dashboards
- **Donation Reports:** Track donations by campaign and donor type.
- **Volunteer Activity:** Summarize volunteer participation by event.
- **Follow-up Tasks:** Dashboard tracking overdue follow-ups for staff to ensure timely outreach.

### Campaigns and Event Tracking 
 Tracks participation, donations, and outcomes for marketing campaigns and events.
- **Created sample Campaigns for:** -
- Food Drive – August
- Wellness Workshop – September
- **Added sample Contacts to Campaigns:** 
- Verified Campaign Member statuses (Planned, Responded, Attended)

### Einstein Bot - Engagement Assistant

-This Einstein Bot provides a guided experience for users to quickly access information related to donors, volunteers, and campaign performance.  
-It is designed to simplify navigation and support staff in engaging with core fundraising and event data.

---



## Project Phases

### 1. **Salesforce Developer Org Setup**
- Created a new Salesforce Developer Org for the HopeBridge nonprofit project.
- Installed the Nonprofit Success Pack (NPSP) to provide nonprofit-specific features and data models.

### 2. **Customizing the CRM Structure**
- Configured the Contact object with custom fields for tracking role (e.g., Donor, Volunteer), service type, and follow-up date.
- Set up Opportunities to track donations and Campaigns for organizing events and initiatives.

### 3. **Creating Automation with Flows**
- Created Record-Triggered Flows to automate follow-up task creation after a donation is logged.
- Built Scheduled Flows to remind the nonprofit team about upcoming events or inactive contacts needing follow-up.
- Set up email templates to send automated reminder emails to volunteers and donors.

### 4. **Reports and Dashboards**
- Designed donation reports by campaign and donor type.
- Set up a dashboard to track volunteer hours, event participation, and upcoming follow-up tasks.

### Campaigns and Event Tracking

- Created sample Campaigns for: Food Drive – August & Wellness Workshop – September
- Added sample Contacts to Campaigns & Verified Campaign Member statuses (Planned, Responded, Attended)
 

### 5. # Einstein Bot - Engagement Assistant

## Overview
This Einstein Bot provides a guided experience for users to quickly access information related to donors, volunteers, and campaign performance.  
It is designed to simplify navigation and support staff in engaging with core fundraising and event data.

---

## Bot Structure

### Main Menu
- **Donor Information**
- **Volunteer Information**
- **Review Campaign Performance**

---

## Dialogs

### 1. Donor Information
**Purpose:**  
Provides quick access to donor-related data and guidance.

**Key Components:**  
- Message elements with navigation tips  
- Directs users to the **Opportunities/Donations tab** for donor activity  
- Guides on how to review donation history and details  

---

### 2. Volunteer Information
**Purpose:**  
Supports staff by pointing them to volunteer-related data.

**Key Components:**  
- Message elements with navigation tips  
- Directs users to the **Contacts tab** and related lists for volunteer details  
- Explains where to find volunteer roles and event participation  

---

### 3. Review Campaign Performance
**Purpose:**  
Guides staff on how to view campaign metrics and performance.

**Message:**  
*"You can see the performance of any campaign by viewing its record.  
Go to the **Campaigns tab**, select the campaign you want to review, and check the **Campaign Details** section to see key metrics like Total Donations and Member Status.  
For more detailed insight, you can use the **Reports tab** to create a custom Campaign Performance report."*

**Notes:**  
- This dialog contains only one **Message element**.  
- Purely informational — no flow branching.  

---

## Deployment
- Added to the **Service App navigation bar** for quick access.  
- Bot is published and available for staff through the **utility bar** or **app workspace**.  

---

## Core Components Built
- Einstein Bot with **Main Menu & 3 Dialogs**  
- Simple navigation & guidance (no Apex or custom code)  
- Integration with standard Salesforce objects: **Opportunities, Contacts, Campaigns**

---

## Benefits
- Staff can quickly locate donor, volunteer, and campaign data without extra training.  
- Reduces time spent searching across records.  
- Creates a lightweight self-service assistant directly inside Salesforce.  

## Tools Used

- **Salesforce Developer Org:** Custom environment to build and demonstrate CRM features.
- **Nonprofit Success Pack (NPSP):** A Salesforce package for nonprofits, providing pre-built objects and workflows.
- **Flow Builder:** To create automation flows that streamline tasks and reminders.
- **Reports & Dashboards:** To visualize donation and volunteer activity.
- **Google Docs, GitHub, Loom:** For project documentation, version control, and video walkthroughs.

## Target Audience

This project is designed to demonstrate Salesforce Admin skills for small nonprofits or solopreneurs. It is particularly valuable for organizations that need a low-cost, user-friendly CRM to manage donor relationships, volunteer programs, and service delivery.

## Outcome

The HopeBridge Outreach CRM implementation enables nonprofit teams to:
- Track and manage donor and volunteer information efficiently.
- Automate common tasks such as donation tracking and follow-ups.
- Provide real-time reporting on donations and volunteer activity.
- Focus on mission-driven work instead of administrative tasks.

## Future Enhancements

Potential enhancements include:
- Integration with external platforms (e.g., email marketing, social media).
- Enhanced reporting and analytics for tracking long-term donor engagement.
- Additional automation to further streamline nonprofit workflows.

## Author

[Shamila]  
Salesforce Admin Portfolio Project – [6/7/2025]


## Credits

This is a fictional demo project developed by me as part of a Salesforce Admin learning portfolio. It is not affiliated with any real nonprofit or organization.


