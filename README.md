# MotoVault — Venox Workshop

Mobile-first workshop companion for tracking motorcycle dismantling and rebuilding.

## Current features
- Parts inventory: part name, category, quantity, storage bin, original location, part number, condition, notes and optional photo.
- Searchable parts list.
- Custom storage bin labels.
- Dismantling/rebuild task checklist with progress.
- Workshop notes and measurements.
- Bike profile with unconfirmed year/version fields.
- JSON export/import backup.
- Installable PWA manifest and mobile-friendly layout.
- Automatic GitHub Pages deployment using GitHub Actions.

## Deploy
The `.github/workflows/deploy.yml` workflow deploys the static app whenever code is pushed to `main`. In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions** if it is not already selected.

If the site shows a 404, open the repository's **Actions** tab and check the latest **Deploy MotoVault to GitHub Pages** run. A new deployment trigger was pushed on 21 October 2026. The app URL is https://trevor3002.github.io/MOTOVAULT-VENOX/.

## Install on iPhone
1. Open https://trevor3002.github.io/MOTOVAULT-VENOX/ in Safari after the Pages deployment succeeds.
2. Tap Share.
3. Choose **Add to Home Screen**, then tap **Add**.

## Data and privacy
Inventory, notes and checklist data are saved in browser local storage on the device where they are entered. Use **Bike profile → Export backup** regularly. Browser data does not automatically sync between devices. Photos are stored in the browser as resized images and may use significant local storage.

## Manual and safety
The Manual screen includes a direct link to the complete KYMCO Venox 250 service manual PDF hosted by KYMCO. If an older message appears on an iPhone, refresh the page after deployment. Verify the motorcycle's exact model year/version before applying specifications, and use a qualified mechanic for safety-critical work.
