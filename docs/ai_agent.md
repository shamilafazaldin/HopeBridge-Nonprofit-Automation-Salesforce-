# Einstein 1 Agent – HopeBridge CRM (Optional)

This document explains how Einstein 1 Agent was added to the HopeBridge Outreach Salesforce org to provide natural language insights and streamline user experience.

---

## Purpose

Einstein 1 Agent provides AI-powered responses to natural language queries inside Salesforce. This helps nonprofit staff ask quick questions like:

- “Who are the top 5 donors this month?”
- “List all upcoming food drives.”
- “Create a follow-up task for a new contact.”

---

## Configuration Steps

1. **Enable Einstein 1 Agent**
   - Go to Setup → Einstein → Einstein 1 Setup
   - Enable Agent and follow prompts to activate

2. **Add Agent to App**
   - From App Manager, edit “Nonprofit Success Pack” app
   - Add the Einstein 1 Assistant utility item to the navigation bar

3. **Set Up Basic Prompts**
   - Added sample natural language prompts
   - Example: “Show me donors who gave more than $500 this year”

4. **Tested Queries**
   - Prompt: “Show top donors this month”
     - Output: List of Contacts with recent donation Opportunities
   - Prompt: “Create task to follow up with Sarah Lee”
     - Output: AI-generated task with subject line and due date

---

## Notes

- The Einstein 1 Agent is powered by Salesforce Data Cloud (if enabled)
- Only basic prompt functionality was tested in this project
- Further enhancements could include training prompts or connecting to external actions

---

## Outcome

Einstein Agent adds a modern, user-friendly interface for non-technical users to query CRM data and create actions without navigating multiple tabs.

