# Div & Span Notes

## Important Concepts & Tags
- `<div>`: A block-level container used to group elements.
- `<span>`: An inline-level container used for text styling.
- `<hr>`: A horizontal rule, representing a thematic break.
- `<sub>`: Renders subscript text (e.g., in H₂O).
- `<sup>`: Renders superscript text (e.g., in 2¹⁰).

## Common Mistakes
- Wrapping block-level elements inside inline span elements (invalid HTML structure).
- Using `<div>` or `<span>` excessively when semantic tags like `<section>`, `<article>`, or `<strong>` are more appropriate.

## Interview Notes
- **What is the core difference between block-level and inline elements?** Block-level elements always start on a new line and stretch to fill the full container width. Inline elements do not start on a new line and only occupy the width of their content.
- **Can inline elements have top/bottom margin or height?** No, inline elements ignore top/bottom margins and height settings. Convert them to `block` or `inline-block` to set these values.

## Practice Ideas
- Format a scientific report text snippet featuring chemical formulas (subscript) and math exponent notes (superscript).
