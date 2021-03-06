[![Build Status](https://travis-ci.org/ikr/react-star-rating-input.svg?branch=master)](https://travis-ci.org/ikr/react-star-rating-input)

# About

React.js component for entering 0-N stars (N is 5 by default). See
[the demo](http://ikr.su/h/react-star-rating-input/demo.html).

# Installation

Made for [Browserify](http://browserify.org/); graphics and CSS bundled.

    npm install --save react-star-rating-input

# Usage

See [the code](https://github.com/ikr/react-star-rating-input/blob/master/demo.js) of the demo
mentioned above.

## Props

Static layout

* `size` -- how many stars to display. The default value is 5
* `showClear` -- hides the "Clear" link when `false`. The default value is `true`
* `clearLabel` -- custom text for the "Clear" link
* `clearHint` -- custom `<a>`'s title, a tooltip for the "Clear" link on mouse-hover

Interaction

* `value` -- how many stars are selected
* `onChange: function (value) {...}` -- your `value` change handler
