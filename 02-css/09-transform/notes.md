# CSS Transform Notes

## Important Concepts & Tags

- `transform`: Shorthand for applying 2D or 3D transformations.
- `translate()`: Moves an element along the X and/or Y axis.
- `scale()`: Resizes an element up or down.
- `rotate()`: Rotates an element around a point.
- `skew()`: Slants an element along an axis.
- `transform-origin`: Sets the pivot point for the transform.

## Common Mistakes

- Forgetting that transforms do not affect surrounding layout space.
- Using too many transforms at once and making the UI feel unstable.
- Ignoring `transform-origin` when rotation or scaling looks off.

## Interview Notes

- **What is CSS transform used for?** It changes how an element is visually positioned, scaled, rotated, or skewed without changing the normal document flow.

## Practice Ideas

- Build a card that tilts slightly on hover using `rotate()` and `scale()`.
