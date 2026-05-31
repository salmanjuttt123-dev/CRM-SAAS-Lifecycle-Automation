# Lead Qualification Workflow

## Purpose

This workflow checks whether a new lead is a good fit for the business.

## Qualification Criteria

- Budget
- Need
- Timeline
- Decision-maker status
- Business size
- Service fit
- Location
- Urgency

## Automation Logic

```text
IF budget is above the minimum threshold
AND the lead needs the service within 30 days
THEN mark as Qualified
AND assign to a sales owner
AND move to the Qualified stage
```

## CRM Statuses

```text
New Lead
Qualified
Unqualified
Needs Nurture
Booked Call
```

## SaaS Tools Used

- HubSpot
- GoHighLevel
- Zapier
- n8n
