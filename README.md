# Clam Bake Drawing — Mitchell's Fish Market $100 (COREy HCM)

A QR-scannable entry form for a free drawing to win a **$100 gift card to
Mitchell's Fish Market**. Guests scan a QR code, fill out name / email / phone
on their phone, and each entry saves to a Google Sheet. Presented by CORE HCM.

_Original artwork; "Mitchell's Fish Market" names the prize only. Not
affiliated with or endorsed by them._

## Hosting
- Live form: **https://arkeo777.github.io/clam-bake/** (GitHub Pages, `main` / root)
- Entries save via the Google Apps Script endpoint set in `index.html` (`ENDPOINT`),
  which appends rows to the Google Sheet: `Timestamp | Name | Email | Phone`.
- `apps-script.gs` is the backend script (already deployed).

This project is intentionally in its **own repository** so it runs independently
of any other GitHub Pages site on this account.
