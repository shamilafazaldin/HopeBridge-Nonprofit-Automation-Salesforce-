# Reports & Dashboards – HopeBridge CRM

This document outlines all reports and dashboards created to support HopeBridge Outreach’s donor, volunteer, and task management efforts.

---

## Reports

### 1. Donations by Campaign

- **Report Type:** Opportunities with Campaign
- **Filters:** Opportunity Type = Donation, Closed = True
- **Grouped by:** Campaign Name
- **Purpose:** Track how effective each campaign is at generating donations

---

### 2. Volunteer Participation

- **Report Type:** Campaign Members with Contacts
- **Filters:** Campaign Type = Volunteer Event
- **Grouped by:** Campaign Name and Member Status
- **Purpose:** View which volunteers attended or responded to events

---

### 3. Overdue Follow-Up Tasks

- **Report Type:** Tasks and Events
- **Filters:** Status ≠ Completed, Due Date < TODAY
- **Grouped by:** Assigned User
- **Purpose:** Show overdue follow-up tasks by staff member

---

## Dashboards

### 1. Nonprofit Engagement Dashboard

This dashboard includes 4 key components:

1. **Total Donations This Month**
   - Source: Donations by Campaign report
   - Chart Type: Metric

2. **Top 3 Active Campaigns**
   - Source: Campaign Members report
   - Chart Type: Horizontal Bar

3. **Overdue Tasks by Staff**
   - Source: Overdue Tasks report
   - Chart Type: Stacked Bar

4. **Donor Retention Gauge**
   - Custom metric using total donations over time (placeholder)
   - Chart Type: Gauge

---

## Notes

- All reports and dashboards were created in Lightning Report Builder
- Dashboards are updated automatically with real-time data
- Filters can be customized per user (e.g., show only their own tasks)

