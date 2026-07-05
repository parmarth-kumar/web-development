# HTML Forms Notes

## Important Concepts & Tags
- `<form>`: Parent element specifying where data is sent (`action`) and method (`GET`/`POST`).
- `<input>`: Gathers user data via types like `text`, `email`, `password`, `radio`, `checkbox`.
- `<label>`: Implements accessibility descriptive text associated via the `for` attribute.
- `<textarea>`: Text box supporting multiline inputs.
- `<select>` & `<option>`: Renders dropdown select lists.
- `<button>`: Submits or resets form data.

## Common Mistakes
- Forgetting the `for` attribute on a `<label>` or naming it incorrectly (must match the input's `id`).
- Omitting the `name` attribute on inputs (causes form fields to be ignored on submission).
- Using the wrong input `type` (e.g. `text` instead of `email` which skips validation).

## Interview Notes
- **What is the difference between GET and POST form methods?** GET appends the form data directly to the URL query string (insecure, limited length, bookmarkable). POST sends data inside the HTTP request body (secure, holds large payloads, not bookmarkable).
- **Why is the for attribute inside labels essential?** It links the label to its corresponding input. This increases click target size (clicking the label focuses the input) and enables screen readers to state the input name.

## Practice Ideas
- Build a complex multi-step checkout form incorporating shipping and card details.
