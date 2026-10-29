---
title: Hypertriglyceridemia workup
publish: true
type: gate
up: "[[Gates]]"
parent: "Gates"
description: "Secondary causes to address before escalating triglyceride therapy."
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
Secondary causes to address before escalating triglyceride therapy.

## Inputs from History (auto-listed)
Every history field tagged to feed this gate:

```base
filters:
  and:
    - 'type == "history-element"'
    - 'feeds_gates.contains("Hypertriglyceridemia workup")'
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
