# Bheki Ndlovu Steelworks — website

Static one-page site. No build step: `index.html` plus `images/`.

## Before launch
Edit the `data-*` attributes on `<body>` in `index.html`:

| Attribute | What |
|---|---|
| `data-phone` | Display phone number, e.g. `+27 82 000 0000` |
| `data-whatsapp` | WhatsApp number, digits only with country code, e.g. `27820000000` |
| `data-email` | Email address |
| `data-area` | Service area wording, e.g. `Johannesburg West` |

Every call, WhatsApp and email link on the page reads from these.

Also replace the three placeholder testimonials in the "What customers say" section, or delete that section.

## Images
Generated with Higgsfield (GPT Image 2.5) from Bheki's reference portrait. `images/manifest.json` lists the source URLs; pushing a changed manifest re-runs `.github/workflows/fetch-site-images.yml`, which downloads, converts to WebP and commits the files. `preview-*.jpg` files are small review copies and can be deleted before deploy.

## Deploy
Vercel: import the repo, set the root directory to `sites/bheki-steelworks`, framework "Other". No environment variables needed.
