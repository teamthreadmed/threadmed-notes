---
visibility: private
publish: false
type: drug-class
up: "[[Osteoporosis]]"
source: "AACE/ACE 2020 PMO; Endocrine Society PMO 2019/2020; FDA labels"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
mechanism: "PTH/PTHrP analogs; sclerostin inhibition"
first_line_for: "Very high risk; first line per AACE 2020"
key_risk: "Romosozumab: MI/stroke in past 12 months is a contraindication"
---
# Anabolics
Always follow with an antiresorptive to keep gains. Avoid denosumab → teriparatide (transient BMD loss, DATA-Switch).

## Agents (layer 3: click a row)
```base
filters:
  and:
    - 'type == "drug"'
    - 'drug_class == "Anabolics"'
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
