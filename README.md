# MedTracker PWA

A personal medicine inventory tracker that installs on your phone like a native app.

## Files
- `index.html` — the app
- `manifest.json` — PWA config
- `sw.js` — service worker (offline support)
- `icon-192.svg` — app icon

## How to deploy (free, ~5 minutes)

### Option A: GitHub Pages
1. Create a free account at github.com
2. Create a new repository (e.g. `medtracker`)
3. Upload all four files to the repo
4. Go to Settings → Pages → set source to "main branch / root"
5. Your app will be live at `https://yourusername.github.io/medtracker`

### Option B: Netlify Drop
1. Go to netlify.com/drop
2. Drag the entire folder onto the page
3. You'll get a live URL instantly (e.g. `https://abc123.netlify.app`)
4. Optional: claim the site and rename the URL

## Installing on your phone

### iPhone (Safari)
1. Open the URL in Safari (must be Safari, not Chrome)
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap "Add"

### Android (Chrome)
1. Open the URL in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home Screen" or "Install app"
4. Tap "Add"

The app will appear on your home screen with its own icon and open fullscreen, just like a native app. Data is saved locally on your device.
