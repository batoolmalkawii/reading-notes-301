# Explore the Tech!
In today's blog, I am going to discuss several topics related to _web development_. So, _let's get started!_


### 1. jQuery:
jQuery offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed, such as the following:
* Select elements.
* Perform tasks.
* Handle events.

jQuery is a javascript file that is included in the webpage. it let's you find elements using CSS-style selectors, and then do something with the elements using **jQuery** methods. There are several benefits for using jQuery, described as follows:
* Simple selectors.
* Common tasks in less code.
* Cross-browser compatibility.


  ##### Looping in jQuery:
  With jQuery, when a selector returns multiple elements, you can update all of them using the one method. There is no need to use a loop.
  ##### Chaining in jQuery:
  If you want to use more than one jQuery method on the same selection of elements, you can list several methods at a time using dot notation to separate each one.
  The process of placing several methods in the same selector is referred to as chaining. It results in code that is far more compact.
  `$( 'l i [i d!="one"] ') . hide() .delay(SOO) . fadeln(1400);`
  ##### Getting element content: 
  `.text`: content only.
  `.html`: content + html code within.
  ##### Adding content:
  `.append`, `.preappend`, `before`, `after`.
  ##### Updating elements:
  `.text`, `.html`, `.replacewith`, `.remove`.
  ##### Inseting content:
  1: Create the new elements in a jQuery object.
  2: Use a method to insert the content into the page. `.append`.., etc.
  ##### Getting and setting attribute values:
  `.attr()`, `.removeAttr()`, `.addClass()`, `.removeClass`.
  ##### Getting and setting CSS properties:
  `.css()`.
  
  
  ### Including jQuery in file in code:
  When a page loads jQuery from a CDN, you will often see a syntax like the one shown below. It starts with a `<script>` tag that tries to load the jQuery file from the CDN. But note that the URL for the script starts with two forward slashes (not http:). This is known as a **protocol relative URL**. If the user is looking at the current page through https, then they will not see an error that tells them there are unsecure items on the page.
  The _position_ of <script> elements can affect how quickly a web page seems to load.
  
  ### Plugins in jQuery:
  Plugins are scripts that extend the functionality of the jQuery library. Hundreds have been written and are available for you to use.
  Plugins are written so that new methods extend the jQuery object and can, therefore, be used on a jQuery selection. As long as you know how to do the following with jQuery:
  * Make a selection of elements.
  * Call a method and use parameters.
  
### 2. Pair Programming:
Pair programing is a technique used to foster a collaborative environment while developing key industry skills, and it is used commonly in many agile work environments.
pair programming involves two roles: 
* Driver: the programmer who is typing and the only one whose hands are on the keyboard. Manages the text editor, switching files, version control, awriting—code.
* Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. 
Using pai programming touches on all four skills (speaking, listening, reading and writing): _developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves._

The following are reasons _why_ you should do _pair programming_:
1. Greater efficiency.
2. Engaged collaboration
3. Learning from fellow students.
4. Social skills.
5. Job interview readiness.
6. Work environment readiness.

