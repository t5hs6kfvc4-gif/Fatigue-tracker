# Fatigue Tracker PWA

This is a small installable web app for iPhone.

## What it records
- 11:00 fatigue (0–10)
- 21:00 fatigue (0–10)
- CTL
- Number of beers
- Previous night's sleep duration
- Training notes
- History and simple 30-day charts
- JSON backup and CSV export

All data is stored locally in Safari on the iPhone.

## Easiest way to put it on your iPhone

A PWA needs to be opened from a normal HTTPS website before iPhone can install it cleanly.

### Option A: GitHub Pages (free)
1. Create a free GitHub account if needed.
2. Create a new repository called `fatigue-tracker`.
3. Upload all files from this folder.
4. In the repository, open Settings > Pages.
5. Under "Build and deployment", choose "Deploy from a branch".
6. Select the `main` branch and `/ (root)`, then Save.
7. GitHub will show the HTTPS address for the site after deployment.
8. Open that address in Safari on your iPhone.
9. Tap Share > Add to Home Screen > Add.

### Option B
Any simple static web host that provides HTTPS will work (Netlify, Cloudflare Pages, etc.).

## Notes
- The app works offline after the first successful load.
- Deleting Safari website data can delete the locally stored records, so use Export JSON Backup periodically.
- Browser PWAs cannot reliably schedule exact local notifications on iPhone. Keep the existing ChatGPT 11:00 and 21:00 reminders.
