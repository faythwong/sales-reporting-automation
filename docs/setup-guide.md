# Setup Guide

## 1. Install n8n

Install n8n globally:

```bash
npm install n8n -g
```

Or run it with Docker.

---

## 2. Import the Workflow

Import the workflow file located at:

```text
workflow/sales-reporting-workflow.json
```

---

## 3. Configure Credentials

Inside n8n, configure credentials for:

- HTTP Header Authentication
- Airtable
- Discord Webhook

---

## 4. Update Placeholder Values

Replace placeholder values in the workflow with your own:

- API endpoint
- API secret token
- Airtable base ID
- Airtable table ID
- Discord webhook configuration

---

## 5. Activate the Workflow

Enable the workflow in n8n.

The automation will then run on the configured weekly schedule.
