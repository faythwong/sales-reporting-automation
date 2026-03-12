# System Architecture

This workflow automates weekly sales reporting by pulling ERP data, processing order records, and sending a summary to internal communication channels.

---

## Workflow Steps

1. **Schedule Trigger**
   - Starts the workflow on a weekly schedule.

2. **HTTP Request**
   - Retrieves order data from an ERP or internal API endpoint.

3. **Conditional Check**
   - Evaluates whether an order is in `processing` status.

4. **Airtable Record Creation**
   - Stores selected processing orders in Airtable.

5. **JavaScript Aggregation**
   - Counts total booked orders.
   - Calculates total booked sales value.

6. **Discord Notification**
   - Sends a weekly summary to the team.

---

## Core Logic

```text
Schedule Trigger
→ API Data Fetch
→ If orderStatus == processing
   ├── Yes → Store selected fields in Airtable
   └── No  → Aggregate order metrics
→ Send summary to Discord
```

---

## Business Value

This automation reduces manual reporting work and gives teams a timely overview of weekly sales performance.
