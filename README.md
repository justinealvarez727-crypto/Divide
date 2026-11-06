# Divvy

Splitwise-style expense splitter. Static PWA: no build step, no backend.

## Deploy to Vercel
**CLI:** `npm i -g vercel && vercel --prod` (answer defaults; framework preset "Other").
**GitHub:** `git init && git add . && git commit -m init`, push to a repo, then import it at vercel.com/new. Leave build and output settings empty.

## Notes
- Data and receipt photos live on each device (localStorage + IndexedDB). Use Account > Back up to move data between devices.
- On a phone, open the deployed URL and choose Add to Home Screen to install.
