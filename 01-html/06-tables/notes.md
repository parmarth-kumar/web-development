# HTML Tables Notes

## Important Concepts & Tags
- `<table>`: Declares the table structure.
- `<tr>`: Table row container.
- `<th>`: Table header cell (bold, centered text by default).
- `<td>`: Table data cell.
- `colspan`: Merges cells across columns.
- `rowspan`: Merges cells across rows.
- `<caption>`: Describes the table's contents.

## Common Mistakes
- Incorrect math/accounting when merging rows or columns using `rowspan` and `colspan` (results in broken/misaligned layout).
- Omitting `<tr>` tags and nesting `<td>` or `<th>` directly under the `<table>` element.

## Interview Notes
- **How does rowspan differ from colspan?** `rowspan` merges cells vertically (combining rows), whereas `colspan` merges cells horizontally (combining columns).

## Practice Ideas
- Create a complex weekly course schedule template featuring merged lecture blocks.
