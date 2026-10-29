---
visibility: private
publish: false
type: condition
up: "[[00 Home]]"
source: "AACE/ACE 2020 PMO; Endocrine Society PMO 2019 + 2020 update; Endocrine Society Osteoporosis in Men 2025; BHOF 2022"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
down:
  - "[[Risk stratification]]"
  - "[[Secondary causes workup]]"
  - "[[Bisphosphonates]]"
  - "[[Denosumab class]]"
  - "[[Anabolics]]"
  - "[[SERMs and hormone therapy]]"
---
# Osteoporosis
Layer 1 hub. Each row below is a note; open one to drop a layer.

## Evaluate
- [[Risk stratification]] (who to treat, who is very high risk)
- [[Secondary causes workup]]

## Drug classes (nested table: click a class to see its agents)
```base
filters:
  and:
    - 'type == "drug-class"'
views:
  - type: table
    name: Classes
    order:
      - file.name
      - mechanism
      - first_line_for
      - key_risk
```

## All agents (flat view of layer 3)
```base
filters:
  and:
    - 'type == "drug"'
views:
  - type: table
    name: All agents
    order:
      - file.name
      - drug_class
      - dose
      - route
      - renal_limit
      - duration_rule
    groupBy:
      property: drug_class
      direction: ASC
```
