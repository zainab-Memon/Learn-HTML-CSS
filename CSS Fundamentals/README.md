# 02- CSS Fundamentals
## Day 3: 11/11/2022
### Introduction 
- CSS : Cascading Style Sheet
- HTML doesn't contain the tags to do the styling of the web page or define how the content should be displayed to the user.
- CSS is all about styling the content that we write in HTML.
- It is used to define different styles for the webpage and handles how the content is displayed to the end user.
### CSS Syntax
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/syntax.PNG)
### Implementing CSS
- There are three ways you can use to implement CSS into your HTML: 
#### Inline CSS
- An inline CSS is used to apply a unique style to a single HTML element.
- An inline CSS uses the style attribute of an HTML element.
- Syntax: \<h1 style="color:blue;">A Blue Heading\</h1>
#### Internal CSS
- An internal CSS is used to define a style for a single HTML page.
- An internal CSS is defined in the \<head> section of an HTML page, within a \<style> element.
- Syntax: <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/internal%20css.PNG)
#### External CSS
- An external style sheet is used to define the style for many HTML pages.
- The external style sheet can be written in any text editor. 
- The file must not contain any HTML code, and must be saved with a .css extension.
- To use an external style sheet, add a link to it in the /<head> section of each HTML page:
- Syntax: <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/stylecss.PNG) <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/external%20css1.PNG)
- **Note: Inline style should never usually be used.**
- External CSS is usually preferred as we can use it to style various web pages.  
### Styling Text 
- There are so many properties in CSS to style text. 
- You don't need to memorize all of them
- Few of the important and most used ones are discusse below. 
#### Text Color 
- We can change/set the color of text in css by using the color property in css. 
#### Text Font Size
- We can set the size of font using the font-size property in css
- The size can be defined in many different units, but for now we will stick to px
#### Text Font Family 
- In CSS, we use the font-family property to specify the font of a text.
- If the font name is more than one word, it must be in quotation marks, like: "Times New Roman".
- You can specify more than one font for your website, so that if the browser doesn't support one of the fonts, it can use another one from your specified fonts
#### Text Alignment
- The text-align property is used to set the horizontal-alignment of the text. 
- A text can be left or right aligned, centered, or justified.
#### Text Transform
- With this property, we can specify the uppercase and lowercase letters in the text
- It can be used to turn everything into uppercase or lowercase letters, or capitalize the first letter of each word
#### Font Style
- The font-style property allows you to make text appear italicized 
- This property accepts one of three possible values: normal, italic, and oblique.
#### Text Spacing
- There are many text spacing properties. One of them is line Height.
- It's used to set the distance between lines of text. <br>
**All of the above mentioned properties are applied on the index.html file from HTML Fundamental chapters.**<br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/text%20styling.PNG) <br>
- You can check the output of this code by downloading the code file of this chapter.
### Selectors 
- A CSS selector selects the HTML element(s) you want to style.
- There are 5 important selectors in CSS
#### Element Selector
- The element selector selects html elements based on their names as shown in above image.
#### Grouping Selectors 
- The grouping selector selects all the HTML elements with the same style definitions.
- As shown in above figure, all the elements have same font-family, so rather than defining the font family over and over again for each element, we can simply group these elements and declare a single css rule for all of them as shown below.
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/group%20selector.PNG)
#### Universal Selector 
- The universal selector (*), selects all of the HTML elements on the page. <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/universal%20selector.PNG)
#### Class Selector 
- The class selector selects HTML elements with a specific class attribute.
- To select elements with a specific class, write a period (.) character, followed by the class name.
- HTML elements can also refer to more than one class <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/class.PNG)
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/class%20sele.PNG)
#### ID Selector 
- The id selector uses the id attribute of an HTML element to select a specific element.
- The id of an element is unique within a page, so the id selector is used to select one unique element!
- To select an element with a specific id, write a hash (#) character, followed by the id of the element.<br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/id.PNG) <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/id%20selector.PNG)
- The difference between id and class selectors is that we **cannot repeat same id more than once** in an html page, however more than one element can belong to same class.
- We usually use **class selectors**, so that a number of different elements can use that styling in future, if need be.
### Comment 
- In css, you can comment your code using this syntax: \/* This is a single-line comment \*/
### Color 
- In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.
- **RGB:** rgb(red, green, blue)
- Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.
- **RGBA:** RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.
- The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all)
- **HEX:** A hexadecimal color is specified with: #RRGGBB, Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).
- The 3-digit hex code can be used when both the values (RR, GG, and BB) are the same for each component. So, if we have #ff00cc, it can be written like this: #f0c. 
- **HSL:** HSL stands for hue, saturation, and lightness.
- hsl(hue, saturation, lightness)
  - Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.
  - Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color.
  - Lightness is also a percentage. 0% is black, 50% is neither light or dark, 100% is white
- Note: We mostly use HEX or RGBA
### Border 
- The CSS border properties allow you to specify the style, width, and color of an element's border.
#### border-width
- Specifies the width of the four borders.
- The border-width property can have from one to four values (for the top border, right border, bottom border, and the left border) <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/border-width.PNG)
#### border-color
- Specifies the color of the four borders.
- The border-color property can have from one to four values (for the top border, right border, bottom border, and the left border).
#### border-style
- Specifies the style of the four borders, either as dotted, solid, dashed etc.
#### Individual Side Border
- border-top refers to the top side of the border, we can solely change its width, style and color as <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/border-top.PNG)
- Similary, we can use border-right, border-left, and border-bottom to style rest of the borders.
#### Shorthand Border
- We can use a shorthand property for width, style and color: <br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/border%20shorthand.PNG)  
- we can use this shortand property with individual side borders as well.<br>
![](https://github.com/zainab-Memon/Learn-HTML-CSS/blob/main/Images/border%20short%20ind.PNG) 
