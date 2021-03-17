# chapter 5
## image 

Images can improve the design and the appearance of a web page.
The HTML <img> tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The <img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image
Syntax
<img src="url" alt="alternatetext">
The src Attribute
The required src attribute specifies the path (URL) to the image.

Note: When a web page loads; it is the browser, at that moment, that gets the image from a web server and inserts it into the page. Therefore, make sure that the image actually stays in the same spot in relation to the web page, otherwise your visitors will get a broken link icon. The broken link icon and the alt text are shown if the browser cannot find the image.

Example
<img src="" alt="Flowers in Chania">

![image](https://www.wikihow.com/images/thumb/b/be/Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-3-Version-3.jpg.webp)

** Chapter Summary **
- Use the HTML <img> element to define an image
- Use the HTML src attribute to define the URL of the image
- Use the HTML alt attribute to define an alternate text for an image   if it cannot be displayed
- Use the HTML width and height attributes or the CSS width and height  properties to define the size of the image
- Use the CSS float property to let the image float to the left or to the right
Note: Loading large images takes time, and can slow down your web page. Use images carefully
[example](https://www.w3schools.com/html/html_images.asp)

# chapter 11
# color

Colors are very important to give a good look and feel to your website. You can specify colors on page level using <body> tag or you can set colors for individual tags using bgcolor attribute.

The <body> tag has following attributes which can be used to set different colors −

bgcolor − sets a color for the background of the page.

text − sets a color for the body text.

alink − sets a color for active links or selected links.

link − sets a color for linked text.

vlink − sets a color for visited links − that is, for linked text that you have already clicked on.

HTML Color Coding Methods
There are following three different methods to set colors in your web page −

Color names − You can specify color names directly like green, blue or red.

Hex codes − A six-digit code representing the amount of red, green, and blue that makes up the color.

Color decimal or percentage values − This value is specified using the rgb( ) property.

Now we will see these coloring schemes one by one.

HTML Colors - Color Names
You can specify direct a color name to set text or background color. W3C has listed 16 basic color names that will validate with an HTML validator but there are over 200 different color names supported by major browsers.

Note − Check a complete list of HTML Color Name.

W3C Standard 16 Colors
Here is the list of W3C Standard 16 Colors names and it is recommended to use them.
![color](https://cdn.educba.com/academy/wp-content/uploads/2019/12/HTML-Colors-.png)
Example
Here are the examples to set background of an HTML tag by color name −

Live Demo
<!DOCTYPE html>
<html>

   <head>
      <title>HTML Colors by Name</title>
   </head>
	
   <body text = "blue" bgcolor = "green">
      <p>Use different color names for for body and table and see the result.</p>
      
      <table bgcolor = "black">
         <tr>
            <td>
               <font color = "white">This text will appear white on black background.</font>
            </td>
         </tr>
      </table>
   </body>
   
</html>
HTML Colors - Hex Codes
A hexadecimal is a 6 digit representation of a color. The first two digits(RR) represent a red value, the next two are a green value(GG), and the last are the blue value(BB).

A hexadecimal value can be taken from any graphics software like Adobe Photoshop, Paintshop Pro or MS Paint.

Each hexadecimal code will be preceded by a pound or hash sign #. Following is a list of few colors using hexadecimal notation.
![rgb](https://i0.wp.com/codeexercise.com/wp-content/uploads/2017/12/HTMLcolors.png?resize=298%2C248&ssl=1)

# chapter 12
## text
** The p tag **
This tag defines a paragraph of text.

<p>Some text</p>
It’s a block element.Inside it, we can add any inline element we like, like span or a. We cannot add block elements.We cannot nest p elements one into another.
By default browsers style a paragraph with a margin on top and at the bottom. 16px in Chrome, but the exact value might vary between browsers.
This causes two consecutive paragraphs to be spaced, replicating what we think of a “paragraph” in printed text.

The heading tags
HTML provides us 6 heading tags. From most important to least important, we have h1, h2, h3, h4, h5, h6.

Typically a page will have one h1 element, which is the page title. Then you might have one or more h2 elements depending on the page content.

Headings, especially the heading organization, are also essential for SEO, and search engines use them in various ways.

The browser by default will render the h1 tag bigger, and will make the elements size smaller as the number near h increases:
![text](https://flaviocopes.com/html-text-tags/headings.png)
