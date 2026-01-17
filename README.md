# Willoughby Data Busters (WDATA) — Open Template Pack

This repository contains an open, public template pack for **Willoughby Data Busters (WDATA)**:
- **Discovery DSAR** (6 variants)
- **14‑Day Reminder** (6 variants)
- **7‑Day Final Notice** (6 variants)
- **Article 21 Objection** (6 variants)

Templates are designed for **UK GDPR / Data Protection Act 2018** style correspondence and are structured to support automated rendering (placeholders + random variant selection).

## What’s in this repo

All templates live under `/templates/`:

- `/templates/01-original-dsar/`
- `/templates/02-reminder-14-day/`
- `/templates/03-final-7-day/`
- `/templates/04-article-21/`

Each folder contains `Template-01` through `Template-06` (six variants) to support variation / anti-bot similarity.

This pack contains **24 active templates total** (4 types × 6 variants). [Source](https://www.genspark.ai/api/files/s/9LwpP4dR)

## Placeholders (rendering contract)

Templates use double-curly placeholders like:

- `{{user_name}}`
- `{{user_dob}}`
- `{{user_email}}`
- `{{user_phone}}`
- `{{user_full_address}}`
- `{{supermarket_name}}`
- `{{sar_reference_number}}`
- `{{current_date}}`
- `{{original_sar_date}}`
- `{{reminder_14day_date}}`

Important: placeholder names are a **strict contract** — downstream render/assembly expects exact spelling. [Source](https://www.genspark.ai/api/files/s/9LwpP4dR)

### Reference scheme
- Original: `{{sar_reference_number}}`
- 14‑Day Reminder: `{{sar_reference_number}}-14`
- Final Notice: `{{sar_reference_number}}-7` [Source](https://www.genspark.ai/api/files/s/9LwpP4dR)

## Intended use

This repo is intended to be used as:
- a **public/open template commons** (for transparency and reuse), and/or
- a **source-of-truth** for automated systems that pull templates from GitHub and render them with user + controller data.

## Not legal advice (important)

These templates are provided for **informational and automation tooling purposes only** and do **not** constitute legal advice.
You are responsible for:
- verifying legal accuracy for your situation and jurisdiction,
- ensuring claims/requests are made in good faith,
- complying with applicable laws and guidance.

## License

**CC0 1.0 Universal (Public Domain Dedication).**

See [`LICENSE`](./LICENSE).


