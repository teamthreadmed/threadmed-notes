---
visibility: private
publish: false
type: drug-class
up: "[[Osteoporosis]]"
source: "AACE/ACE 2020 PMO; Endocrine Society PMO 2019/2020; FDA labels"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
mechanism: "Inhibit osteoclast activity (bind hydroxyapatite)"
first_line_for: "High risk; first line for most"
key_risk: "Atypical femoral fracture, ONJ (rare); GI with oral"
---
# Bisphosphonates
Drug holiday (ASBMR 2016 task force): consider after 5 y oral or 3 y IV if no longer high risk. Continue up to 10 y oral / 6 y IV if still high risk.

## Agents (layer 3: click a row)
```base
filters:
  and:
    - 'type == "drug"'
    - 'drug_class == "Bisphosphonates"'
views:
  - type: table
    name: Agents
    order:
      - file.name
      - dose
      - route
      - renal_limit
      - duration_rule
```
