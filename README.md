# heki.css
A simple responsive boilerplate to kickstart your project.

heki.css provides a minimal set of styles for a clean start at only *2.5kb gzipped*.
It is intentionally not a UI framework and a great start if you feel that you don't need all the functionality provided by a larger framework.

[Documentation](https://fdietz.github.io/heki.css/index.html)

## Motivation
* Using CSS variables (for example: --primary-color: blue)
  * Simplifies customizing of boilerplate
  * Offers easy themeing capabilities
  * Change via Javascript
* Consistenly using margin-bottom only (even in reset)
* Responsive font-size using a modular type scale
* It is just vanilla CSS, no compile step required

## Getting started

### Download
The easist way to get started is to download the [latest release](https://github.com/fdietz/heki.css/releases).


### heki.css is available via npm
```
$ npm install heki.css
```

### Add the stylesheet link tag in the head.

```
<html>
  <head>
    <link rel="stylesheet" href="//cdn.rawgit.com/fdietz/heki.css/master/dist/heki.min.css">
  </head>
  <body>
    <h1>Welcome to heki.css!</h1>
  </body>
</html>
```

## Browser Support
* Chrome latest
* Firefox latest
* Opera latest
* Safari latest
* Edge

You can use `heki.css` today if you can ignore Internet Explorer. Edge is fine though.

This mostly comes down to support for [CSS variables](http://caniuse.com/#feat=css-variables). If you need to support Internet Explorer consider using a Polyfill [myth](http://www.myth.io/) or similar. To makes things simpler for now, `heki.css` only uses css variables at the `:root` scope.
## Credit
Lot's of inspiration from minimal frameworks as for example [milligram](https://github.com/milligram/milligram) or [skeleton](http://getskeleton.com/).

The reset is based on [Bootstrap 4 Reboot](https://v4-alpha.getbootstrap.com/content/reboot/) and adapted to use CSS variables.

Awesome articles as for example [Locally scoped CSS variables: What, how, and why](https://una.im/local-css-vars/#💁) by Una Kravets.
