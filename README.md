# Atlas Explorers

A kid-friendly world geography game: flags, capitals, country shapes, mystery clues, languages, animals, map games, landmarks and neighbours, with passport stamps, trophies, gemstones and leaderboards.

Once it's published, it installs on phones and tablets like an app and works offline.

## Files

| File | What it does |
|---|---|
| `index.html` | The game |
| `manifest.json` | The app's name, colors and icons |
| `sw.js` | Lets the game work offline |
| `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon-32.png`, `icon.svg` | Home-screen icons |

All 8 files must sit together at the top level of the repository, not inside a folder.

## Publish it with GitHub Pages (one time)

1. Create a free account at **github.com**. A personal email works best; school accounts sometimes block publishing.
2. Click **+** (top right) → **New repository**.
   - Repository name: `atlas-explorers`
   - Choose **Public** (free GitHub Pages sites must be public)
   - Click **Create repository**.
3. On the new repository page, click **uploading an existing file** (or **Add file → Upload files**).
4. Select **all 8 files** and drag them into the page. Drag the files themselves, not the folder they're in.
5. Click **Commit changes**.
6. Go to **Settings** (top of the repository) → **Pages** (left side).
7. Under **Build and deployment → Source**, choose **Deploy from a branch**. Under **Branch**, choose **main** and **/ (root)**, then click **Save**.
8. Wait 1–2 minutes, then refresh the Pages settings page. It will show your address:
   `https://YOUR-USERNAME.github.io/atlas-explorers/`

## Install it on a phone

- **Android:** open the address in **Chrome** → **⋮** → **Install app** → **Install**.
- **iPhone/iPad:** open it in **Safari** → **Share** → **Add to Home Screen** → **Add**.
- Open the game once from the new icon while online. After that it works offline.

## Updating the game later

1. In the repository, click **Add file → Upload files**.
2. Drag in the new files with exactly the same names. They replace the old ones.
3. Click **Commit changes**. The site updates in about a minute.
4. On each device, open the game while online, close it, and open it again.

Scores, stamps and trophies are saved on each device and are kept when the game updates.
