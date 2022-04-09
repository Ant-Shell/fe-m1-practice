# Day 2 Exercises
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
Of note: Letting the user know the page will open in a new window is a best practice.

4. How do you link to a specific part of the same page?
- Linking to a specific part of the page requires an id attribute and an href attribute linking back to the id attribute as follows:

`<h1 id="top">Example link</h1>`
which links to:
`<p><a href="#top">Back to top of page</a></p>`
