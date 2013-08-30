# Bits.sass utilities: space

Utility classes for spacing-related CSS. See [other utilities](https://github.com/bits-sass/utils).

Read more about [Bits.sass toolkit](https://github.com/bits-sass/bits.sass).

## Installation

* __Bower:__ `bower install --save bits-sass-utils-space`
* __Download:__ [zip](https://github.com/bits-sass/utils-space/zipball/master), [tar.gz](https://github.com/bits-sass/utils-space/tarball/master)
* __Git:__ `git clone https://github.com/bits-sass/utils-space.git`

## Demo

See [demo](https://rawgithub.com/bits-sass/utils-space/master/demo/index.html).

## Available SASS variables

* `bits-utils-ns` - utilities namespace, defaults to 'bits-'

### Spacing

* `bits-space-spacing-directions` - specifies list of generated `<D>` directions
* `bits-space-spacing-sizes` - specifies list of generated `<s>` sizes

### Gutters

* `bits-space-gutter-supported-children` - specifies list of supported children
   that should have a gutter inbetween
* `bits-space-gutter-types` - specifies list of generated `<T>` types
* `bits-space-gutter-sizes` - specifies list of generated `<s>` sizes

### Stretching

* `bits-space-stretch-types` - specifies list of generated `<T>` types
* `bits-space-stretch-sizes` - specifies list of generated `<s>` sizes

## Available utility classes

### Spacing

* `u-margin<D><s>` (adjustable) - margin of size `s` in the direction `D`
* `u-padding<D><s>` (adjustable) - padding of size `s` in the direction `D`

### Gutters

* `u-gutter<T><s>` (adjustable) - gutter of size `s` and type `T`

### Stretching

* `u-stretch<T><s>` (adjustable) - stretching of size `s` and type `T`

## Requirements

* Sass 3.2+

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+