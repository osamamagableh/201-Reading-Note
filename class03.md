# Reading_03
## Chapter 3 : list (HTML)
we have three different type of list in HTML :
1. Ordered : a list where all items in the list numberd 
2. UnOrderd : a list where items begin a bullt point 
3. Definition lists : are made up of a set of terms along with the definitions for each of those terms.

**Syntax**
1. Ordedrd list :
```
<ol>
  <li>item1</li>
  <li>item2</li>
  <li>item3</li>
</ol>
```

2. UnOrderd list :
```
<ul>
  <li>item1</li>
  <li>item2</li>
  <li>item3</li>
</ul>
```

3. Definition lists
```
<dl>
  <dt>item1</dt>
  <dd>discription</dd>
  <dt>item2</dt>
  <dd>discription</dd>
</dl>
```
**also we can use Nested Lists :
ex : 
```
<ul>
    <li>Mousses</li>
    <li>Pastries
      <ul>
        <li>Croissant</li>
        <li>Mille-feuille</li>
        <li>Palmier</li>
        <li>Profiterole</li>
        </ul>
    </li>
    <li>Tarts</li>
</ul>
```
this Example show us the output for lists:

![List](https://www.dummies.com/wp-content/uploads/280304.image0.jpg);

## Chapter 13 : Boxes (HTML)

We can set several properties that affect the appearance ofthese boxesalso we can :
Control the dimensions of our boxes
Create borders around boxes
Set margins and padding for boxes
Show and hide boxes

we can control the dimensions of our boxes by using :
1. wight 
2. hight 

**Limiting Width and Hight**
Some page designs expand and shrink to fit the size of the user's screen so we can use :
max-wight : to specifies the bigest wight a box can be displayed
min-width : specifies the smallest wight a box can be displayed
max-hight :to specifies the bigest hight a box can be displayed
min-hight :specifies the smallest hight a box can be displayed

**Overflowing Content**
The overflow property tells the browser what to do if the content contained within a box is larger
than the box itself. It can have one of two values:
- hidden : This property simply hides any extra content that does not fit in the box.
- scroll : This property adds a scrollbar to the box so that users can scroll to see the missing content

**Shorthand**
border : The border property allows you to specify the width, style and
color of a border in one property (and the values should be coded in that specific order).

padding : The padding property allows you to specify how much space
should appear between the content of an element and its border.

margin : The margin property controls the gap between boxes. Its value is commonly given in pixels,
although you may also use percentages or ems.

**Change Inline/Block**
display : The display property allows you to turn an inline element into a block-level element or vice
versa, and can also be used to hide an element from the page.
the value of display contain on of :
1. inline :This causes a block-level element to act like an inline element.
2. block :This causes an inline element to act like a block-level element
3. inline-block :This causes a block-level element to flow like an inline
element, while retaining other features of a block-level element.
4. none : This hides an element from the page. In this case, the element acts as though it is not on the
page at all (although a user could still see the content of the box if they used the view source option
in their browser).

this Example contant what we can do in boxes :
```
<!DOCTYPE html>
<html>
<head>
<title>Boxes</title>
<style type="text/css">
body {
font-size: 80%;
font-family: "Courier New", Courier, monospace;
letter-spacing: 0.15em;
background-color: #efefef;}
#page {
max-width: 940px;
min-width: 720px;
margin: 10px auto 10px auto;
padding: 20px;
border: 4px double #000;
background-color: #ffffff;}
#logo {
width: 150px;
margin: 10px auto 25px auto;}
ul {
width: 570px;
padding: 15px;
margin: 0px auto 0px auto;
border-top: 2px solid #000;
border-bottom: 1px solid #000;
text-align: center;}
li {
display: inline;
margin: 0px 3px;}
p {
text-align: center;
width: 600px;
margin: 20px auto 20px auto;
font-weight: normal;}
a {
color: #000000;
text-transform: uppercase;
text-decoration: none;
padding: 6px 18px 5px 18px;}
a:hover, a.on {
color: #cc3333;
background-color: #ffffff;}
</style>
</head>
<body>
<div id="page">
<div id="logo">
<img src="images/logo.gif" alt="The Analog Specialists" />
</div>
<ul id="navigation">
<li><a href="#" class="on">Home</a></li>
<li><a href="#">For Sale</a></li>
<li><a href="#">Repairs</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
</ul>
<p>
<img src="images/keys.jpg" alt="Fender Rhodes, Hohner Clavinet,
and Wurlitzer EP200" />
</p>
<p>
We specialise in the sales and repair of classic keyboards, in particular
the Fender Rhodes, Wurlitzer EP200, and Hohner Clavinet.
</p>
</div>
</body>
</html>
```
## chapter 2 and 4 : JS

### SWITCH STATEMENTS

A switch statement starts with a variable called the switch value. Each case indicates a possible
value for this variable and the code that should run if the variable matches that value.

**Syntax**
```
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```
**How does it work**
1. The switch expression is evaluated once
2. The value of the expression is compared with the values of each case.
3. If there is a match, the associated block of code is executed.
4. If there is no match, the default code block is executed.

Example :
```
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
     day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}
```
JavaScript is said to use weak typing because the data type for a value can change. Some
other languages require that you specify what data type each variable will be. They are
said to use strong typing.

**Loop**

For loop : loops through a block of code a number of times

**syntax** 
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

do/while : loops through a block of code once, and then repeats the loop while a specified condition is true

**syntax** 
do {
  code block to be executed
}
while (condition);

Example of loop :
```
let i = 1;
const n = 5;
// do...while loop from 1 to 5
do {
    console.log(i);
    i++;
} while(i <= n);

```
