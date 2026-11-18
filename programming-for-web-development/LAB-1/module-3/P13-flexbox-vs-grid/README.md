# Problem 13: Choosing between Flexbox and Grid for a shared layout

## Aim
To compare one-dimensional Flexbox and two-dimensional CSS Grid layouts using a shared card component and understand when to choose each system.

## Concepts Covered
- One-dimensional layout with Flexbox (`flex-wrap: wrap; flex: 1 1 200px`) where items wrap and stretch to fill available row space
- Two-dimensional layout with CSS Grid (`grid-template-columns: repeat(3, 1fr)`) where items stay locked in strict row and column tracks
- Layout selection criteria: Flexbox for components and navigation, Grid for overall page structures and rigid alignments
- Media queries for responsive stacking on smaller screens

## Steps
1. Created `index.html` with side-by-side comparison sections demonstrating the same cards in Flexbox and Grid.
2. Added `styles.css` styling the flex container to show content-driven wrapping and stretching.
3. Styled the grid container to show consistent 2D track alignment.
4. Added a summary comparison section outlining practical guidelines for choosing between Flexbox and Grid.
