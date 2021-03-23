# chapter 7 in html book
## forms 

** HTML Form **
An HTML form is a section of a document which contains controls such as text fields, password fields, checkboxes, radio buttons, submit button, menus etc.

An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc. 
HTML borrows the concept of a form to refer to different 
elements that allow you to collect information from visitors to 
your site.
Whether you are adding a simple search box to your website or 
you need to create more complicated insurance applications, 
HTML forms give you a set of elements to collect data from 
your users

** Why use HTML Form? **
HTML forms are required if you want to collect some data from of the site visitor.
For example: If a user want to purchase some items on internet, he/she must fill the form such as shipping address and credit/debit card details so that item can be sent to the given address.
<form action="server url" method="get|post">  
  //input controls e.g. textfield, textarea, radiobutton, button  
</form>

![form](https://www.seoclerk.com/pics/433240-1e1xvh1456640064.png)

** HTML Form Elements **
Tag	Description
- <form>	Defines an HTML form for user input
- <input>	Defines an input control
- <textarea>	Defines a multiline input control (text area)
- <label>	Defines a label for an <input> element
- <fieldset>	Groups related elements in a form
- <legend>	Defines a caption for a <fieldset> element
- <select>	Defines a drop-down list
- <optgroup>	Defines a group of related options in a drop-down list
- <option>	Defines an option in a drop-down list
- <button>	Defines a clickable button
- <datalist>	Specifies a list of pre-defined options for input controls
- <output>	Defines the result of a calculation
![image](https://www.htmlgoodies.com/img/2010/06/HTML-Forms-From-Basics-to-Style-Layouts-Figure2.gif)



# chapter 14 
# Lists, Tables and forms

** The three basic elements that make up the table **
- table: the scope of the table, the outer frame; used to define the  table. The other elements of the table are contained in the table tag.
- tr: the row of the table.
- td: Column (cell) of the table.

th element: add a header row to the table. The th element is used to define the header cell of the table. It is a child element of the tr element and must be placed in the tr tag. The content of the tr element will automatically be center aligned and bold text.

** Table properties **

- border table line
- bordercolor The color of the table line
- cellspacing: margins. The distance between cells.
- cellpadding: padding. The property is used to set the table cell fill (distance from content to border).
- width The width of the table
- height The height of the table
- align: horizontal alignment: left: left alignment; center: center - - alignment; right: right alignment
- background: The property is used to set the background image of the table. You can repeat the form as many times as you like, but don’t use the extra parts.
- bgcolor: set the background color of the table
- td attribute: valign: vertical alignment top: top alignment; middle: center alignment; bottom: bottom alignment

<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>form</title>
	</head>
	<body>
		<table border="20" cellspacing="50" cellpadding="50">
			<tr>
				<td>Cell</td>
				<td>Cell</td>
			</tr>
			<tr>
				<td>Cell</td>
				<td>Cell</td>
			</tr>
		</table>
	</body>
</html>
List
The container is loaded with a structure, a form of text or graphics in a consistent style, called a list.

Unordered list
The unordered list consists of ul tags and li tags. Use the ul tag as the declaration of the unordered list and use the li tag as the start of each list item. Follow W3C standards,ul tags can only nest li tags，Any tag can be nested in li tag。

Shortcut key: Enter an unordered list of 9 columns:ul>li*9 Tab key

<ul>
	<li>Item 1</li>
	<li>Item 2</li>
	<li>Item 3</li>
</ul>

![img](https://software-solutions-online.com/wp-content/uploads/2014/07/database1.png)

# chapter 6 in java book 
## event 
Events are the browser's way of indicating when 
something has happened (such as when a page has 
finished loading or a button has been clicked). 
Binding is the process of stating which event you are 
waiting to happen, and which element you are waiting 
for that event to happen upon. 
When an event occurs on an element, it can trigger a 
JavaScript function. When this function then changes 
the web page in some way, it feels interactive because 
it has responded to the user. 
You can use event delegation to monitor for events 
that happen on all of the children of an element. 
The most commonly used events are W3C DOM 
events, although there are others in the HTMLS 
specification as well as browser-specific events. 

Event         	Description
- onchange	    An HTML element has been changed
- onclick	    The user clicks an HTML element
- onmouseover	The user moves the mouse over an HTML element
- onmouseout	The user moves the mouse away from an HTML element
- onkeydown	    The user pushes a keyboard key
- onload       	The browser has finished loading the page
![event](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)
