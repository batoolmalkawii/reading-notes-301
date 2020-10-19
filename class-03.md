# Explore the Tech!
In today's blod, I am going to discuss some topics related to _we development_. So, _let's get started!_


### 1. Templating with Mustache:
Javascript templating is a fast and efficient technique to **render** client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
The template engine replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.

***Mustache*** is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.
It is often referred to as ***“logic-less”*** because there are no if statements, else clauses, or for loops. Instead, there are only _tags_.
`mustache.js` is an implementation of the mustache template system in JavaScript. 
Also, mustache supports various languages, we _don’t_ need a separate templating system on the server side.
Example: `Mustache.render(“Hello, {{name}}”, { name: “Batool” });` => {{name}} is a **placeholder**
