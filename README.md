# Talika Notes

Table-first quick notes for Android. Open the app, tap a cell, type. Enter jumps to the next cell.

Exports to PDF, Word (.docx), Excel (.xlsx), CSV and a .json backup. Works offline.

## Put it online with GitHub Pages

1. On github.com, create a new repository, for example `talika-notes` (Public).
2. Open the repository, tap **Add file → Upload files**, and upload everything from this zip
   (`index.html`, `manifest.json`, `sw.js`, `.nojekyll`, `README.md` and the `icons` folder).
   Keep the `icons` folder as a folder.
3. Go to **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://<your-username>.github.io/talika-notes/`

## Install it on the phone

1. Open that link in **Chrome** on the phone.
2. Tap **⋮ → Install app** (or **Add to Home screen → Install**).
3. Talika Notes now opens from its own icon, full screen, with no browser bar, and works without internet.

## Updating later

1. Upload the new `index.html` (replace the old one).
2. Open `sw.js` on GitHub, change `VERSION = 'talika-v1'` to `'talika-v2'` (then v3, and so on), and commit.
3. Open the app twice on the phone. The first open downloads the update, the second shows it.

Your notes are not affected by updates. They stay on the phone.

## Keep your notes safe

Notes are stored only on the phone, inside the installed app.
Use **Notes list → Backup → Backup all notes** now and then, and keep the file in Google Drive.
Uninstalling the app or clearing Chrome's site data deletes the notes on the phone.
