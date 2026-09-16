# n8n Automation Workflows

A collection of practical automation workflows built with n8n for business operations, reporting, AI, CRM, and productivity.

---

## Workflows

### 1. Daily Work Report Automation

Automatically collects daily tasks from Google Sheets, formats them into a structured daily report, creates the report document, and sends it through Telegram.

### Workflow Flow

Schedule Trigger  
↓  
Google Sheets  
↓  
Filter Today's Tasks  
↓  
Format Report  
↓  
Google Docs  
↓  
Prepare File  
↓  
Telegram  
↓  
Mark Tasks as Reported

### Features

- Runs automatically every day
- Reads tasks from Google Sheets
- Filters tasks for the current day
- Generates a structured daily report
- Creates a Google Docs report
- Sends the report automatically to Telegram
- Prevents previously reported tasks from being sent again

### Tools Used

- n8n
- Google Sheets
- Google Docs
- Telegram Bot API
- JavaScript / Code Nodes

### Workflow File

`Daily Work Report Automation.json`

### Use Case

This workflow is useful for teams and individuals who want to automatically generate and send daily work reports without manually writing them every day.

---

## How to Import

1. Download the workflow JSON file
2. Open n8n
3. Go to Workflows
4. Import from File
5. Configure your own credentials
6. Update Google Sheets, Google Docs, and Telegram settings
7. Test the workflow
8. Activate it

---

## Security

No API keys, passwords, or private credentials are included in the workflow files.

Always use your own credentials after importing.
