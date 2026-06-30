# HTML Lists Notes

## Important Concepts & Tags
- `<ul>`: Declares an unordered list (bullet points).
- `<ol>`: Declares an ordered list (numbered/lettered items).
- `<li>`: Represents a single list item within an ordered or unordered list.
- `type`: Attribute for `<ol>` (e.g. `type="a"` or `type="I"`) to change list markers.

## Common Mistakes
- Nesting lists directly inside parent list containers without wrapping them inside a `<li>` tag.
- Using unordered lists for content that needs sequential steps (like recipes).

## Interview Notes
- **How do you nest lists correctly in HTML?** A nested list must be placed inside a list item (`<li>`) of the parent list, not directly under the `<ul>` or `<ol>` elements.
- **Can we customize the starting number of an ordered list?** Yes, by using the `start` attribute on the `<ol>` tag (e.g., `<ol start="5">`).

## Practice Ideas
- Build a nested grocery list grouped by department (e.g. Produce, Dairy).
