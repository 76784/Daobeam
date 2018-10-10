# Changelog
All notable changes to the "Daobeam" extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.3.4] - 2018-10-09
### Changed
- Most significant change: I found that I was hardly using my default foreground color, and I think using the default foreground color for function invocations and object properties works well. A function invocation is a very common thing, and shouldn't need to be called out. Goal: Don't be overly granular, and keep it simple.
- `this` keyword bold, non-italic
- numeric constant blue

## [1.3.3] - 2018-10-07
### Changed
- Make colors consistent hex code.

## [1.3.2] - 2018-10-02
### Changed
- Most significant change: remove italic from function invocations. After coding for awhile with all the italic font, I thought it was too much. Goal: Keep it simple.

### Refined
- Remove green font from non-DOM-related code. Support functions like `require` are now standard foreground color.
- `new` keyword now non-italic.
- Make purple consistent color, make green consistent color.
- Overall simplification; remove black in favor of standard very dark gray.
- Better scoping.
- Terminal green now standard foreground green from editor.

### Added
- Beginning of JSDoc section (comments in code).

## [1.3.1] - 2018-09-20
### Changed
- Tweaks to undo a few inadvertent changes to JavaScript coloring

## [1.3.0] - 2018-09-19
### Added
- General language support
    - I have taken the JavaScript coloring and added a section with general scoping. This should make most languages look decent.

### Changed
- JavaScript refinements
    - Make violet consistent, and based on current purple and burgundy.
- Terminal
    - Refinements and undoing some unnecessary "fixes"

## [1.2.4] - 2018-09-8
### Changed
- JavaScript refinements
    - Make DOM properties (bold) and DOM functions (italic) the same color (green). Now you know when you're working with the DOM!
    - Make variables much more consistent in color
    - Make string templates standard foreground color
	- General polishing (`delete` and `this` keywords)
    - Refactor and cleanup: remove a lot of overscoping in variables and functions
- All languages
    - Make comments slightly darker orange
- README.md
    - Added section on constrast
    - Changed user settings (how to increase sidebar font)

## [1.2.3] - 2018-09-1
### Changed
- Syntax coloring clean-up, make consistent, refactor
    - DOM function calls green, non-DOM function calls burgundy    

## [1.2.2] - 2018-08-31
### Changed
- Syntax coloring
    - `require()` colored like library functions, only not italic
    - Object literal "module" and key colored like JSON (for example, in webpack.config.js)
    - Comments changed from #CC6600 to #BF6000, which I feel is slightly more readable
- Change log
    - Correction to user settings recommendations

## [1.2.1] - 2018-08-26
### Changed
- Editor
    - Activity bar changed to a light background/dark foreground
- Syntax coloring
    - Numeric constant foreground color

## [1.2.0] - 2018-08-05
### Added
- Syntax coloring for ES6 (official name: ECMAScript 2015) added!

### Changed
- for JavaScript
    - careful scoping of green color for function calls (example: request.open() and request.send() now matching burgandy)
- side panel minor color tweaks

## [1.1.5] - 2018-07-03
### Changed
- for JavaScript
    - variable and function name -  improve consistency when inside and outside of functions and grouping parens
    - substantial refactoring

## [1.1.4] - 2018-07-02
### Changed
- for JavaScript
    - painstaking foreground coloring work
    - color and style of function name when outside of grouping parens
    - color and style of function name at prototype definition
    - color of function name defined in an object (e.g., blah in blah: function()...)
    - bold font for property at prototype definition
    - make color of property names consistent
    - bind(), map(), etc., now colored like library functions (part of the language - a function you did not write)

## [1.1.3] - 2018-06-30
### Changed
- for JavaScript
    - function name bold (invocation of function is unchanged)
    - User in User.prototype.toString bold font, non-italic
    - Object in Object.getPrototypeOf(u) bold font
    - use theme-existing purple foreground color for JS variable name 
    - use theme-existing blue foreground color for array braces
    - other minor font changes for the sake of consistency
    - update screenshot

## [1.1.2] - 2018-05-09
### Fixed
- Fix broken icon image

## [1.1.1] - 2018-05-09
### Changed
- Built-in constant (null, false, undefined) for all languages
    - Change to blue. Previous color was extremely close to string color.
- Terminal foreground colors
- Foreground and background colors of Problems / Output / Debug Console 
- More closely following format of [Keep a Changelog](http://keepachangelog.com/)
- Changlog now follows [Semantic Versioning](http://semver.org/spec/v2.0.0.html)
    - Previous version should have been version 1.1.0 when Markdown was added (functionality added, minor version number increments)

## [1.0.4] - 2018-04-27
### Added
- Syntax highlighting for Markdown added!
### Changed
- Terminal background color changed to work better with foreground colors
- Terminal foreground color tweak
- Borders added to panes
- Tab colors

## [1.0.3] - 2018-04-22
### Changed
- JavaScript refinements:
    - Refactoring
    - Object name in bold
    - DOM functions (e.g., `createElement()`) - darken green color, italics
    - `this` keyword font style normal
    - italics on function invocation, but not definition
    - a few other polishes
- Change display name back to "Daobeam"

## [1.0.2] - 2018-04-08
### Changed
- Change display name to "Daobeam Theme"
- Correct spelling in README.md

## [1.0.1] - 2018-04-07
### Changed
- Correct spelling in README.md

## [1.0.0] - 2018-04-07
### Initial release
- Support for HTML, CSS, SCSS, JavaScript, JSON
