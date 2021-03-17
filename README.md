# @hexsoftstudio/theme-default

[![npm (scoped)](https://img.shields.io/npm/v/@hexsoftstudio/theme-default.svg)](https://github.com/hexsoftstudio/theme-default)

A scss package with using plain or Bulma extension

### Install ###
```
$ npm install @hexsoftstudio/theme-default
```

```
in nuxt.config.js, add

css: [
    '@hexsoftstudio/theme-default/styles/bulma.css'
],

...
component: true,

```

```
or import css

@import "node_modules/@hexsoftstudio/theme-default/styles/bulma.css"
@import "node_modules/@hexsoftstudio/theme-default/styles/main.css"
```

### Usage ###

### Avatar

```html
<section>
    <div class="avatar-container">
        <div class="avatar">
        <img
            src="realtor-1.jpeg"
            alt="Avatar 1"
            class="avatar__photo"
        />
        <span class="avatar__notification">12</span>
        <img
            src="realtor-2.jpeg"
            alt="Avatar 2"
            class="avatar__photo avatar__photo--border"
        />
        <span class="avatar__notification">21</span>
        <img
            src="realtor-3.jpeg"
            alt="Avatar 3"
            class="avatar__photo"
        />
        <span class="avatar__notification">53</span>
        </div>
    </div>
</section>
```

### Buttons

```html
<section>
    <div class="container">
        <button class="button-primary">Primary</button>
        <button class="button-red button-red--rounded">Secondary</button>
        <button class="button-custom button-custom--rounded">Custom</button>
        <button class="button-simple">Simple Button</button>
    </div>
</section>
```

### Footer

```html
<footer>
    <div class="footer__copyright">Copyright (c) 2021</div>
</footer>
```

### Ratings

```html
<section>
    <div id="ratings">
        <svg class="ratings__star">
            <use xlink:href="icons/sprite.svg#icon-star"></use>
        </svg>
        <svg class="ratings__star">
            <use xlink:href="icons/sprite.svg#icon-star"></use>
        </svg>
        <svg class="ratings__star">
            <use xlink:href="icons/sprite.svg#icon-star"></use>
        </svg>
        <svg class="ratings__star">
            <use xlink:href="icons/sprite.svg#icon-star"></use>
        </svg>
        <svg class="ratings__star">
            <use xlink:href="icons/sprite.svg#icon-star-outlined"></use>
        </svg>
    </div>
</section>
```

For examples see [https://hexsoftstudio.github.io/demo/](https://hexsoftstudio.github.io/demo/)
