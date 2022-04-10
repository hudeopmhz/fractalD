# Default button / Default link as button

The default form of a button, used for most cases. They are not impactful enought to represent the primary action in a container.

## For default button

```html
{% render '@base-button', {template: true} %}
```

---

```html
{% render '@base-button', {type: 'button', template: true} %}
```

> As semantic markup for button, Container should be strictly
>
> `<button> ... </button> or <input />`
>
> inside a
> `<form> ... </form>`

<br>

## For default link as button

```html
{% render '@base-button', {href: '#', template: true} %}
```

> As semantic markup for a link, Container should be strictly
>
> `<a> ... </a>`
>
> inside a body tag.

<br>

## Styling hooks

| Category | Styling Hook          |
| :------- | :-------------------- |
| type     | button, submit, reset |
| color    | [@color](/colors)     |

<br>
<br>
