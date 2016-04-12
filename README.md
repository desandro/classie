# classie - class helper functions

[Ripped from bonzo](https://github.com/ded/bonzo) :heart: @ded

## No longer supported

Use classie only if you need to support older browsers that do not support `classList`. `classList` is supported in IE10+, Android 3+, iOS Safari 5.1+, and modern evergreen browsers. [Can I use classList](http://caniuse.com/#search=classlist)?

classie is longer supported. v1.0.1 is the final version.

## Usage

``` js
classie.has( element, 'my-class' ) // returns true/false
classie.add( element, 'my-new-class' ) // add new class
classie.remove( element, 'my-unwanted-class' ) // remove class
classie.toggle( element, 'my-class' ) // toggle class
```

## Package management

Install with [Bower](http://bower.io) :bird: `bower install classie`

Install with [npm](https://github.com/npm/npm) `npm install desandro-classie`

Install with [Component](http://github.com/component/component) `component install desandro/classie`

## MIT license

classie is released under the [MIT license](http://desandro.mit-license.org).
