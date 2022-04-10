### Learn more about [@DefaultButton](/components/detail/default--default) behaviour, style and usecase.

<br>

# Button sizes / Sizes link as button

Fancy larger or smaller buttons? Add this class for additional sizes.

> ```
> .btn-lg or .btn-sm
> ```

## For button size

```html
{% render '@base-button', {template: true,size: true} %}
```

---

```html
{% render '@base-button', {type: 'button', template: true,size: true} %}
```

> As semantic markup for button, Container should be strictly
>
> `<button> ... </button> or <input />`
>
> inside a
> `<form> ... </form>`

<br>

## For sizes link as button

```html
{% render '@base-button', {href: '#', template: true, size: true} %}
```

> As semantic markup for a link, Container should be strictly
>
> `<a> ... </a>`
>
> inside a body tag.

<br>

## Styling hooks

| Category      | Styling Hook          | type      |
| :------------ | :-------------------- | :-------- |
| type          | button, submit, reset | attribute |
| outline color | [@color](/colors)     | class     |
| sizing        | .btn-lg, .btn-sm      | class     |

<br>
<br>
