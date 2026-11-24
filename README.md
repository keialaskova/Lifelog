# LIFELOG v1

A browser-based personal life recorder/PWA starter project.

## Included in this first version
- Personalized first-launch name and time-based greeting
- Light, Dark and Original themes
- Clickable categories and quick recording forms
- Automatic current date/time, editable before saving
- Sleep and Wake Up as separate quick actions
- Meals and travel costs are optional
- Travel modes and optional destination
- Daily tasks, activities, health, social, learning and custom categories
- Money section with Cash, GCash, Bank, cash-in, cash-out and transfers
- Life History search, date/category filters, edit and delete for activity records
- Basic reports and JSON backup export
- PWA manifest and service worker for install/offline shell

## Important data note
This version stores records in the browser's local storage on the device. It does not sync between devices. Export a JSON backup regularly. Clearing browser data can erase records.

## Test locally
Open `index.html` in a modern browser. Some PWA features (install/offline service worker) require HTTPS or localhost.

## Publish with GitHub Pages
1. Create a new GitHub repository named `lifelog`.
2. Upload all files from this folder to the repository root.
3. In GitHub, open Settings → Pages.
4. Choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Open the Pages URL on your Android phone in Chrome.
6. Use Chrome's menu → Install app or Add to Home screen.

## Next build steps
- Improve wallet opening balances and transaction editing
- Add full monthly/weekly report filters
- Add Memories with IndexedDB attachment storage
- Add reminder controls and optional PIN/biometric protection
- Add backup import/restore and data validation
- Test on Android screen sizes and offline behavior
