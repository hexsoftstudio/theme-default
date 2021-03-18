# @hexsoftstudio/theme-default

[![npm (scoped)](https://img.shields.io/npm/v/@hexsoftstudio/theme-default.svg)](https://github.com/hexsoftstudio/theme-default)

A scss package using plain or Bulma extension

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

examples:
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

### Cart

```html
<section>
    <div class="cart">
      <div class="cart__image">
        <svg class="cart__image--shopping-cart">
          <use xlink:href="./demo/icons/sprite.svg#icon-shopping-cart"></use>
        </svg>
      </div>
      <div class="cart__label">
        <span class="cart__label--count">
          10
        </span>
      </div>
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

### Social Media

```html
<section>
    <div class="socialmedia">
      <h1 class="socialmedia__title">Follow us on</h1>
      <svg class="socialmedia__facebook">
        <use xlink:href="./icons/sprite.svg#icon-facebook"></use>
      </svg>
      <svg class="socialmedia__google">
        <use xlink:href="./icons/sprite.svg#icon-google"></use>
      </svg>
      <svg class="socialmedia__instagram">
        <use xlink:href="./icons/sprite.svg#icon-instagram"></use>
      </svg>
      <svg class="socialmedia__linkedin">
        <use xlink:href="./icons/sprite.svg#icon-linkedin"></use>
      </svg>
      <svg class="socialmedia__pinterest">
        <use xlink:href="./icons/sprite.svg#icon-pinterest"></use>
      </svg>
      <svg class="socialmedia__twitter">
        <use xlink:href="./icons/sprite.svg#icon-twitter"></use>
      </svg>
      <svg class="socialmedia__vimeo">
        <use xlink:href="./icons/sprite.svg#icon-vimeo"></use>
      </svg>
      <svg class="socialmedia__youtube">
        <use xlink:href="./icons/sprite.svg#icon-youtube"></use>
      </svg>
    </div>
</section>
```

### User

```html
<section>
    <div class="user">
      <svg class="user__image">
        <use xlink:href="./icons/sprite.svg#icon-user"></use>
      </svg>
      <svg class="user__logout">
        <use xlink:href="./icons/sprite.svg#icon-lock"></use>
      </svg>
      <span class="user__logout--register">Register</span>
    </div>
  </section>

  <section>
    <div class="user">
      <img
        src="./img/realtor-3.jpeg"
        alt="Avatar 3"
        class="user__image user__image--bordered"
      />
      <svg class="user__login">
        <use xlink:href="./icons/sprite.svg#icon-lock-open"></use>
      </svg>
      <span class="user__login--name">John S.</span>
    </div>
</section>
```

For examples see [https://hexsoftstudio.github.io/demo/](https://hexsoftstudio.github.io/demo/)
