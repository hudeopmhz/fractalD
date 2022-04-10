### Learn more about [@DefaultButton](/components/detail/default--default) behaviour, style and usecase.

<br>

# Alignment button / Alignment link as button

Button alignment.

## For button alignment

```html
{% render '@base-button', {template: true, align: true} %}
```

---

```html
{% render '@base-button', {type: 'button', template: true, align: true} %}
```

> As semantic markup for button, Container should be strictly
>
> `<button> ... </button> or <input />`
>
> inside a
> `<form> ... </form>`

<br>

## For link as button alignment

```html
{% render '@base-button', {href: '#', template: true, align: true} %}
```

> As semantic markup for a link, Container should be strictly
>
> `<a> ... </a>`
>
> inside a body tag.

<br>

## Styling hooks

| Category      | Styling Hook                      | type      |
| :------------ | :-------------------------------- | :-------- |
| type          | button, submit, reset             | attribute |
| outline-color | see [@color](/colors)             | class     |
| align         | text-start, text-center, text-end | class     |

<br>
<br>
