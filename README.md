# Daobeam - A low contrast, light theme, with balanced colors to minimize eye strain

## Philosophy
Have you ever watched television in a totally dark room? That is an example of high contrast. It is hard on your eyes. It leads to eye strain. It is unhealthy. **Read "The Case Against Dark Themes" section near the bottom of this README.**

People like dark themes with bright foreground colors because they are eye-catching in the showroom. But most of these dark themes are very high contrast (example: Monokai). You're asking for eye strain by using themes like these. As a professional coder, I would not use a high contrast theme.

There are relatively few low contrast themes in general. They are much harder to design, and to design well. So I decided to design one myself.

**Daobeam** is designed to be low contrast and balanced in it's coloring. 

The Firefox (desktop) reader button (sepia setting) uses a similar (but lighter) beige background as **Daobeam**. **_Beige as a background is a thing, and a thing that works well._** If you want to look cool to your peers, use Monokai. If you want a theme that will minimize eye strain and help you code all day, use **Daobeam**.

## Supported Languages (currently)
ES6 (JavaScript) and below, JSON, HTML, CSS, SCSS, Markdown

## See Below the Screenshots for More Info

## Full Editor
!["Full Editor Screenshot"][6]

## JavaScript
!["JavaScript Screenshot"][1]

## CSS (note error shown)
!["CSS Screenshot"][2]

## HTML
!["HTML Screenshot"][3]

## JSON (note error shown)
!["JSON Screenshot"][4]

## Comparison of Biege Background Colors
Here is a comparison of several usages of beige as a background color. Whether you're reading a book for hours, or writing code for hours, beige as a background can help reduce eyestrain. **Notice how bright the VS Code theme "Solarized-light" is in comparison to Daobeam.**

!["Beige Colors Screenshot][5]

## My Approach / Things to Notice About **Daobeam**
Use colors that compliment each other. Don't use a bullhorn when designing. Syntax highlighting is supposed to help you code, not scream at you.

Colors balanced using professional tools, to ensure they compliment each other. For example, #880000 (burgundy) and #000088 (purple) [are tetradic harmonized colors][0].

Use bold when something is more powerful than something else. Case in point: CSS element names are in bold, because targeting them in CSS is more powerful than targeting an id or a class name. At the same time, don't get overly granular and try to highlight ids differently than class names.

In my CSS screenshots, notice how the property values are all the same color (good!). In many of the themes you see, this is not the case. As a long-time CSS developer, I want all property values to be the same color. Most themes don't have this consistency because the theme author didn't put in the time to figure out how to do it. I did.

## User Settings Recommendations
```
{
    "window.zoomLevel": 0,
    "editor.fontFamily": "Consolas",
    "editor.fontSize": 18,
    "workbench.colorTheme": "Daobeam",
    "files.autoSave": "onFocusChange",
    "editor.wordWrap": "on",
}
```

## The Case Against Dark Themes
Usually when one is talking about "low contrast", one is referring to the contrast of the foreground colors with respect to the background colors. But there is another area of contrast that does not get enough attention; the overall contrast of the theme itself in relation to your physical environment (the lighting of your room, the wall behind your monitor, your desk, etc.).

When it comes to reducing eyestrain, this matters. If you want to know what I'm talking about, try this:

1. Use a light theme for 20 minutes. Whatever you may think of that light theme, note that you are *not* thinking "whoa, that is bright".
2. Now switch to a dark theme, and use it for 20 minutes.
3. Now switch back to the light theme. You *will now* think "whoa, that is bright!". 

Have you ever thought about *why* this is? The answer is that your eyes dialated while using the dark theme. 

Not only that, when you use a dark theme in a light room, your eyes have to work to balance out the high contrast of the dark theme on the light room. The work your eyes are doing here is what is called "eyestrain".

**Daobeam** is designed to blend in with the well-lit room you are working in. 

If you are coding in a very dark room (and I don't recommend it), then **Daobeam** is probably not for you.

But if you work in a well-lit room like I do - with both natural light, and artificial light - then try **Daobeam**.

## License
GNU General Public License v3.0

## Enjoy **Daobeam**!

[0]:https://www.sessions.edu/color-calculator/

[1]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/javascript.png

[2]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/css.png

[3]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/html.png

[4]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/json.png

[5]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/beige-usages.png

[6]:https://raw.githubusercontent.com/76784/Daobeam/master/screenshots/full-editor.png