# Lesson# 8 – HTML Elements and Attributes


**What is element in HTML?**

An element in HTML represents some kind of structure or semantics and generally consists of a start tag, content, and an end tag. The following is a paragraph element:

```html
<p>

This is the content of the paragraph element.

</p>
```

**What are HTML attributes?**

An attribute defines a property for an element, consists of an attribute/value pair, and appears within the element’s start tag. An element’s start tag may contain any number of space-separated attribute/value pairs.

For example:

`<img src="adot.jpg">`

**Case Insensitivity in HTML Tags and Attributes**

In HTML, tag and attribute names are not `case-sensitive`. It means the tag `<P>`, and the tag` <p> `defines the same thing in HTML which is a paragraph.

#### _Example_

```html 
<p>This is a paragraph.</p>
```

```html 
<P>This is also a valid paragraph.</P>
```

**Empty HTML Elements**

Empty elements (also called self-closing or void elements) are not container tags — that means, you can not write `<hr>some content</hr>` or `<br>some content</br>`.

A typical example of an empty element, is the `<br>` element, which represents a line break. Some other common empty elements are `<img>, <input>, <link>, <meta>, <hr>,` etc.

**Nesting HTML Elements**

HTML elements can be nested (this means that elements can contain other elements).

All HTML documents consist of nested HTML elements.

The following example contains four HTML elements` (<html>, <body>, <h1> and <p>)`

Example
```html
<!DOCTYPE html>  
<html>  
<body>  
  
<h1>HyLo World</h1>  
<p>We are learning CS202</p>  
  
</body>  
</html>
```
Example Explained

The `<html>` element is the root element and it defines the whole HTML document.

It has a start tag `<html>` and an end tag `</html>`.

Then, inside the `<html>` element there is a `<body>` element:

`<body> ` 
  
`<h1>Hylo World</h1>  `
`<p>We are learning CS202</p>  `
  
`</body>`

The `<body>` element defines the document's body.

It has a start tag` <body>` and an end tag `</body>`.

Then, inside the `<body>` element there are two other elements: `<h1>` and `<p>`

`<h1>Hylo World</h1>  `
`<p>We are learning CS202</p>`

The` <h1> `element defines a heading.

It has a start tag` <h1> and an end tag </h1>`

`<h1>Hylo World</h1>`

The `<p> `element defines a paragraph.

It has a start tag `<p>` and an end tag `</p>`

`<p>We are learning CS202</p>`