# Changelog
All notable changes to the "Daobeam" extension will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
- ECMAScript 2015 (aka, ES6)

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
