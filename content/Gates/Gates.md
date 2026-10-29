---
title: Gates
publish: true
type: gate-hub
up: "[[index]]"
description: "Logic gates. Each one lists the History fields it reads."
---
Logic gates. Each gate page lists, automatically, every [[History]] field that feeds it.

```base
filters:
  and:
    - 'type == "gate"'
views:
  - type: table
    name: Gates
    order:
      - file.name
      - description
```
