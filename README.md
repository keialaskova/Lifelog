# LIFELOG v3.0 — Category Sticker Picker

This update is based on LIFELOG v2.9 and the user's uploaded `cute_bear_stickers_54_HD.zip`.

## Changes requested
- Removed the entire "Your Bubu & Dudu looks" card from Home.
- Removed the separate Bubu & Dudu outfit gallery section from Settings.
- Added a character-sticker selector directly inside every category card under Settings > Manage categories.
- Each category selector offers all 54 supplied stickers, clearly labeled by activity and character: Bubu (white), Dudu (brown), or Together.
- The selected sticker is saved on that category and becomes its icon artwork in the Bubu & Dudu theme.
- Added the same 54-sticker selector when creating a new category, with a live preview.
- Existing emoji icons remain available for non-Bubu themes.
- Existing category names, records, payments, wallets, and other data are preserved.
- Updated service-worker cache and precached all 54 sticker images.

## How to test
1. Export a LIFELOG backup from Settings > Backup & restore.
2. Extract this ZIP.
3. Upload the contents of `lifelog_v2` to the root of your GitHub Pages repository, replacing the previous files.
4. Open LIFELOG and select Settings > Appearance > Bubu & Dudu (Character Theme).
5. Under Settings > Manage categories, choose a Bubu, Dudu, or Together sticker for each category.
6. Return to Home. Each category card and its record form should show the sticker chosen for that category.
7. If the old version remains cached, close the tab and reopen the site after the service worker refreshes.

## Validation
- JavaScript syntax check passed.
- Service-worker syntax check passed.
- All 54 sticker PNGs are included and precached.
- Live GitHub Pages behavior still needs device testing.
