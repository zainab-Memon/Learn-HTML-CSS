# 01- HTML FUNDAMENTALS
## Day 1: 09/11/2022
- HTML --> Noun --> Content 
- CSS  --> Adjectives --> Presentation of Content 
- JS   --> Verb --> Provides dynamic effects and web applications
### Introduction
- HyperText Markup Language
- HTML is a markup language that web developers use to structure and describe the content of a webpage (not a programming language) 
- Element: \<p> Hi, My name is Zainab Memon \</p>
	- Opening Tag: \<p>
	- Closing Tag: \</p>
	- Content: Hi, My name is Zainab Memon
### HTML Document Structure 
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/doc%20structure.PNG)
### Headings 
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/html%20headings.PNG) <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/headings.PNG)
### Text and Formatting Elements 
There are so many text elements in html, a few of them are listed below.
- Paragraph Element: \<p> This is a paragraph element \</p>
- List Element: You can use two types of list in html.
	- Ordered Lists <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/OL.PNG) <br>	
	- Unordered Lists <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/ul.PNG) <br>
#### Formatting Elements
Here is a list of a few formatting elements of html 
- \<b> - Bold text
- \<strong> - Important text
- \<i> - Italic text
- \<em> - Emphasized text
- \<mark> - Marked text
- \<small> - Smaller text
- \<del> - Deleted text
- \<ins> - Inserted text
- \<sub> - Subscript text
- \<sup> - Superscript text
## Day 2 10/11/2022
### Attributes 
- Attributes are pieces of data which we can use to describe the elements.
- There are lots of attributes in html. 
- All HTML elements can have attributes
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"
- Here are a few of the attributes of different HTML elements:
	- The href attribute of \<a> specifies the URL of the page the link goes to.
	- The src attribute of \<img> specifies the path to the image to be displayed
	- The width and height attributes of \<img> provide size information for images
	- The alt attribute of \<img> provides an alternate text for an image
	- The style attribute is used to add styles to an element, such as color, font, size, and more
	- The lang attribute of the \<html> tag declares the language of the Web page
	- The title attribute defines some extra information about an element
### Image Tag
- The HTML \<img> tag is used to embed an image in a web page.
- Images are not technically inserted into a web page; images are linked to web pages. 
- The \<img> tag creates a holding space for the referenced image.
- The \<img> tag is empty, it contains attributes only, and does not have a closing tag.
- The \<img> tag has two required attributes:
	- src: Specifies the path to the image
	- alt: Specifies an alternate text for the image <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/image%20tag.PNG)
### Comments
- If you want some text to be in the code file but do not want it to be displayed on the browser, you can hide it using html comments.
- You can use comments to document your source code.
- Syntax: \<!-- Write your comments here \-->
### Hyperlinks 
- Links are hyperlinks that help a user jump to another document or jump to some other content within the document.
- A link can be text, image or any other html element.
- The HTML \<a> tag defines a hyperlink.<br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/link.PNG)
- Here the href attribute defines the link destination. 
- The content within the opening and closing tag will be displayed to the user.
- Once he clicks the text, he will be redirected to the destination page.
- The target attribute specifies where to open the linked document. 
- By default, the link will open in the same browser window, however you can set it to different window by using target attribute. 
- The target attribute can have one of the following values:
	- \_self: Default. Opens the document in the same window/tab as it was clicked
	- \_blank: Opens the document in a new window or tab
	- \_parent: Opens the document in the parent frame
	- \_top: Opens the document in the full body of the window
#### Absolute URL and Relative URL 
- A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part)
- An absolute URL contains the entire address and points to other websites.
