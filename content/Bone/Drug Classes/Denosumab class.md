---
visibility: private
publish: false
type: drug-class
up: "[[Osteoporosis]]"
source: "AACE/ACE 2020 PMO; Endocrine Society PMO 2019/2020; FDA labels"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
mechanism: "RANKL monoclonal antibody"
first_line_for: "High risk; CKD where bisphosphonates are limited"
key_risk: "Rebound vertebral fractures if stopped late or without follow-on therapy; severe hypocalcemia in advanced CKD (FDA boxed warning 2024)"
---
# Denosumab class
No drug holiday. On stopping, transition to a bisphosphonate (commonly zoledronic acid ~6 months after the last dose; consider CTX-guided follow-up).

## Agents (layer 3: click a row)
```base
filters:
  and:
    - 'type == "drug"'
    - 'drug_class == "Denosumab class"'
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
