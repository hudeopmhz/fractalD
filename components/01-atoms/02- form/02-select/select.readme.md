# Select

Custom **`<select>`** menus need only a custom class, **`.form-select`** to trigger the custom styles. Custom styles are limited to the **`<select>’s`** initial appearance and cannot modify the **`<option>s`** due to browser limitations.

```html
<select class="form-select" aria-label="select">
    <option value="Open this select menu" selected>Open this select menu</option>
    <option value="One">One</option>
    <option value="Two">Two</option>1
    <option value="Three">Three</option>
</select>
```

## Sizing
You may also choose from **small** and **large** custom selects to match our similarly sized text inputs by adding class **`form-select-sm`** and **`form-select-lg`** respectively.

> ```html
> <select class="form-select form-select-{size}" aria-label="select">...</select>
> ```

## Multiple
On Select, The `multiple` (default) or `size` (specific size) attributes are supported.

> ```html
> <select class="form-select multiple" aria-label="select">...</select>
> ```

or

> ```html
> <select class="form-select size="{multipleSize}" aria-label="select">...</select>
> ```

## Disabled
Add the `disabled` boolean attribute on a **select or any form element** to give it a grayed out appearance and remove pointer events.

> ```html
> <select class="form-select disabled aria-label="select">...</select>
> ```

or

> ```html
> <input type="{type}" disabled>...</input>
> ```


## Styling hooks

| Category      | Styling Hook          | type      |
| :------------ | :-------------------- | :-------- |
| size          | form-select-lg, form-select-sm | class |
| multipleSize | number | value |