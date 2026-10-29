---
title: Medications
publish: true
type: history-domain
up: "[[History]]"
parent: "History"
description: "Current and past medications, with exposure classes that feed bone, metabolic and endocrine gates."
source: "Structure: Anthony Pick; gate criteria per cited tools"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
Current and past medications, with exposure classes that feed bone, metabolic and endocrine gates.

## Contents (click a row to go down a layer)
```base
filters:
  and:
    - 'parent == "Medications"'
views:
  - type: table
    name: Medications
    order:
      - file.name
      - description
      - feeds_gates
```
