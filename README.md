# ZEROTRACE Security

Marketing landing page for a cybersecurity service (showcase / lead capture / newsletter), styled after Cyberpunk 2077's Arasaka look.

Single static file: `index.html`. No build step.

## Run locally
Open `index.html` in a browser.

## Deploy
GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.

## Before going live
- Forms are front-end only. Connect the lead form and newsletter to a real backend (Formspree, Mailchimp, ConvertKit, HubSpot…).
- Brand name, stats, prices, email and phone are placeholders.

## Edit with live reload
```
npm run dev
```
Opens http://localhost:5500 and reloads the browser every time you save `index.html`.

## Publish changes
```
git add -A
git commit -m "Describe your change"
git push
```
GitHub Pages redeploys automatically about a minute after each push.
