# NPCs

```base
views:
  - type: cards
    name: NPCs
    image: portrait
    imageAspectRatio: 1
    imageFit: cover
    order:
      - notes
    filters: 'file.inFolder("NPCs") && file.name != "NPCs" && status != "deceased"'
```

## Deceased

```base
views:
  - type: cards
    name: Deceased
    image: portrait
    imageAspectRatio: 1
    imageFit: cover
    order:
      - notes
    filters: 'file.inFolder("NPCs") && file.name != "NPCs" && status == "deceased"'
```
