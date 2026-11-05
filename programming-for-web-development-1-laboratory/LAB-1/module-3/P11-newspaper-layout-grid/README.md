# Problem 11: Newspaper-style three-column layout with CSS Grid

## Aim
To build a classic three-column newspaper layout using CSS Grid and responsive column adaptation.

## Concepts Covered
- `display: grid` with `grid-template-columns: 1fr 2fr 1fr` for asymmetric three-column layout
- `gap` property for consistent spacing between columns without margin hacks
- Editorial styling with masthead typography, issue meta bar, and vertical column dividers
- `@media (max-width: 768px)` media query to stack columns on mobile screens

## Steps
1. Created `index.html` with a masthead header, three article column sections, and a footer.
2. Added `styles.css` using CSS Grid to create a 3-column layout with a wider center column for the lead story.
3. Added column border separators and responsive rules to collapse into a single column on mobile screens.
4. Verified layout rendering and column responsiveness in the browser.
