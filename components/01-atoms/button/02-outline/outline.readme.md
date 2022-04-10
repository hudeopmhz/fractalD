# Outline button / Outline link as button

The outline button form of a button, used for most cases. They are not impactful enought to represent the primary action in a container.

## For outline button

```html
{% render '@base-button', {template: true, outline: true} %}
```

---

```html
{% render '@base-button', {type: 'button', template: true, outline: true} %}
```

> As semantic markup for button, Container should be strictly
>
> `<button> ... </button> or <input />`
>
> inside a
> `<form> ... </form>`

<br>

## For outline link as button

```html
{% render '@base-button', {href: '#', type: 'button', template: true, outline:
true} %}
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
| outline-color | see [@color](/colors) | class     |

<br>
<br>
