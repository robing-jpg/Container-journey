# A Container Journey

Interactive onboarding animation that follows a shipping container from the shipper's premises to the consignee and back.

**Version 0.1 (pilot):** engine + step 2 "Stuffing, sealing & VGM", levels 1 and 2, neutral branding.

## Run it
Open `index.html` in any modern browser. It is a single self-contained file: no build step, no external dependencies, works offline.

## Deploy
Deployed on Vercel straight from this repository (framework preset: Other, no build command). Every push to `main` triggers a new deployment.

## Edit
- **Branding:** the `CONFIG` block at the top of the script (company name, logo text, colours, illustrative tariff).
- **Content:** the JSON block `content-data` (texts per level, questions, Incoterms, glossary, verification list).
- **Engine:** the last script block. No need to touch it to change content.

## Content status
Items marked **[TO VERIFY]** have not yet been checked against their sources. Open the in-app "Verification list" for the full list with references (IMO, ICC, carrier tariffs…). Set `showVerifyMarkers: false` in `CONFIG` once everything is validated.

Built with AI (Claude) for an AI course project.
