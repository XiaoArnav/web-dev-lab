# Problem 10: Portfolio header and footer with advanced Flexbox

## Aim
To implement advanced Flexbox layout patterns including a three-zone navigation header, a multi-column footer, and a sticky footer technique.

## Concepts Covered
- Sticky footer layout using `display: flex`, `flex-direction: column`, and `min-height: 100vh` on `body` with `flex: 1` on `main`
- Three-zone header navigation using `justify-content: space-between` and `align-items: center`
- Multi-column footer layout using `flex-wrap: wrap` and `flex: 1`
- Media queries for collapsing header and footer columns on smaller screens

## Steps
1. Created `index.html` with a three-zone navigation bar, hero banner, main content section, and multi-column footer.
2. Added `styles.css` applying full-height column flex to keep the footer pinned to the bottom.
3. Styled the header and footer with flex distribution and added a responsive media query for mobile screens.
4. Verified layout behavior and footer pinning in the browser.
