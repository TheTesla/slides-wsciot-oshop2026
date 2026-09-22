# Slides: IoT monitoring solution for event based water sample collection – Lessons learnt

Quarto (revealjs) presentation for the **oSHOP Conference 2026** (Halle/Saale, 23–24 Sept 2026).
Talk: 10–15 min + 10 min Q&A. Language: English.

## Preview / render

Requirements: [Quarto](https://quarto.org/) ≥ 1.4.

```bash
quarto preview oshop2026-iot-water-sampler.qmd
quarto render oshop2026-iot-water-sampler.qmd --to revealjs
```

The rendered single-file HTML (`oshop2026-iot-water-sampler.html`, `embed-resources: true`)
is committed alongside the source for easy sharing.

## Content

- `oshop2026-iot-water-sampler.qmd` – slide source
- `htwd-theme.css` – HTW Dresden corporate design (from `HTWD_PPT-Master` .potx template)
- `logos/` – official HTWD logos (wordmark for footer, horizontal for title slide)
  and VolkswagenStiftung logo
- `photos/` – slide images (copies of the paper figures)
- Paper (full text): separate Overleaf-synced repo, not included here
  (see `.gitignore`).

Design notes: white background, Open Sans, black text, orange accent `#EC6608`;
title slide with diagonal photo cut; footer with wordmark logo, date, short title
and slide number on every slide except the title slide.
Funding acknowledgement: VolkswagenStiftung, grant 9C858.
