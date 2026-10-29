---
title: Teaching
publish: true
type: teaching-hub
up: "[[index]]"
description: "Original teaching diagrams."
---
Original teaching diagrams. Each one links to the notes it teaches.

```base
filters:
  and:
    - 'type == "teaching"'
views:
  - type: table
    name: Diagrams
    order:
      - file.name
      - description
```
