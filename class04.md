# chapter 4
## links 
Hyperlinks, usually called links, are a foundational concept behind the Web. To explain what links are, we need to step back to the very basics of Web architecture.

Back in 1989, Tim Berners-Lee, the Web's inventor, spoke of the three pillars on which the Web stands:
1. URL, an address system that keeps track of Web documents. 
2. HTTP, a transfer protocol to find documents when given their URLs
3. HTML, a document format allowing for embedded hyperlinks

As you can see in the three pillars, everything on the Web revolves around documents and how to access them. The Web's original purpose was to provide an easy way to reach, read, and navigate through text documents. Since then, the Web has evolved to provide access to images, videos, and binary data, but these improvements have hardly changed the three pillars.

Before the Web, it was quite hard to access documents and move from one to another. Being human-readable, URLs already made things easier, but it's hard to type a long URL whenever you want to access a document. This is where hyperlinks revolutionized everything. Links can correlate any text string with a URL, such that the user can instantly reach the target document by activating the link.

![link](https://helpx.adobe.com/content/dam/help/en/dreamweaver/how-to/make-hyperlink/_jcr_content/main-pars/image1/create-hyperlink-step2b.jpg)

![img](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_hyperlinks/link-1.png)

Types of links
Internal link
A link between two webpages, where both webpages belong to the same website, is called an internal link. Without internal links, there's no such thing as a website (unless, of course, it's a one-page website).
External link
A link from your webpage to someone else's webpage. Without external links, there is no Web, since the Web is a network of webpages. Use external links to provide information besides the content available through your webpage.
Incoming links
A link from someone else's webpage to your site. It's the opposite of an external link. Note that you don't have to link back when someone links to your site.
When you're building a website, focus on internal links, since those make your site usable. Find a good balance between having too many links and too few. We'll talk about designing website navigation in another article, but as a rule, whenever you add a new webpage, make sure at least one of your other pages links to that new page. On the other hand, if your site has more than about ten pages, it's counter-productive to link to every page from every other page.

When you're starting out, you don't have to worry about external and incoming links as much, but they are very important if you want search engines to find your site (see below for more details).

[example link](https://www.w3schools.com/html/html_links.asp)

# chapter 15 
## layout
HTML layouts provide a way to arrange web pages in well-mannered, well-structured, and in responsive form or we can say that HTML layout specifies a way in which the web pages can be arranged. Web-page layout works with arrangement of visual elements of an HTML document.

Web page layout is the most important part to keep in mind while creating a website so that our website can appear professional with the great look. You can also use CSS and JAVASCRIPT based frameworks for creating layouts for responsive and dynamic website designing.
![layout](https://static.javatpoint.com/htmlpages/images/html-layouts.png)

** Following are different HTML5 elements which are used to define the different parts of a webpage. **

1. <header>: It is used to define a header for a document or a       section.
2. <nav>: It is used to define a container for navigation links
3. <section>: It is used to define a section in a document
4. <article>: It is used to define an independent self-contained article
5. <aside>: It is used to define content aside from the content (like a sidebar)
6. <footer>: It is used to define a footer for a document or a section
7. <details>: It is used to define additional details
8. <summary>: It is used to define a heading for the <details> element

example:
Example:
<nav style="background-color:#bcdeef;">  
        <h1 style="text-align: center;">Navgation Links</h1>  
        <ul>  
            <li><a href="#">link1</a></li>  
            <li><a href="#">link2</a></li>  
            <li><a href="#">link3</a></li>  
            <li><a href="#">link4</a></li>  
        </ul>  
    </nav>  

# chapter 3 java
## js function 
JavaScript function objects are used to define a piece of JavaScript code. This code can be called within a JavaScript code as and when required.
Can be created by function constructor.
Code defined by a function can be called by function().

The arguments array is a local variable available within all function objects as function's arguments; arguments as a property of a function is no longer used.
This array contains an entry for each argument passed to the function.

For example, if a function passes three arguments, you can refer to the arguments as follows :
arguments[0]
arguments[1]
arguments[2]

The arguments array can also be declared with a function name :
myfunc.arguments[0]
myfunc.arguments[1]
myfunc.arguments[2]
Where myfunc is the name of the function.

The arguments array is available only within a function body. Attempting to access the arguments array outside a function declaration results in an error

[example of function in java](https://www.w3resource.com/javascript/object-property-method/function.php)
