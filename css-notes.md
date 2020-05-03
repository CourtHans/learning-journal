[Return to Table of Contents](README.md)

# Class 5: CSS Notes

## CSS - an introduction

CSS - cascading style sheet

CSS is the style of the page - takes the foundation (your html) and makes it pretty (though in truth, beauty is in the eye of the beholder)

CSS is styled with selectors: element, class, id, universal, parent/child/siblings

Diffrerent types of selectors allow you to target your rules at different elements, . Understanding how CSS rules cascade means you can write simpler style sheets because you can create generic rules that apply to most elements and then override the properies on indivisual elements that need to appear differently (e.g. `!important`)

It's best practice to keep your CSS rules in a seperate document, for clean code and ease of duplication across multiple pages in a site (you can, however, keep them within an HTML page)

Declarations are made up of two parts: the properties of the lement that you want to change, and the values of those properties.

`p {font-family: "Arial";}`

In this example `p` is the selector - it tells the page which element the rules apply to. `{font-family: "Arial";}` is the declaration, where `font-family` is the property and `"Arial"` is the chosen value.
You can use several properties in a single declaration.

You can force a lot of properties to inherit values from their parent elements by using inherit for the value of the properties.

## Color

[Adobe Color Tool link](https://color.adobe.com/create)

Color helps bring your site to life!

There are three ways to specify colors in CSS:
1. RGB Values (red, green, blue - espressed as numbers b/w 0-255)
2. hex codes (6-digit codes that represent amount of r, g, and b in a color -preceded by a `#` - e.g. `#ee3e80`); hsl and hsla - hue, saturation, lightness, opacity
3. color names - there are 147 predefined color names recognized by browsers)

* **Color pickers** can help you find the color you want
* It is *critical* to ensure proper contrast between your background color and text for easy reading
* Hex values represent values for red, green, and blue in dexadecimal code. If two digits/letters are the same within each grouping, they can be represented by a single.
* **RGBA** is the value attributed to opacity for RGB colors with the "a" indicating alpha for opacity
* CSS3 allows you to specify colors as HSL values, with an optional opacity - it's known as **HSLA**


[Previous - HTML notes](html-notes.md)

[Next - JavaScript notes](javascript-notes.md)