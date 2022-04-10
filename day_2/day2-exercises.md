# Day 2 Exercises
## HTML
1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
- Ordered List: This list type uses numbers for ordering
- Unordered List: This list type uses bullet points for ordering
- Definition: This list type is used for defining terminology

2. What is the basic structure of an element used to link to another website?
- The basic structure is as follows:
```
<a href="https://turing.edu/">Turing.edu</a>
```
This consists of an opening link tag (plus href and assigned URL), and closing link tag (link text the user clicks on is between the opening and closing link tags, after the URL)

3. What attribute should you include in a link to open a new tab when the link is clicked?
- The `target=_blank` attribute should be added; example:
```
<a href="https://turing.edu/" target="_blank">Turing.edu</a> (Opens in new window)
```
**Of note:** Letting the user know the page will open in a new window is a best practice.

4. How do you link to a specific part of the same page?
- Linking to a specific part of the page requires an id attribute and an href attribute linking back to the id attribute as follows:

`<h1 id="top">Example link</h1>`
which links to:
`<p><a href="#top">Top of page</a></p>`

## CSS
1. What is the purpose of CSS?
- The purpose of CSS is to allow for creating rules which specify how content of an element should appear.

2. What does CSS stand for? What does cascading mean in this case?
- CSS stands for Cascading Style Sheets. Cascading, in this case, means ordering from most broad rules at the top to more specific rules moving toward the bottom. The ordering of rules is important.

3. What is the basic structure of a CSS rule?
- The basic structure is as follows:
```
h1 {
  font-family: Times New Roman;
}
```
This consists of the selector (h1) and the declaration (font-family: Times New Roman;)

4. How do you link a CSS stylesheet to your HTML document?
- A CSS stylesheet is linked by using the <link /> element, along with href, type and rel attributes. Example follows:
```
<link href="css/cool-styles.css" type="text/css" rel="stylesheet" />
```

5. When is it useful to use external stylesheets as opposed to using internal CSS?
- External stylesheets are best used when building a site with more than one webpage.

6. Describe what a color hex code is.
- A color hex code is a six-digit code which represents the amount of red, green and blue in a color, beginning with a # sign.
  * Example: `#99ccff`

7. What are the three parts of an HSL color property?
- The three parts of an HSL property are: Hue, Saturation, and Lightness/Luminosity

8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?
- The three main categories of fonts are:
  * Serif - has serifs (extra details on the end of letters)
  * Sans-Serif - has straight ends to letters (literally every without serifs)
  * Monospace - Every letter has the same width (non-monospace have different widths)

9. When specifying font-size, what are the main three units used?
- The three main units are:
  * Pixels (px)
  * Percentages (%)
  * Ems (em)
