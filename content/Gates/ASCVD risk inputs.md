---
title: ASCVD risk inputs
publish: true
type: gate
up: "[[Gates]]"
parent: "Gates"
description: "History fields that feed 10-year ASCVD risk (PCE, PREVENT)."
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
History fields that feed 10-year ASCVD risk (PCE, PREVENT).

## Inputs from History (auto-listed)
Every history field tagged to feed this gate:

```base
filters:
  and:
    - 'type == "history-element"'
    - 'feeds_gates.contains("ASCVD risk inputs")'
views:
  - type: table
    name: Inputs
    order:
      - file.name
      - parent
      - data_type
      - values
```

## Logic
*Stub: thresholds and decision rules to be added.*
