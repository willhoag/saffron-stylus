# Saffron-Stylus

> A simple Stylus mixin library for animations and transitions.

Saffron-stylus is a collection of Stylus mixins and helpers that make adding CSS3 animations and transitions much simpler. Just include a mixin in your Stylus declaration, then set any configuration using variables and mixin parameters. This is a port of the original [colindresj/saffron](https://github.com/colindresj/saffron) sass mixin library, minus the vendor prefixing. Any prefixing should now be handled with [Autoprefixer](https://github.com/postcss/autoprefixer) or something similar.

[![NPM](https://nodei.co/npm/saffron-stylus.png)](https://nodei.co/npm/saffron-stylus/)

## Installation
```bash
npm install saffron-stylus --save
```

## Manual Installation
Download or clone the project repo from GitHub. Copy the `saffron-stylus` folder and paste into your `styles` folder (or whatever you call it). You won't need any of the other directories or files.

## Usage
```stylus
// import the whole library
@import "saffron-stylus/styles"

// or just the mixins you want
@import "saffron-stylus/styles/in-place/hover"

.hover {
  hover() // hover(5s, 0s, none, infinite, ease-in-out)
}
```

## Browser Support
Saffron-stylus uses CSS3 transform, keyframes, animations and transitions, so it's really only for modern browsers. Visit http://caniuse.com/ for a clear idea of CSS3 browser support. For vendor prefixes, use [Autoprefixer](https://github.com/postcss/autoprefixer), or something similar.

## License
MIT
