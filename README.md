# Planner

A planner app with nested checklists, timers, templates, incoming orders, a board view and a done log. It installs on Android or iPhone from the browser, works offline, and keeps all data on the phone.

## Put it online with GitHub Pages (free)

1. Sign in at github.com and create a new **public** repository, for example `planner`.
2. On the repository page, choose **Add file → Upload files**. Drag in everything from this folder (index.html, sw.js, manifest.webmanifest, README.md and the `icons` and `fonts` folders), then tap **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, the branch to **main**, the folder to **/ (root)**, and tap **Save**.
4. After a minute or two, the app is live at `https://YOUR-USERNAME.github.io/planner/`.

## Install it on a phone

- **Android (Chrome):** open the link, then tap ⋮ → **Install app** (or **Add to Home screen**). You can also use the "Install Planner as an app" button in **Backup & app** at the bottom of the All tab.
- **iPhone (Safari):** open the link, tap Share → **Add to Home Screen**.

## Your data

Everything is saved on the phone. To move to a new phone, or just to stay safe, open **Backup & app** at the bottom of the All tab and tap **Save backup file**. On the new phone, tap **Restore from backup** and pick that file.

## Releasing an update

Replace the changed files in the repository, and in `sw.js` change the `VERSION` line (for example `planner-1.0` → `planner-1.1`). Installed apps then show "A new version of Planner is ready" with a Refresh button. Saved data isn't touched by updates.

## Credits

Heading font: Bricolage Grotesque, SIL Open Font License (see fonts/OFL.txt). Drag and drop: SortableJS (MIT), loaded from cdnjs and cached for offline use.
