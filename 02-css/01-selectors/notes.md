# CSS Selectors Notes

## Important Concepts & Tags
- Universal selector (`*`): Targets all tags.
- Type selector (`h1`, `p`): Targets elements by tag name.
- Class selector (`.classname`): Targets elements sharing a class name.
- ID selector (`#idname`): Targets a single unique element with a specific ID.
- Descendant combinator (`div p`): Targets paragraphs nested inside divs.
- Pseudo-classes (`:hover`, `:checked`): Applies styles on interactions/states.
- Pseudo-elements (`::first-letter`): Styles specific sub-parts of text.

## Common Mistakes
- Forgetting to write the dot (`.`) for class selectors or the hash (`#`) for ID selectors in the CSS file.
- Overusing ID selectors for general styling, leading to high specificity conflicts.

## Interview Notes
- **What is Selector Specificity in CSS?** It is the weight system browsers use to decide which CSS rule takes priority. Inline styles win over IDs, IDs win over classes/pseudo-classes, and classes win over tag/element selectors.
- **How does a descendant selector (space) differ from a child selector (>) ?** A descendant selector (`A B`) selects all B elements inside A at any level. A child selector (`A > B`) only selects B elements that are direct children of A.

## Practice Ideas
- Design a custom navigation card styled dynamically on hover using pseudo-classes.
