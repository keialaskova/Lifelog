# LIFELOG v2.0

LIFELOG is an installable, mobile-friendly personal life recorder for Android and iPhone browsers.

## What's new in v2.0
- Added app-wide text size controls (Small, Medium, Large, Extra Large).
- Added category renaming; existing records are updated when a category is renamed.
- Renamed category management is available in Settings.
- Improved Meals & Drinks form with a meal/drink description, meal type, optional cost, wallet, and notes.
- Added JSON backup restore with validation and a replacement confirmation.
- Added iOS Home Screen web-app metadata and Apple touch icon support.
- Updated service worker cache version so deployed clients can receive the new release.
- Existing localStorage key is retained to preserve current LIFELOG data on the same browser/device.

## Important limitations
- Data remains stored locally in each browser/device. Android and iPhone do not automatically sync records.
- Backup restore replaces the current browser's LIFELOG data; export a backup first.
- Memories/photo and video storage, scheduled reminders, PIN/biometric lock, cloud sync, and advanced monthly/weekly reports are not included in this release yet. They require additional development and testing.
- PWA installation requires HTTPS (GitHub Pages provides HTTPS). On iPhone, open the site in Safari, tap Share, then Add to Home Screen.

## Publish on GitHub Pages
Upload the contents of this folder to the root of the existing `Lifelog` repository, replacing the previous files. Commit the changes. Keep the repository's GitHub Pages setting on `main` and `/(root)`.
