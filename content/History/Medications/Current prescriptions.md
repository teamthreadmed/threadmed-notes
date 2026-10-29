---
title: Current prescriptions
publish: true
type: history-element
up: "[[Medications]]"
parent: "Medications"
description: "Active prescribed medications."
data_type: "List of agent + dose + frequency + start date"
values: "Coded agent (RxNorm); dose; route; frequency; start date; prescriber"
feeds_gates: ["Medication safety check"]
source: "Structure: Anthony Pick; gate criteria per cited tools"
version_date: 2026-10-29
evidence: "verify"
review_by: 2027-04-30
---
Active prescribed medications.

**Capture:** List of agent + dose + frequency + start date. **Values:** Coded agent (RxNorm); dose; route; frequency; start date; prescriber

Start dates matter: drug-holiday and duration rules (bisphosphonates, denosumab timing) depend on them.

## Feeds these gates
- [[Medication safety check]]
