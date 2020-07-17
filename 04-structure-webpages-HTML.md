[Home](README.md)
## Learning Journal Notes
# Structure Web Pages with HTML
---
## Duckett’s HTML & CSS 
### Chapter 18 – Process & Design
Website designers need to design website for the target audience, not yourself or the site owner. Invent some fictional visitors – can include name, gender, age, location, occupation, income, web use – to think about how the website will be used.

The target audience could have a variety of motivations and goals for visiting a website, including entertainment, researching a topic, product information, contact information, and many more. 
A site map is a diagram that shows how a website will be structured. The card sorting technique can be used to decide how to organize it – place each piece of information a visitor might need to know then organize them into groups. 

A wireframe is a simple sketch of the sections of a page, showing hierarchy of information and how much space each section requires. 

Visual hierarchy draws attention to key messages first, differentiating using size, color, and style.
### Chapter 1 – Structure
This was an overview of HTML pages, tags, and attributes.
### Chapter 17 – HTML5 Layout
HTML5 elements indicate the purpose of different parts of the webpage and are clearer to read than HTML which used multiple `<div>` commands. Examples of new HTML5 elements include `<header>`, `<nav>`, `<article>`, and `<aside>` (previously `<div id=”header”>`, `<div id=”nav”>`, `<div id=”article”>`, and `<div id=”sidebar”>`). Older web browsers (IE9 and older) require a workaround line of JavaScript to display the HTML5 code properly.
### Chapter 8 – Extra Markup
For HTML5, the very first thing in a document is `<!DOCTYPE html>`; other versions of HTML have different document type declarations.

To make comments in HTML use `<!--  comment here -->`. Comment regularly, for others and for yourself when you come back to it later.

An ‘id’ attribute uniquely identifies one element from other elements in the page. The example below identifies the paragraph as ‘pullquote’ and can be styled differently than the rest of the elements on the page.
`<p id=’pullquote’> This paragraph is a quote. </p>`

A class attribute groups similar elements within a document, so that a CSS rule can later style them together. More than one class can be assigned to one element.
`<p class=”important”>This is an important paragraph. </p>`
`<p class=”important admittance”>Hours 10:00 – 18:00 </p>`

Block elements start on a new line in browser window, examples: `<h1>`, `<p>`, `<u1>`, and `<li>`.

Inline elements continue on same line in browser window, examples: `<a>`, `<b>`, `<em>`, and `<img>`.

`<div>` groups a set of elements together in one block-level box.

`<span>` is an inline equivalent of `<div>` element.

`<iframe>` inline frame embeds another webpage into another webpage, such as a Google map in a window of another webpage. No scrolling or frameborder in HTML5; new HTML5 attribute seamless.

`<meta>` tag specifies information about your webpage.
Escape characters (&) are used to escape meaning of special characters in HTML. 



## Additional Resources for Webpage Design
   * [User Persona Comparison](https://library.xtensio.com/user-persona-comparison-template-and-examples)
   * [Persona Development Discussion Guide](https://www.usability.gov/how-to-and-tools/resources/templates/persona-development-discussion-guide.html)
   * [Balsamiq](https://balsamiq.com/for/web-designers)
   * [Usability](https://www.usability.gov/)
   * [Timothy Templates](https://www.timothytemplates.com/)
   * [Xtensio Templates](https://xtensio.com/templates/)
   * [Personas - YouTube](https://www.youtube.com/watch?v=GNvLpfXCge8)

