# Mistress Predicament — Enquiry Form

Standalone lead capture form. Submissions are sent to the private CRM via a secure API endpoint.

## Images

Add the following to the `images/` folder before going live:

- `images/heels.jpg` — close-up lace-up heels shot (used as hero banner)
- `images/restraint.jpg` — leather restraint and heel detail (used as mid-page image break)

## GitHub Pages

Enable Pages in this repo's settings, set source to `main` branch / root.
The form will be live at `https://yes-mistress.github.io/predicament-form/`.

## CORS lock-down

Once live, add this environment variable to the Vercel project:

```
LEADS_FORM_ORIGIN=https://yes-mistress.github.io
```
