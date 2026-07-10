# CSS Flexbox Notes

## Important Concepts & Tags
- `display: flex`: Activates flex container context.
- `flex-direction`: Sets primary axis (`row`, `column`).
- `justify-content`: Aligns items along the main axis.
- `align-items`: Aligns items along the cross axis.
- `flex-wrap`: Controls wrapping of child elements.

## Common Mistakes
- Trying to use `align-items` or `justify-content` on flex items instead of the flex parent container.
- Assuming flex axes are fixed (they rotate when `flex-direction` shifts to `column`).

## Interview Notes
- **What is the difference between main-axis and cross-axis in Flexbox?** The main axis is defined by `flex-direction` (row: horizontal, column: vertical). The cross axis is perpendicular to it.

## Practice Ideas
- Center a div perfectly horizontally and vertically using three lines of flexbox.
