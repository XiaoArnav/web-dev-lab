# Problem 8: Sticky navbar and card overlay using CSS positioning

## Aim
To implement a sticky navigation bar and create multiple card overlay effects using CSS positioning techniques.

## Concepts Covered
- `position: sticky` and `top: 0` for keeping the navbar pinned during scroll
- `position: relative` on card containers to establish positioning context
- `position: absolute` for corner badges, hover overlays, and bottom caption banners
- `z-index` to maintain proper stacking layer hierarchy

## Steps
1. Created `index.html` with a top navigation bar, hero section, and project cards demonstrating badge, hover, and banner overlays.
2. Added `styles.css` applying `position: sticky` to the navbar so it remains fixed while scrolling.
3. Applied `position: relative` to `.card-image-box` and positioned `.badge`, `.card-overlay`, and `.bottom-banner` with `position: absolute`.
4. Verified sticky scrolling behavior and hover transitions in the browser.
