# Charli's Bunny Life

A bunny companion game for a tablet. Everything is in `index.html`; the other files let it install as an app and work offline.

## Files
- `index.html` - the whole game
- `manifest.webmanifest` - app name, icon and full-screen setting
- `sw.js` - keeps the game working without internet
- `icon-180.png`, `icon-192.png`, `icon-512.png` - app icons

## Put it on GitHub Pages
1. Create a new repository on GitHub (for a free account it must be Public for Pages to work).
2. Upload all six files to the top level of the repository (Add file > Upload files) and commit.
3. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main` and folder to `/ (root)`. Save.
4. After a minute or two the page shows the address, in the form `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Install on the iPad
1. Open that address in Safari (it must be Safari).
2. Tap the Share button, then "Add to Home Screen", then "Add".
3. Open the game from the new Bunny Life icon. It runs full screen and works offline after the first open.

## Good to know
- The game saves on the iPad itself. The home-screen app keeps its own save, separate from Safari and from any other link the game was played on, so it starts with a new bunny.
- Deleting the home-screen icon, or clearing Safari website data, erases the save and the photos.
- To update the game: replace `index.html` in the repository and change the version name in `sw.js` (for example `bunny-life-v7`). The iPad picks up the new version the next time or two the app is opened with internet.
- Voice prompts use the iPad's own speech and need the ringer/volume on.
- A public repository means anyone with the address can open the game. It holds no personal information beyond the name in the title.
