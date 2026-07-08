# Photos

Drop your photos here and update the paths in `index.html`.

## Expected filenames (referenced in HTML as commented `<img>` tags)

### Chapters (timeline)
- `2020-arrival.jpg` — Chapter 01, first arrival in Munich
- `2021-lmu.jpg` — Chapter 02, LMU / start of KI studies
- `2023-study.jpg` — Chapter 03, bridge year
- `2024-allianz.jpg` — Chapter 04, Allianz start
- `2025-foto2text.jpg` — Chapter 05, Foto2Text project
- `2026-now.jpg` — Chapter 06, present day

### Archive (photo wall)
- `archive-01.jpg` — landscape (large card)
- `archive-02.jpg` — portrait (pill card)
- `archive-03.jpg` — square/portrait (circle card)
- `archive-04.jpg` — wide/landscape (wide card)

## Aspect ratios (recommended crops)
- rect (4:5) portrait
- square (1:1) — will be masked to a circle
- wide (16:9) landscape
- pill (3:5) tall portrait — will be masked to a pill shape

## Activate a photo
In `index.html`, find the corresponding `<div class="frame ...">` block and:
1. Delete or comment out `<div class="placeholder">...</div>`
2. Uncomment the `<img src="photos/....jpg" ...>` line
