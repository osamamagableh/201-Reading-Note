# class02
## Chapter 2 HTML and CSS
### Text 
Text contain many type in HTML web pages like :
* Heading
* Paragraphs
Now let us talk about heading :

there is **6** type of headers
h1 , h2, ... , h6 
**h1** called the main heading
in figure bellow will show the different btween headers 

![Different headers](https://karoku.com/wp-content/uploads/2019/02/Heading-Tag-Hierarchy.jpg)

Now we will talk about paragraphs :
**what is the meaning of paragraph ?**
paragraph consists of one or more sentences that form a self-contained unit of discourse. The start of a paragraph is indicated by a new line . 

**How I can create paragraph ?**
To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag

for Example : 
<p> My name is Osama Magableh , I'm 23 years old , I was graduation from JUST with Computer Engineer </p>

this is paraghraph contane many sentenses about my self .

I can do many things in paragraphs like : change font to bold by using <b>this will appear bold </b>
also i can put it in italic by using <i>this will appear italic </i>

for Example :
<p> My name is <b>Osama Magableh</b> , I'm 23 years old , I was graduation from JUST with <i>Computer Engineer</i> </p>
 the word Osama Magableh will be bold and  computer Engineer will be italic .

we can apply **Superscript and Subscrip** for our word in paragraph by using <sub> and <sup>

The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or 
mathematical concepts like raising a number to a power .

The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas .

**White space**

When the browser comes across two or more spaces next to each other, it only displays one space. 
Similarly if it comes across a line break, it treats that as a single space too. This is known as 
white space collapsing.

As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag <br />

when you create HTML page usually have two views of the page you are creating: a visual editor and a 
code view. 
**1. visual editor**:
often resemble word processors. Although each editor will differ slightly, there are some features that 
are common to most editors that allow you to control the presentation of text.

![visual editor](https://i.ytimg.com/vi/yAg7KpK1xws/maxresdefault.jpg)

**2. code view**:
show you the code created by the visual editor so you can manually edit it, or so you can just enter new code 
yourself. It is often activated using a button with an icon that says HTML or has angled brackets. White space may be added to the code by the editor to make the code easier to read .
![code view](https://i.stack.imgur.com/PnZ4G.png)

**Strong  Emphasis**

The use of the <strong>element indicates that its content has strong importance. For example, the words 
contained in this element might be said with strong emphasis.
By default, browsers will show the contents of a <strong>element in bold.

The <em> element indicates emphasis that subtly changes the meaning of a sentence.
By default browsers will show the contents of an <em> element in italic.

**Qutations**
For Qutations we use <blockquote> Or <q>
* blockquote

The <blockquote> element is used for longer quotes that take up an entire paragraph. Note 
how the <p> element is still used inside the <blockquote>element. 
Browsers tend to indent the contents of the <blockquote>element, however you should not use this element just to indent a piece of text — rather you should achieve this effect using CSS.

* q

The <q> element is used for shorter quotes that sit within a paragraph. Browsers are supposed to put quotes around the <q> element, however Internet Explorer does not — therefore many people avoid using the <q> element.


## chapter 10 HTML and CSS
### Introducing CSS

Waht is the meaning of CSS :
CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

We can use CSS to style our pages like : font size , font color , background color , images 

There is three way to disgin our pages by using css 
1. inline style :
we can do that by put the css inside the opening of tag .
EX : <p style "color : red";>

2. internal style : 
we can do that by put our css in the style tag .
<style> 
p{
    color : red;
}
</style>

3. external style :
Make a new file with extention css and link it in the head tag.
EX :<link href="css/styles.css" type="text/css" rel="stylesheet" />

in css file we can use selectors to git what we want 

figure bellow show the selectotrs :
![Selectors](https://i.pinimg.com/originals/bc/97/96/bc97965579512f8a6d2303934f599c65.png)

## chapter 2 JS
### introduction to js

if we want to write a code in JS we have to know the sentaxe of them

to declare a variable we use :
var name_of_variable = value ;
Ex : var age = 23;

**Data type**
in JS there is just 3 type of data type :
1. Number : contain numbers positive or negative like : 1 , -2 , 1.5
2. srting : contain words like : Osama , Naser 
3. boolean : contain just 2 type : true , false 

** the role of naming varable :
1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you 
must not use a dash(-) or a period (.) in a variable name. 
3. You cannot use keywords or reserved words. Keywords are special words that tell the 
interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
4. All variables are case sensitive, so score and Score would be different variable names, but 
it is bad practice to create two variables that have the same name using different cases.
5. Use a name that describes the kind of information that the variable stores. For example, 
fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age
6. If your variable name is made up of more than one word, use a capital letter for the first letter of 
every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred 
to as camel case). You can also use an underscore between each word (you cannot use a dash)

**CREATING AN ARRAY**
y You create an array and give it a name just like you would any other variable (using the var 
keyword followed by the name of the array). 
The values are assigned to the array inside a pair of square brackets, and each value is 
separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.  

Ex : 
var colors; 
colors ['white', 'black', ' custom']; 
var el document.getElementByld('col ors'); 
el . textContent = col ors[O]; 

**EXPRESSIONS**

An expression evaluates into (results in) a single value. Broadly speaking 
there are two types of expressions. 

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
ex : var x = 5;
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
ex : var area = 5*6;

**Operator**
JavaScript contains the following mathematical operators, which you can use with numbers. 

![OPerotor](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Arithmatic-Operators.png)

## chapter 4 JS

### Decisions and Loops

There are four equality algorithms in ES2015:

Abstract Equality Comparison (==)
Strict Equality Comparison (===): used by Array.prototype.indexOf, Array.prototype.lastIndexOf, and case-matching
SameValueZero: used by %TypedArray% and ArrayBuffer constructors, as well as Map and Set operations, and also String.prototype.includes and Array.prototype.includes since ES2016
SameValue: used in all other places
JavaScript provides three different value-comparison operations:

=== - Strict Equality Comparison ("strict equality", "identity", "triple equals")
== - Abstract Equality Comparison ("loose equality", "double equals")
Object.is provides SameValue (new in ES2015).
Which operation you choose depends on what sort of comparison you are looking to perform. Briefly:

double equals (==) will perform a type conversion when comparing two things, and will handle NaN, -0, and +0 specially to conform to IEEE 754 (so NaN != NaN, and -0 == +0);
triple equals (===) will do the same comparison as double equals (including the special handling for NaN, -0, and +0) but without type conversion; if the types differ, false is returned.
Object.is does no type conversion and no special handling for NaN, -0, and +0 (giving it the same behavior as === except on those special numeric values).
Note that the distinction between these all have to do with their handling of primitives; none of them compares whether the parameters are conceptually similar in structure. For any non-primitive objects x and y which have the same structure but are distinct objects themselves, all of the above forms will evaluate to false.

**logical Operators**
 we can use these logical operators in the exprestions 
 Ex: (a>b)&&(c<d)

![Logical Operators](https://media.geeksforgeeks.org/wp-content/uploads/Operators.png)

**IF statment**
Very often when you write code, you want to perform different actions for different decisions.
You can use conditional statements in your code to do this.
In JavaScript we have the following conditional statements:
Use if to specify a block of code to be executed, if a specified condition is true
Use else to specify a block of code to be executed, if the same condition is false

**syntax**
if (condition) {
  //  block of code to be executed if the condition is true
} else {
  //  block of code to be executed if the condition is false
}
