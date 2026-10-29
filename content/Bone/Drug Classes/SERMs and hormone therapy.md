---
visibility: private
publish: false
type: drug-class
up: "[[Osteoporosis]]"
source: "AACE/ACE 2020 PMO; Endocrine Society PMO 2019/2020; FDA labels"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
mechanism: "Estrogen receptor modulation"
first_line_for: "Younger postmenopausal women, vertebral risk, or menopausal symptoms"
key_risk: "VTE; raloxifene has no hip or nonvertebral fracture benefit"
---
# SERMs and hormone therapy
Raloxifene also lowers invasive breast cancer risk. Menopausal hormone therapy: see the Menopause domain when built.

## Agents (layer 3: click a row)
```base
filters:
  and:
    - 'type == "drug"'
    - 'drug_class == "SERMs and hormone therapy"'
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
