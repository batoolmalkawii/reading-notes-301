# Explore the Tech!

In today's blog, I am going to discuss some topics related to ***web development*** in _CSS_. So, _let's get started!_

## 1. ***Responsice Web Design (RWD)***:

Responsive web design is the practice of building a website suitable to work on _every_ device and _every_ screen size, no matter how large or small, mobile or desktop.
Responsive generally means to **react** quickly and positively to any change, while adaptive means to be easily **modified** for a new purpose or situation, such as change.
Currently the most popular technique lies within _responsive web design_, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, **responsive**, **adaptive**, and **mobile**.

Responsive web design is broken down into three main components, described as follows:
* ***Flexible Layouts:*** the practice of building the layout of a website with a **flexible grid**, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly `percentages` or `em` units. These relative lengths are then used to declare common grid property values such as `width`, `margin`, or `padding`.
    ##### Flexible Grid: 
    Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units.
    
* ***Media Queries:*** Media queries provide the ability to specify different styles for individual browser and device circumstances.
    ##### Initializing Media Queries:
     * `@media` rule inside of an existing style sheet (RECOMMENDED to avoid any additional HTTP requests).
     * importing a new style sheet using the `@import` rule.
     * linking to a separate style sheet from within the HTML document.
    ##### Logical Operators in Media Queries:
    Logical operators in media queries help build powerful expressions. There are three different logical operators available for use within media queries, including `and`, `not`, and `only`.
    ##### Media Features in Media Queries:
    Media features identify what **attributes** or **properties** will be targeted within the media query expression. Examples are as follows:
    * `width`, `height`.
    * `orientation`: `landscape`, `portrait`.
    * `aspect-ratio`.
    * `resolution`.
    * `color`, `monochrome`, `grid`.
    
* ***Flexible Media:*** One quick way to make media scalable is by using the `max-width` property with a value of `100%`. Doing so ensures that as the viewport gets smaller any media will scale down according to its containers width.




## 2. ***All About floats***:

The `float` property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. This can be `float:right` or `float-left`. Furthermore, float can be cleared using the `clear` property, the values can be `left`, `right`, `both` and `none`. To create multi-column layouts with floats, The following three CSS properties are used to position the columns next to each other:
* `width`: sets the width of the columns.
* `float`: positions the columns next to each other.
* `margin`: creates a gap between the columns.



## 3. ***Grids***:
An appropriate way to build grids in websites is as follows: 
* Creating context with `width: 100%`. (container).
* Creating to columns floating to `left` with `width 66.6%` and `right` with `width 33.3%` (percentages make the grid flexible).
* Clearing the context. 
* Gutters: `box-sizing: border-box`, fixed `padding`, 



## 4. ***Scalable and Modular architecture for CSS (SMACSS)***:
SMACSS is a way to _examine_ your design process and as a way to fit those rigid frameworks into a _flexible_ thought process. It is an attempt to _documen_t a consistent approach to site development when using CSS. 
