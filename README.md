# Sticky Element

`sticky-element` is [sticky positioned](https://developer.mozilla.org/en/docs/Web/CSS/position#Sticky_positioning) container. It uses the [Stickyfill](https://github.com/wilddeer/stickyfill) `position: sticky` polyfill for cross-browser support.

### Usage

Link into your project

```html
<link rel="import" href="[path]/sticky-element/sticky-element.html">
```

And use it wherever you want a sticky container

```html
<sticky-element>
    I'm sticky!
</sticky-element>
```

### Options
You can disable a sticky element any time with the `disabled` property

```html
<sticky-element disabled>
    I am no longer sticky :-(
</sticky-element>
```

--
