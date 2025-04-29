# 📧 Email Reminder Bot

## Overview
An automated email reminder bot built with n8n.  
It sends a scheduled daily reminder email to a target address automatically at a set time each day.

## Workflow Diagram
> Schedule Trigger → Set Node (Subject & Body) → Send Email (SMTP)

## Business Value
- Helps users stay on top of daily tasks without manual effort.
- Reduces forgetfulness and improves daily organization.
- Simple but expandable to team updates, task tracking, or habit reminders.

## Skills Learned
- Using Schedule Trigger nodes to automate actions.
- Structuring data using Set nodes.
- Sending emails via SMTP (Gmail) inside n8n.
- Managing data flow between nodes.
- Troubleshooting JSON data handling and testing full workflow execution.

## Challenges
- Understanding that individual node tests don’t pass upstream data — full workflows must be executed.
- Correct SMTP authentication using App Passwords.
- Managing case sensitivity in field names.

## Screenshots
_Insert your screenshots here, for example:_
- Full workflow diagram (n8n canvas view).
- Example of the email received (subject and body visible).

## Files
- `email-reminder-bot.json` — exported n8n workflow file.
- `/screenshots/` — folder with visuals of workflow and output.

---

✅ Built using [n8n.io](https://n8n.io) and basic SMTP integrations.
