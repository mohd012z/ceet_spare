# ceet_spare
Ceet Spare

## Excel Database

The repository now includes an Excel-compatible database file:

- `data/CEET_Spares_Database.xls`

This file is in Excel 2003 XML `.xls` format so it can be opened in Microsoft Excel and imported into the CEET HTML app.

## Update Workflow (Phone + GitHub)

1. Update records in the CEET HTML app.
2. Export Excel from the app.
3. Save/rename the export as `data/CEET_Spares_Database.xls`.
4. Upload/replace the file in this repository from GitHub mobile/web.
5. Commit with a date-based message (example: `Update spares database 2026-07-12`).

Optional: keep daily history files under `data/history/`.

## Live System

The live app is now at:

- `index.html`

Enable GitHub Pages:

1. Open repository settings.
2. Go to Pages.
3. Source: Deploy from a branch.
4. Branch: `main` and folder `/ (root)`.
5. Save.

After Pages is enabled, open the site URL shown by GitHub Pages.

## Daily Update Routine (Phone)

1. Open live app.
2. Update spare items.
3. Use `☁ Export GitHub Sync`.
4. Upload these files into repository `data/`:
	- `CEET_Spares_Database.json`
	- `CEET_Spares_Database.xls`
	- optional dated file into `data/history/`
5. Commit in GitHub app/web.
6. In live app, press `☁ Load GitHub DB` to verify latest data.
