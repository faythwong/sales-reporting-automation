# Demo Scenario

## Scenario

A sales team wants to receive a weekly summary of booked orders and store selected processing orders in Airtable for operational tracking.

---

## Workflow Execution

1. The workflow starts on the scheduled day and time.
2. Sales data is retrieved from the ERP/API.
3. Orders with `processing` status are sent to Airtable.
4. Other order records are aggregated using JavaScript.
5. A Discord summary is sent to the team.

---

## Outcome

The team receives an automated weekly sales summary without manual calculation or reporting.
