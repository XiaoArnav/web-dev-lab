# Problem 12: Portfolio projects grid with advanced CSS Grid

## Aim
To create a portfolio projects grid using advanced CSS Grid techniques including auto-fit columns and spanning featured cards.

## Concepts Covered
- `repeat(auto-fit, minmax(280px, 1fr))` for fluid and responsive grid columns
- `grid-column: span 2` to highlight a featured project card across two columns
- Internal grid structuring (`grid-template-columns: 1fr 1fr`) on the featured card
- Responsive fallback via media queries to reset spanning cards on smaller screens

## Steps
1. Created `index.html` with a portfolio header and project cards including a featured project showcase.
2. Added `styles.css` defining an auto-fitting grid container with gap spacing.
3. Configured the featured card to span two columns with an internal two-column layout.
4. Added media queries to ensure smooth single-column stacking on mobile viewports.
