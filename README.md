# Sticky Element
![][bower-badge] [![][bowerdeps-badge]][bowerdeps-url]

`sticky-element` is [sticky positioned](https://developer.mozilla.org/en/docs/Web/CSS/position#Sticky_positioning) container. It uses the [Stickyfill](https://github.com/wilddeer/stickyfill) `position: sticky` polyfill for cross-browser support.

### Installation and usage
Install with bower 

```sh
bower install --save sticky-element
```

Then link into your project

```html
<link rel="import" href="/bower_components/sticky-element/sticky-element.html">
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

### License

MIT © [Sean King](sean@seanking.org)

[bower-badge]: https://img.shields.io/bower/v/sticky-element.svg
[bowerlicense-badge]: https://img.shields.io/bower/l/sticky-element.svg
[bowerdeps-badge]: https://img.shields.io/gemnasium/seaneking/sticky-element.svg
[bowerdeps-url]: https://gemnasium.com/bower/sticky-element