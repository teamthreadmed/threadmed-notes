---
title: FRAX inputs
publish: true
type: gate
up: "[[Gates]]"
parent: "Gates"
description: "History fields that feed the FRAX 10-year fracture probability (MOF and hip)."
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
History fields that feed the FRAX 10-year fracture probability (MOF and hip).

## Inputs from History (auto-listed)
Every history field tagged to feed this gate:

```base
filters:
  and:
    - 'type == "history-element"'
    - 'feeds_gates.contains("FRAX inputs")'
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
