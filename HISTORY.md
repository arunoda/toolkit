1.5.0 / master
==================

  * Migrated testing framework to QUnit.
  * Added all missing ECMA5 methods from ECMA3.
  * Added advanced descriptor processing utilities for legacy browsers.
  * Fixed to pass tests on Safari 5.1, Chrome 14 and IE 5.5, 6, 7 and 8

1.4.0 / 2011-09-18 
==================

  * Migrated testing framework to expresso.
  * Preparing for browser migration and updated a lot of the docs.
  * Added: New useful Array#plug key array parameter.
  * Added: Array shortcut utilities (avoids having to use Func.apply)
  * Added: Object.enum/Object.enum$ for working with enumerable hashes.
  * Bugfix: Multiple bug fixes to tests and methods.

1.3.0 / 2011-09-10 
==================

  * Brand new documenter to better generate docs.
  * A lot of random bug fixes and improvements to docs overall.
  * Added: 15 new methods including: Object.size, Array#invoke, Array#pluck, Array#grep, Array#sortBy, Array#fetch, Number#radix, Number#bin, Number#oct, Number#dec, Number#hexl, Number#hex, Number#abbr, String#pad and String#sprintf.
  * Added: 14 Self-modification functions including: Object.Map$, Object.filter$, Object.clean$, Array#map$, Array#Filter$, Array#clean$, Array#shuffle$, Array#chunk$, Array#flatten$, Array#invoke$, Array#pluck$, Array#grep, Array#sort$ and Array#sortBy$.
  * Bugfix: Object.reduce not working correctly.

1.2.0 / 2011-09-07 
==================

  * A number of improvements on the docs with a number of examples / descriptions updated.
  * Api: First() and Last() in Array.prototype now return just the value if given no parameter.
  * Added: String.prototype methods.
  * Added: Function.prototype methods.
  * Added: Object hash id. Useful for caching methods.
  * Bugfix: Sum() and Product() in Array.prototype didn't cast values.
  * Bugfix: Infamous error in the calculation of odd numbers.

1.1.0 / 2011-09-01 
==================

  * New documenter added to automatically generate documents
  * Added: Number.prototype methods added
  * Added: Object.walk method added
  * Bugfix: Object.clone wasn't working
  * Bugfix: Callbacks weren't respecting scopes
  * Bugfix: Object.map & filter recreated object incorrectly
  * Bugfix: Array.range was declared as enumerable

1.0.0 / 2011-08-27 
==================

  * Initial Release
  * Unit Tests Complete
  * Math, Array and Object extensions pass all tests and are to spec design.