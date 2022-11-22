# Lesson# 7 – HTML Basics 


**Definition of an HTML Document**

An HTML document is a file containing hypertext markup language. HTML code is based on tags, or hidden keywords, which provide instructions for formatting the document. A tag starts with an angle bracket and the 'less than' sign: '<'. The tag ends with an angle bracket and the 'greater than' sign '>'. Tags tell the processing program, often the web browser, what to do with the text. For example, to make the word 'Hello' bold, you would use the opening bold tag` <b>` and then the closing bold tag `</b>`, like this:

`<b>Hello</b>`

HTML is defined by the World Wide Web Consortium, an organization that regulates standards for the Internet. Each version of HTML has a set of definitions. Note that HTML is not a programming language. While we often refer to HTML markup as HTML code, programming languages require the processing of logical statements and math. HTML allows the developer to make text documents look engaging and pleasant. In most cases, programming on an HTML document is done with JavaScript.

**The Meaning of `<!DOCTYPE html>`**

The very first line in every web document should contain a `<!DOCTYPE html>` declaration. Even though it's wrapped in angle brackets, it is not a tag but a statement.

Doctype stands for Document Type Declaration. It informs the web browser about the type and version of HTML used in building the web document. This helps the browser to handle and load it properly.

**The` <html>` tag**

The `<html>` tag represents the root of an HTML document.

The` <html>` tag is the container for all other HTML elements (except for the` <!DOCTYPE>` tag).

**What are HTML attributes?**

HTML attributes are special words used inside the opening tag to control the element's behavior. HTML attributes are modifiers of an HTML element type.

All HTML elements can have attributes. Attributes provide additional information about elements. Attributes are always specified in the start tag. Attributes usually come in name/value pairs like: `name="value"`.

The`<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:

**Example**

```html 
<img src="xyz.jpg">