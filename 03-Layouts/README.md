# Types of Layout in CSS
## Day 7: 15/11/2022
### Introduction
- Layout is the way text, images and other content is placed and arranged on a webpage.
#### CSS Grid 
- CSS Grid is a set of CSS properties for building 2-dimensional layouts.
- The main idea behind CSS Grid is that we divide a container element into rows and columns that can be filled with its child elements.
- An HTML element becomes a grid container when its display property is set to grid or inline-grid. <br>
![image](https://user-images.githubusercontent.com/88162824/201994987-d92e3c17-354b-4150-be4f-7c217c68b056.png)
- Important properties related to grid are demonstrated in the following [codepen](https://codepen.io/zainab-Memon/pen/rNKzpqm)
## Day 8: 16/11/2022
#### Floats 
- The CSS float property specifies how an element should float.
- The float property is used for positioning and formatting content 
- e.g. let an image float left to the text in a container.
- The float property can have one of the following values:
  - left - The element floats to the left of its container
  - right - The element floats to the right of its container
  - none - The element does not float (will be displayed just where it occurs in the text). This is default
  - inherit - The element inherits the float value of its parent
#### The clear Property
- When we use the float property, and we want the next element below (not on right or left), we will have to use the clear property.
- The clear property specifies what should happen with the element that is next to a floating element.
- The clear property can have one of the following values:
  - none - The element is not pushed below left or right floated elements. This is default
  - left - The element is pushed below left floated elements
  - right - The element is pushed below right floated elements
  - both - The element is pushed below both left and right floated elements
  - inherit - The element inherits the clear value from its parent
- When clearing floats, you should match the clear to the float: If an element is floated to the left, then you should clear to the left. 
- Your floated element will continue to float, but the cleared element will appear below it on the web page.
#### Clear fix hack
- A clearfix is a way for an element to automatically clear its child elements, so that you don't need to add additional markup. It's generally used in float layouts where elements are floated to be stacked horizontally.
- Syntax: <br>
  ![image](https://user-images.githubusercontent.com/88162824/202436724-d6b6b7e9-6329-44f7-bb84-290ff18acc6c.png)
#### Flexbox
- Flexbox is a one-dimensional layout method for laying out items in rows or columns. 
- Items flex to fill additional space and shrink to fit into smaller spaces.
- It is more flexible than the grid.
- Maintains Vertical Alignment
- Layout is more flexible as compared to grid.
- Important properties related to flexbox are demonstrated in the following [codepen](https://codepen.io/zainab-Memon/pen/BaVwKpN)
- We can nest flexboxes
