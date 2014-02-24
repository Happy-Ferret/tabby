# Tabby
Tabby is a lightweight toggle tab powered by vanilla JS.

## How It Works
Getting started with Tabby is really easy. [View the online tutorial](http://cferdinandi.github.com/tabby/) or dig through the `index.html` file.

## Changelog
* v6.0 (February 24, 2014)
  * Better public/private method namespacing.
  * Require `init()` call to run.
  * New API exposes additional methods for use in your own scripts.
  * Better documentation.
* v5.3 (February 16, 2014)
  * [Added method to stop YouTube, Vimeo, and HTML5 videos from playing when tab is closed.](https://github.com/cferdinandi/tabby/issues/8)
* v5.2 (February 5, 2014)
  * Reverted to `Array.prototype.forEach` loops.
* v5.1 (January 27, 2014)
  * Updated addEventListener to be more object oriented.
  * Moved feature test to script itself.
* v5.0 (January 27, 2014)
  * Switched to a data attribute for the toggle selector (separates scripts from styles).
  * Removed unused `tab-toggle` class.
  * Prefixed script with a `;` to prevent errors if other scripts are incorrectly closed.
  * Added namespacing to IIFE.
* v4.0 (December 4, 2013)
  * Added Sass support.
  * Removed horizontal and vertical styling for great design flexibility.
  * Add active class to button elements.
* v3.2 (August 27, 2013)
  * Added missing semicolon.
  * Activated strict mode.
* v3.1 (August 26,2013)
  * Converted to an IIFE pattern.
  * Added Buoy vanilla JS micro-library.
* v3.0 (August 13, 2013)
  * Converted to vanilla JS.
  * Removed dependence on jQuery.
* v2.1 (August 5, 2013)
  * Updated with variable for `$(this)` (better performance).
* v2.0 (June 7, 2013)
  * Switched to MIT license.
* v2.0 (June 5, 2013)
  * Switched from `href` to `data-target` value for tab id, breaking backward compatibility.
* v1.1 (February 13, 2013)
  * Renamed `example.html` to `index.html`.
* v1.1 (February 5, 2013)
  * Switched to relative sizing.
* v1.0 (January 22, 2013)
  * Initial release.

## License
Tabby is free to use under the [MIT License](http://gomakethings.com/mit/).