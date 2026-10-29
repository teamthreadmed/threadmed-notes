---
visibility: private
publish: false
type: dashboard
up: "[[00 Home]]"
---
# Review queue
Every clinical note whose review-by date has passed or falls in the next 60 days.

```base
filters:
  and:
    - 'review_by <= today() + "60d"'
views:
  - type: table
    name: Due for review
    order:
      - file.name
      - type
      - source
      - review_by
    sort:
      - property: review_by
        direction: ASC
```
