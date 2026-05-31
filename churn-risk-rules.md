# Churn Risk Rules

## Purpose

Churn risk rules identify customers who may cancel, stop using the service, or need extra support.

## Risk Signals

```text
No login activity for 7 days
Multiple unresolved support tickets
Low NPS score
Payment failure
Low product usage
Renewal date approaching with low engagement
```

## Automation Logic

```text
IF customer has no login activity for 7 days
OR customer health score is below 50
THEN mark customer as At Risk
AND notify customer success
AND create follow-up task
```
