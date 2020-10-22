# Explore the Tech!
In today's blog, I am going to discuss some topics related to _web development_. So, _let's get started!_

## Node.js

Node.js® is a JavaScript runtime built on Chrome’s V8 JavaScript engine. Basically, it a program we can use to execute JavaScript on our computers.
The V8 engine is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi.
It was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.
`npm`, a package manager that comes bundled with Node.

`.js` files use Node’s built-in console module to display a message in a terminal window.
Example: `node hello.js`

Node.js Has Excellent Support for **Modern JavaScript**. Node has excellent support for ECMAScript 2015 (ES6) and beyond.
As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can write your JavaScript using the latest and most modern syntax. 
It also means that you don’t generally have to worry about _compatibility issues_ — as you would if you were writing JavaScript that would run in different browsers.

 Node comes bundled with a package manager called npm. To check which version you have installed on your system, type npm -v.

In addition to being the package manager for JavaScript, npm is also the world’s **largest software registry***. There are over 1,000,000 packages of JavaScript code available to download, with billions of downloads per week.

#### Node.js use cases:
1. For anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.
2. Lets Us Run JavaScript on the Server.
3. As a scripting language to automate repetitive or error prone tasks on your PC. 
4. Write your own command line tool, such as this Yeoman-Style generator to scaffold out new projects.

Node.js is **single-threaded** and **event-driven**, which means that everything that happens in Node is in reaction to an _event_.
- For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a _callback_ before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.

#### Node.js execution model:
1. Node apps pass async tasks to the event loop, along with a callback.
2. The event loop efficiently manages a thread pool and executes taks efficiently.
3. Executes each task as callback executes.

### What Node.js is suited to?
1. applications that require some form of real-time interaction or collaboration — for example, chat sites, or apps such as CodeShare.
2. APIs where you’re handling lots of requests that are I/O driven (such as those needing to perform operations on a database).
3. Sites involving data streaming, as Node makes it possible to process files while they’re still being uploaded.

### Node.js advantages:
* Speed and scalability.
* You can do everything in the same language.
* It speaks JSON. JSON is probably the most important data exchange format on the Web.
* JavaScript is ubiquitous.
