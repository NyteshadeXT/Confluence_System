```base
and:
  - file.hasTag("Mind")
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Essence Powers")
        - essences.contains("Mind")
    groupBy:
      property: slot
      direction: ASC
    order:
      - file.name
      - slot
      - essences
    summaries:
      file.name: Filled
  - type: cards
    name: View

```