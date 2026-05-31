# Follow-Up Sequences

## Purpose

Follow-up sequences keep leads engaged until they respond, book a call, buy, or become inactive.

## Example Sequence

```text
Day 0: Instant email and SMS
Day 1: Reminder email
Day 2: Sales call task
Day 4: Case study email
Day 7: Final check-in
Day 14: Move to long-term nurture
```

## Automation Logic

```text
IF lead replies
THEN stop follow-up sequence
AND notify sales rep

IF lead books a call
THEN move to Booked Call stage

IF no response after 14 days
THEN move to Nurture stage
```
