---
title: Disease State Education
publish: true
type: dse-hub
up: "[[index]]"
description: "Plain-language teaching on common endocrine and cardiometabolic conditions, built around the images used in clinic."
version_date: 2026-10-30
---
Teaching notes for patients and the clinicians who teach them. Each note is built around one image used in clinic: what the picture shows, what it means, and what can be done about it.

## Sections
- [[Cardiometabolic]]: atherosclerosis, cholesterol, diabetes, weight, blood pressure
- [[Osteoporosis education|Osteoporosis]]: bone strength, fracture risk, treatment
- [[Other conditions]]: thyroid, menopause, adrenal and pituitary

```base
filters:
  and:
    - 'type == "dse"'
views:
  - type: table
    name: All teaching notes
    order:
      - file.name
      - section
      - description
```

> [!warning] Education, not medical advice
> These notes explain conditions in general terms. Decisions about your own care belong with your clinician.
