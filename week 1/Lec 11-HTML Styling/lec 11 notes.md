# Lesson# 11 – HTML Styling 


**HTML Tags**

HTML Tags: Tags are the starting and ending parts of an HTML element. They begin with < symbol and end with > symbol. Whatever written inside < and > are called tags.

Example:

`<b> </b>`

**HTML elements**

HTML elements: Elements enclose the contents in between the tags. They consist of some kind of structure or expression. It generally consists of a start tag, content and an end tag.

Example:

`<b>This is the content.</b>`

Where, `<b>` is the starting tag and `</b>` is the ending tag.

# **HTML Attributes**

HTML Attributes: It is used to define the character of an HTML element. It always placed in the opening tag of an element. It generally provides additional styling (attribute) to the element.

Example:

`<p align="center">This is paragraph.</p>`

**What is HTML Style Attribute?**

The style attribute specifies an inline style for an element.

The style attribute will override any style set globally.

The HTML style attribute has the following syntax:

style="property:value"

**Example**

Use of the style attribute in an HTML document:
```html
<h1 style="color:blue;text-align:center">This is a header</h1>

<p style="color:green">This is a paragraph.</p>
```
Result:

![](/resources/lec%2011%20-result.png)

**HTML Style Properties**

-   Use background-color for background color
-   Use color for text colors
-   Use font-family for text fonts
-   Use font-size for text sizes
-   Use text-align for text alignment

**HTML Formatting Elements**

HTML also defines special elements, for defining text with a special meaning.

HTML uses elements like` <b>`and `<i> `for formatting output, like bold or italic.

Following are some of the formatting elements:

## **HTML <b> element**

The HTML` <b> `element defines bold text, without any extra importance.

`<p>This text is normal.</p>`

`<p><b>This text is bold</b>.</p>`

**The HTML <i> element**

The HTML` <i>` element defines italic text, without any extra importance.

`<p>This text is normal.</p>`

`<p><i>This text is italic</i>.</p>`

 **The HTML` <em> `element**

The HTML `<em>` element defines emphasized text, with added semantic importance.

`<p>This text is normal.</p>`

`<p><em>This text is emphasized</em>.</p>`

**The HTML `<small>` element**

The HTML `<small> `element defines small text:

`<h2>HTML <small>Small</small> Formatting</h2>`

**The HTML `<mark>` element**

The HTML `<mark>` element defines marked or highlighted text:

`<h2>HTML <mark>Marked</mark> Formatting</h2>`

**The HTML `<del>` element**

The HTML` <del> `element defines deleted (removed) of text.

`<p>My favorite color is <del>blue</del> red.</p>`

**The HTML `<sub>` element**

The HTML `<sub>` element defines subscripted text.

`<p>This is <sub>subscripted</sub> text.</p>`