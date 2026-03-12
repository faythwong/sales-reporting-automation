# Sales Reporting Automation

An automated workflow that retrieves ERP sales data, filters processing orders, stores selected records in Airtable, and posts weekly sales summaries to Discord.

This project demonstrates practical business automation using scheduled workflows, API integrations, JavaScript data processing, and team reporting.

---

## Features

- Scheduled weekly reporting
- ERP/API data retrieval
- Conditional filtering for order status
- Airtable record creation
- JavaScript-based sales aggregation
- Automated Discord reporting

---

## Workflow Overview

```text
Schedule Trigger
→ Fetch ERP Sales Data
→ Check Order Status
→ Route Processing Orders to Airtable
→ Aggregate Weekly Sales Metrics
→ Send Summary to Discord
```

---

## Tech Stack

- n8n
- HTTP API integration
- Airtable
- Discord
- JavaScript

---

## Use Case

This workflow can be used by operations or sales teams to:

- monitor weekly booked orders
- track total order value
- store selected sales records
- automatically notify internal teams

---

## Repository Structure

```text
sales-reporting-automation/
├── README.md
├── workflow/
│   └── sales-reporting-workflow.json
├── docs/
│   ├── architecture.md
│   ├── setup-guide.md
│   └── example-output.md
├── demo/
│   └── demo-scenario.md
└── LICENSE
```

---

## Setup

See [docs/setup-guide.md](docs/setup-guide.md)

---

## Documentation

- [System Architecture](docs/architecture.md)
- [Setup Guide](docs/setup-guide.md)
- [Example Output](docs/example-output.md)
- [Demo Scenario](demo/demo-scenario.md)

---

## Skills Demonstrated

- workflow automation
- API integrations
- conditional routing
- JavaScript data aggregation
- team reporting automation
- low-code system design

---

## Security

All credentials, IDs, tokens, endpoints, and internal identifiers have been removed from this repository.
