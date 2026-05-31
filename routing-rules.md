# Lead Routing Rules

## Purpose

Lead routing sends each lead to the correct pipeline, team member, or nurture sequence.

## Routing Logic

```text
IF lead source = Facebook Ads
AND budget is above £1,000
THEN assign to Sales Pipeline

IF lead is not ready to buy
THEN move to Nurture Sequence

IF existing customer submits a request
THEN assign to Customer Success

IF lead books a call
THEN move to Booked Call stage
```
