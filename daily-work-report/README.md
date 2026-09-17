# Daily Work Report Automation

An automated n8n workflow that generates and sends a daily work report based on tasks stored in Google Sheets.

## Problem Solved

Manually preparing daily work reports takes time and can lead to missing or duplicated tasks.

This workflow automatically collects the day's tasks, formats them into a structured report, creates the report document, and sends it to Telegram.

## Workflow Flow

Schedule Trigger  
↓  
Google Sheets  
↓  
Filter Today's Tasks  
↓  
Format Report  
↓  
Create Report  
↓  
Send to Telegram  
↓  
Mark Tasks as Reported

## Features

- Runs automatically every day
- Reads tasks directly from Google Sheets
- Filters only the current day's tasks
- Prevents already reported tasks from being sent again
- Generates a structured daily report
- Sends the final report to Telegram
- Automatically updates task status after reporting

## Tools Used

- n8n
- Google Sheets
- Google Docs
- Telegram Bot API
- JavaScript Code Nodes

## Requirements

- n8n instance
- Google account
- Google Sheets credentials
- Google Docs credentials
- Telegram Bot
- Telegram Chat ID

## Setup

1. Import `workflow.json` into n8n
2. Connect your Google credentials
3. Connect your Telegram Bot credentials
4. Select your Google Sheet
5. Configure your Telegram Chat ID
6. Test the workflow
7. Activate it

## Workflow File

`workflow.json`

## Security

Credentials and API keys are not included in this repository.

You must configure your own credentials after importing the workflow.
