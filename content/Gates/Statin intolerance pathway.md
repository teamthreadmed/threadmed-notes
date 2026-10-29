---
title: Statin intolerance pathway
publish: true
type: gate
up: "[[Gates]]"
parent: "Gates"
description: "Rechallenge, dose change or non-statin options after statin-associated symptoms."
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
Rechallenge, dose change or non-statin options after statin-associated symptoms.

## Inputs from History (auto-listed)
Every history field tagged to feed this gate:

```base
filters:
  and:
    - 'type == "history-element"'
    - 'feeds_gates.contains("Statin intolerance pathway")'
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
