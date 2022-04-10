### Learn more about [@DefaultButton](/components/detail/@default--default) behaviour, style and usecase.

<br>

# Disabled button / Disabled link as button

Make buttons look inactive by adding the disabled boolean attribute to any button element. Disabled buttons have pointer-events: none applied to, preventing hover and active states from triggering.

> ```
> disabled
> ```

## For disabled button state

```html
{% render '@base-button', {template: true, state: 'disabled'} %}
```

---

```html
{% render '@base-button', {type: 'button', template: true, state: 'disabled'} %}
```

> As semantic markup for button, Container should be strictly
>
> `<button> ... </button> or <input />`
>
> inside a
> `<form> ... </form>`

<br>

## For disable link as button state

```html
{% render '@base-button', {href: '#', template: true, class: ' disabled'} %}
```

> As semantic markup for a link, Container should be strictly
>
> `<a> ... </a>`
>
> inside a body tag.

<br>

## Styling hooks

| Category      | Styling Hook          | type                                    |
| :------------ | :-------------------- | :-------------------------------------- |
| type          | button, submit, reset | attribute                               |
| outline-color | see [@color](/colors) | class                                   |
| state         | disabled / .disabled  | button = attribute / anchor tag = class |

<br>
<br>
