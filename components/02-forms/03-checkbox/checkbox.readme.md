# Checkbox

Browser default checkboxes are replaced with the help of **`.form-check`**, that improves the layout and behavior of their HTML elements, that provide greater customization and cross browser consistency.

**Checkboxes are for selecting one or several options in a list**

Structurally, our `<input>s` and `<label>s` are sibling elements as opposed to an `<input>` within a `<label>`. This is slightly more verbose as you must specify id and for attributes to relate the `<input>` and `<label>`. We use the sibling selector (~) for all our `<input>` states, like :checked or :disabled. When combined with the .form-check-label class, we can easily style the text for each item based on the `<input>`’s state.

Our checks use custom Bootstrap icons to indicate checked or indeterminate states.

```html
<div class="form-check">
  <label class="form-check-label" for="idToReferenceLabel">
    Default checkbox<input class="form-check-input" type="checkbox" value="" id="idToReferenceLabel">
  </label>
</div>
```
---
```html
<div class="form-check">
  <label class="form-check-label">
    Default checkbox<input class="form-check-input" type="checkbox" value="">
  </label>
</div>
```

## Inline
Group checkboxes or radios on the same horizontal row by adding `**.form-check-inline**` to any ``*.form-check.*``