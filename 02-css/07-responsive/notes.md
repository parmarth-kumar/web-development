# Responsive Design Notes

## Important Concepts & Tags
- `@media`: Declares style rules matching screen breakpoints.
- `min-width`: Declares styles targetting mobile up.
- `max-width`: Declares styles targetting desktop down.

## Common Mistakes
- Using fixed pixel widths (`width: 960px`) instead of fluid percentages/relative values (`width: 100%; max-width: 960px`).
- Forgetting to verify layout scaling across different viewport widths.

## Interview Notes
- **What is Mobile-First Responsive Design?** Mobile-first design starts by styling pages for the smallest viewports first. Media queries (using `min-width`) are then added to scale up the layout as screen size increases.

## Practice Ideas
- Implement a media query checking color shifting across mobile and desktop browser windows.
