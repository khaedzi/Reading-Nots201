# Read-03
## HTML Lists:
### The type of Lists in the HTML:
* Ordered lists:
 - Ordered listes will give Orders or marks to the items inside, items will be marked with numbers by default.
An ordered list starts with the <ol> tag. Each list item starts with the <li> tag.
* Unordered lists:
 - Unordered listes will not give Orders or marks to the items inside, The list items will be marked with bullets (small black circles) by default.
An unordered list starts with the <ul> tag. Each list item starts with the <li> tag.
 * Definition lists:
 - A description list is a list of terms, with a description of each term.
The <dl> tag defines the description list, the <dt> tag defines the term (name), and the <dd> tag describes each term:
  
 # CSS:
## Box Dimensions:
![box-model](https://s3.amazonaws.com/viking_education/web_development/web_app_eng/css_box_model_chrome.png)

* Content - The content of the box, where text and images appear
* Padding - Clears an area around the content. The padding is transparent
* Border - A border that goes around the padding and content
* Margin - Clears an area outside the border. The margin is transparent



The CSS box-sizing
property allows us to include the padding and border in an element’s total width and height.
You can use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size and the size of the box is relative to the size of the browser window when you use percentages.
When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens.
* width: width + padding + border = actual width of an element
* height: height + padding + border = actual height of an element
# Why we use boxes elements?
* border-width:it controls the width of a border.
* border-style:it controls the style of a border using the border-style property.
* border-color: it specifies the color of a border using either RGB values, hex codes or CSS color names.
* padding:it specifies how much space should appear between the content of an element and its border.
* margin:it controls the gap between boxes.

# javascript

## Java Switch Statements

Use the switch statement to select one of many code blocks to be executed.

Syntax

![switch syntax](https://www.bookofnetwork.com/images/javascript-images/JS_switch-syntax_20Sep16_1827.png)




# This is how it works:

* The switch expression is evaluated once.
* The value of the expression is compared with the values of each case.
* If there is a match, the associated block of code is executed.
* The break and default keywords are optional.



# Why do we have to use break in switch?
In switch case, the break statement is used to terminate the switch case. Basically it is used to execute the statements of a single case statement. If no break appears, the flow of control will fall through all the subsequent cases until a break is reached or the closing curly brace '}' is reached.
