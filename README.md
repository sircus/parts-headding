# sircus-tools-align-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-align-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-align-responsive)

> A responsive align tools Module for Sircus.

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-align-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-align-responsive";
/*
@import "sircus-tools-align-responsive/lib/sm";
@import "sircus-tools-align-responsive/lib/md";
@import "sircus-tools-align-responsive/lib/lg";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-align-responsive/converted";
// @import "./node_modules/sircus-tools-align-responsive/scss/sm";
// @import "./node_modules/sircus-tools-align-responsive/scss/md";
// @import "./node_modules/sircus-tools-align-responsive/scss/lg";
```


> html

```html
/* text-align */
<p class="t-sm-alignLeft"></p>
<p class="t-sm-alignRight"></p>
<p class="t-sm-alignCenter"></p>
<p class="t-sm-alignJustify"></p>
/* vertical-align */
<p class="t-sm-alignTop"></p>
<p class="t-sm-alignMiddle"></p>
<p class="t-sm-alignBottom"></p>
<p class="t-sm-alignBaseline"></p>
<p class="t-sm-alignTextTop"></p>
<p class="t-sm-alignTextBottom"></p>

/* text-align */
<p class="t-md-alignLeft"></p>
<p class="t-md-alignRight"></p>
<p class="t-md-alignCenter"></p>
<p class="t-md-alignJustify"></p>
/* vertical-align */
<p class="t-md-alignTop"></p>
<p class="t-md-alignMiddle"></p>
<p class="t-md-alignBottom"></p>
<p class="t-md-alignBaseline"></p>
<p class="t-md-alignTextTop"></p>
<p class="t-md-alignTextBottom"></p>

/* text-align */
<p class="t-lg-alignLeft"></p>
<p class="t-lg-alignRight"></p>
<p class="t-lg-alignCenter"></p>
<p class="t-lg-alignJustify"></p>
/* vertical-align */
<p class="t-lg-alignTop"></p>
<p class="t-lg-alignMiddle"></p>
<p class="t-lg-alignBottom"></p>
<p class="t-lg-alignBaseline"></p>
<p class="t-lg-alignTextTop"></p>
<p class="t-lg-alignTextBottom"></p>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
