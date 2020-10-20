# Explore the Tech! 
In today's blog, I am going to discuss some topics related to _web development_. So, _let's get started!_


### 1. Grids in CSS:
The CSS **Grid Layout** Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
A grid layout consists of a parent element, with one or more child elements.
An HTML element becomes a grid container when its display property is set to grid or inline-grid.
* Example: 
```
.grid-container {
  display: grid;
}
```

All direct children of the grid container automatically become _grid items_.
The vertical lines of grid items are called **columns**.
The horizontal lines of grid items are called **rows**.
The spaces between each column/row are called **gaps**.

- You can adjust the gap size by using one of the following properties:
`grid-column-gap`: sets the gap between the columns.
`grid-row-gap`: sets the gap between the rows.
`grid-gap`: is a shorthand property for the grid-row-gap and the grid-column-gap properties.

The lines between columns are called **column lines**.

The lines between rows are called **row lines**.
Refer to line numbers when placing a grid item in a grid container:










