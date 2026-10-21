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

## Data and privacy
Inventory, notes and checklist data are saved in browser local storage on the device where they are entered. Use **Bike profile → Export backup** regularly. Browser data does not automatically sync between devices. Photos are stored in the browser as resized images and may use significant local storage.

## Manual and safety
The supplied reference is a KYMCO Venox 250 Service Manual dated March 2002. This initial app contains a chapter topic index, not the PDF itself. The manual publication date does not establish the motorcycle's model year. Verify the VIN, engine identity and exact variant before relying on torque values or repair procedures. Brakes, steering, suspension, fuel and engine internals require correct model-specific specifications.

MotoVault is an organizational tool, not a substitute for the correct service manual or qualified mechanical work.

Deployment check: latest push should trigger the GitHub Pages workflow.