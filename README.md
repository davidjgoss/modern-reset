# modern-reset
A modern CSS reset

Other solutions have been invented since, but I still think [Eric Meyer's CSS Reset](http://meyerweb.com/eric/tools/css/reset/) is the best way of approaching the problem of getting a predictable baseline across browsers. I've adapted Eric's original reset for the modern browser landscape.

## Changes

- Removed `display:block` for HTML5 elements --- no need any more
- Removed `line-height:1` --- leading is a project style decision
- Added `font:inherit` for form elements --- saves doing it per-element later
- Added `box-sizing:inherit` universally and `border-box` on root --- nicer box model by default
- Added `text-size-adjust:100%` on root --- fixes some unwanted mobile browser behaviour
- Added `max-width` and `max-height` to image elements --- responsive by default
- Added sensible defaults for text-level semantic elements

## Browser support

IE9+, Edge, Safari, Firefox, Chrome, Opera.
