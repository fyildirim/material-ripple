# Google Material Ripple Effect

These two files allow you to add Google's material ripple effect to any element you want!

This comes with two minified files so you can include it and use it immediately.

There's two sorts of ripple effects, the light effect and the dark effect.

## Ripple effect in action

### `ripple-effect ripple-light` on a `button`
![https://i.gyazo.com/c2e0191b4fbdff3ccd858419c83a7b0d.gif](https://i.gyazo.com/c2e0191b4fbdff3ccd858419c83a7b0d.gif)

### `ripple-effect` on a `button`
![https://i.gyazo.com/941613c1f341c2cd2180f7d9019160b7.gif](https://i.gyazo.com/941613c1f341c2cd2180f7d9019160b7.gif)

### `ripple-effect ripple-circle ripple-light` on a `span`
![https://i.gyazo.com/b7a2dbcc1c48e576f35717c89d1c5da4.gif](https://i.gyazo.com/b7a2dbcc1c48e576f35717c89d1c5da4.gif)

### `ripple-effect ripple-circle` on a `span`
![https://i.gyazo.com/668b166de7749abd34744ef1e555efc2.gif](https://i.gyazo.com/668b166de7749abd34744ef1e555efc2.gif)


## How to use?

Make sure you've got jQuery in your page first.

Add the following piece of code to your `<head>` element, make sure to change the path accordingly.
```html
<link rel="stylesheet" href="[[/path/to/]]ferhat-ripple.css">
```

Add the following piece of code all the way at the bottom of your `<body>` element. Make sure it comes after jQuery.
```html
<script src="[[path/to/]]ferhat-ripple.js"></script>
```

After all files have been included in your page, simply add `class="ripple-fx"` to use it!

You can also use `class="ripple-fx ripple-circle"` to make the ripple start from the center and expand from there on, like the following examples:
![https://i.gyazo.com/668b166de7749abd34744ef1e555efc2.gif](https://i.gyazo.com/668b166de7749abd34744ef1e555efc2.gif)
![https://i.gyazo.com/b7a2dbcc1c48e576f35717c89d1c5da4.gif](https://i.gyazo.com/b7a2dbcc1c48e576f35717c89d1c5da4.gif)

Don't want the dark ripple? Simply add `ripple-light` to make it a light ripple, so your `class` attribute should look like this: `class="ripple-fx ripple-circle ripple-light"` or `class="ripple-fx ripple-light"`

# Element you want to add ripples to requires `display: block;`?
Add `ripple-block` to the `class` attribute.