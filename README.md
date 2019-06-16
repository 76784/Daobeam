# Daobeam - A low contrast, light theme, with balanced colors to minimize eye strain

## Supported Languages 
Polished support for ES6 (JavaScript), HTML, CSS, SCSS, Markdown, JSON. General support for most other languages, based on the colors used for JavaScript.

## Motivation and Goal
High contrast themes make your eyes work to balance out the high degree of difference between foreground and background colors. Dark themes make your eyes work to balance out the high degree of difference between the dark theme and the well-lit room you are (hopefully) working in. Beige works well as a background on a computer monitor. It's used by the Firefox reader button (sepia setting), and ebook apps. My goal is to create a theme that is not trying to be cool, but is comfortable for the eyes and helps you code.

!["Full Editor Screenshot"][6]

## Comparison of Biege Background Usages
While **Daobeam** is a light theme, it is in no way meant to be a *bright* theme.

!["Beige Colors Screenshot][5]

## About **Daobeam**
All colors are meant to compliment each other. For example, #880000 (burgundy) and #000088 (purple) [are tetradic harmonized colors][0].

~~JavaScript: `window`, `document`, and `getElementsByTagName()` - all members of the DOM - are all green; an example of the thought put into the foreground colors.~~

The VS Code team has unfortunately removed the DOM scope. This means that my coloring of DOM members no longer works. There is a workaround, but it would take more than my current available time.

CSS: Property values are all the same color (good!).

Comments: Consistent contrast level compared to other code. Theme designers: we already understand that comments are not processed as code. We don't need a visual indication (making them ultra-low contrast, etc.). **We should be able to read comments just as easily as code!**

I am open to pull requests and constructive feedback. I would like to see polished support for many other languages, particularly back-end languages. If you like **Daobeam**, please review it.

## User Settings Recommendations
VS Code user settings has properties to increase the font-size of the source code (`editor.fontSize`), the terminal (`terminal.integrated.fontSize`), but *not* the editor sidebar. Here is a workaround for this limitation: Increase the overall font-size of everything using `window.zoomLevel`, and then slightly *decrease* the `editor.fontSize` and `terminal.integrated.fontSize` to compensate for increasing `window.zoomLevel`:

```
{
    "workbench.colorTheme": "Daobeam",
    "editor.fontFamily": "Consolas",
    "editor.wordWrap": "on",
    "files.autoSave": "onFocusChange",
    
    //BEGIN these settings work in tandem ~~~~~~~~
    "window.zoomLevel": 0.7, // 0.7<-- keep this value in a comment, because it will be overwritten on ctrl + 0, ctrl + +, or ctrl + -.
    "editor.fontSize": 16, // smaller than I would want it if window.zoomLevel was 0
    "terminal.integrated.fontSize": 15, //smaller than I would want it if window.zoomLevel was 0
    //END these settings work in tandem ~~~~~~~~    
}
```
## Pay it Forward at World Community Grid
Please join the [Daobeam World Community Grid team](https://join.worldcommunitygrid.org?teamId=RF7TGV6H72). Just sign up, download the software, and start crunching.

## License
GNU General Public License v3.0

## Enjoy **Daobeam**!

[0]:https://www.sessions.edu/color-calculator/

[5]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/beige-usages.png

[6]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/full-editor.png

[7]:https://join.worldcommunitygrid.org?teamId=RF7TGV6H72