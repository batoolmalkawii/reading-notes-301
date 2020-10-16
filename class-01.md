# Explore the Tech!

In today's blog, I am going to discuss some topics related to ***web development*** in _CSS_. So, _let's get started!_

1. Responsice Web Design (RWD):
Responsive web design is the practice of building a website suitable to work on _every_ device and _every_ screen size, no matter how large or small, mobile or desktop.
Responsive generally means to **react** quickly and positively to any change, while adaptive means to be easily **modified** for a new purpose or situation, such as change.
Currently the most popular technique lies within _responsive web design_, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being all three, **responsive**, **adaptive**, and **mobile**.

Responsive web design is broken down into three main components, described as follows:
* Flexible Layouts: the practice of building the layout of a website with a **flexible grid**, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly `percentages` or `em` units. These relative lengths are then used to declare common grid property values such as `width`, `margin`, or `padding`.
    ##### Flexible Grid: 
    Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units.
    
* Media Queries: Media queries provide the ability to specify different styles for individual browser and device circumstances.
    ##### Initializing Media Queries:
     * `@media` rule inside of an existing style sheet (RECOMMENDED to avoid any additional HTTP requests).
     * importing a new style sheet using the `@import` rule.
     * linking to a separate style sheet from within the HTML document.

