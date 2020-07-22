[Home](README.md)
## Learning Journal Notes
# Design Web Pages with CSS
---
## Duckett’s HTML & CSS 
### Chapter 10 – Introducing CSS
CSS stands for Cascading Style Sheets; it is a language used to specify the style of a website. CSS applies styling rules to HTML elements. 

Best practice is to store CSS code in a separate file not in the HTML code. 

By the way you can add comments in CSS `/* like this*/`.

Foreground is inside an element; background is the space around elements.

Use the `<link>` element to specify CSS file, with href, type, and relationship as shown below.

`<link href=”css/styles.css” type=”text/css” rel=”stylesheet” />`

* Selector – selects which HTML element(s) to format. 
* Declaration – declares formatting for the selected HTML element(s), contains property and value
* Property – indicates aspect of the element to change
* Value – specifies the setting for the chosen property

`p {
  color: red;
  text-align: center;
}`

In the above example, `p` is the selector, selecting all paragraphs to be affected; `color: red;` and `text-align: center;` are declarations; `color` and `text-align` are properties and `red` and `center` are values.

[CSS Selectors Reference](https://www.w3schools.com/cssref/css_selectors.asp) 

[CSS Selector Tester](https://www.w3schools.com/cssref/trysel.asp)

### CSS Rules Precedence
If more than one rule applies to the same element,  precedence is determine by:
* Last rule - if two selectors are identical, the latter takes precedence.
* Specificity - the more specific selector takes precedence over the more general selector.
* Important - add `!important` after any property value to indicate it is more important than other rules applied to that element.

Font-family property is inherited; background-color and border properties are not inherited.

Check how your site displays on different operating systems and web browsers using the following online tools:
BrowserCam.com
BrowserLab.Adobe.com
BrowserShots.org
CrossBrowserTesting.com
To find a solution to a browser quirk or CSS bug, try these sites:
PositionIsEverything.net
QuirksMode.org

Example: 
In this example, the selectors are h1, h2, and h3, meaning those three headings types are selected for this CSS formatting rule. There are two declarations
h1, h2, h3 {
                   font-family: Arial;
                   color: yellow;}

### Chapter 11 – Color
Three ways to specify color: RGB values (100,100,90), hex codes (#ee3e80), and color names (DarkCyan). Red green and blue (RGB) values range is 0 to 255. Hex code colors express red green blue in hexidecimal code (205 expressed as cd and 170 expressed as aa). There are 147 predefined color names supported by browsers. Hue is essentially color (technically color also has saturation and brightness); saturation is amount of grey in a color - max saturation is no grey; min saturation is most gray; brightness is amount of black in a color - max brightness is no black; min brightness is very dark.

Try my [CSS Web Design Quiz](/class05quiz.md)!

### Additional Resources

[Contrast checker tool](www.snook.ca/technical/colour_contrast/colour.html)

[Adobe's Create Color Wheel](color.adobe.com/create/color-wheel/)

[ColorHunt Color Palettes](https://colorhunt.co/)

[Mozilla CSS Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/)

[Web Accessibility Evaluation Tool](https://wave.webaim.org/)


