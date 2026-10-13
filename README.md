# UseFirst – Working Web App

A working prototype of **UseFirst: Smart Household Consumption Prioritization and Replenishment System**.
Everything is in one file (`index.html`), so there is nothing to install or build.

## What it does
- Sign up, sign in, create a household or join one with a code (roles: Home Manager, Household Member, Viewer)
- Inventory with barcode lookup (sample catalog), quantity, unit, place, expiry date and low-stock level
- Use-First list ranked by earliest expiry (FEFO), with recipe ideas for food that is about to expire
- Alerts for expired, expiring soon, low and out-of-stock items
- Record use or waste; item history is kept
- Smart shopping list built from stock levels and your real usage; finished items are added automatically
- Reports: weekly use vs waste, expiry outlook, most wasted items, typical weekly use
- Household page: members and roles, alert settings, activity log

## Try it quickly
Create an account, create a household, then press **Load sample data**.
Sample barcodes: `8900000000011` (Milk), `8900000000059` (Eggs), `8900000000103` (Tomato).

## Publish on GitHub Pages
1. Create a public repository, for example `usefirst`.
2. Upload `index.html` (and this README) to the top level.
3. Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Open `https://YOUR-USERNAME.github.io/usefirst/` after about a minute.

## Notes
- Data is saved in the browser (localStorage). It is private to each browser and device.
- Passwords are salted and hashed in the browser. This is fine for a prototype, but a real
  deployment needs a server and database (see "next steps" in the case study).
