```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Bestiary")
    order:
      - file.name
      - level
    sort:
      - property: file.name
        direction: ASC
      - property: level
        direction: ASC
  - type: cards
    name: View
    filters:
      and:
        - file.folder == "Bestiary"
    image: file.file

```