# Explore the Tech!
In today's blog, I am going to discuss some topics related to _web development_. So, _let's get started!_


## 1. EJS:


 - ### Use EJS to Template Your Node Application:
 
  - EJS Partials `footer.ejs`, `head.ejs`, `header.ejs`:
   -  call those partials and define three files we'll use across all of our site: head.ejs, header.ejs, and footer.ejs

```   
<!-- views/partials/head.ejs -->
<meta charset="UTF-8">
<title>Super Awesome</title>
<!-- CSS (load bootstrap from a CDN) -->
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<style>
    body    { padding-top:50px; }
</style>
<!-- views/partials/header.ejs -->
<nav class="navbar navbar-default" role="navigation">
<div class="container-fluid">
    <div class="navbar-header">
        <a class="navbar-brand" href="#">
            <span class="glyphicon glyphicon glyphicon-tree-deciduous"></span>
            EJS Is Fun
        </a>
        <ul class="nav navbar-nav">
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
        </ul>
    </div>
</div>
</nav>
<!-- views/partials/footer.ejs -->
<p class="text-center text-muted">© Copyright 2014 The Awesome People</p>
```

- Using EJS Partials :
  -  The syntax to use an EJS partial is: `<% include FILENAME %>`.
- Single Variable:
  - To echo a single variable, we just use `<%= tagline %>`.
  
- Looping Over Data
  - To loop over our data, we will use .forEach

 ---------
 ## 2. Using the API:
 
  - Here's how to determine which of those options to use:
   1. If the request requires authorization (such as a request for an individual's private data), then the application must provide an OAuth 2.0 token with the request.
    -The application may also provide the API key, but it doesn't have to.
  2. If the request doesn't require authorization (such as a request for public data), then the application must provide either the API key or an OAuth 2.0 token, or both—whatever option is most convenient for you.
  
  - Authorizing requests with OAuth 2.0:
   1. When you create your application, you register it using the Google API Console. Google then provides information you'll need later, such as a client ID and a client secret.
   2. Activate the Books API in the Google API Console.
   3. When your application needs access to user data, it asks Google for a particular scope of access.
   4. Google displays a consent screen to the user, asking them to authorize your application to request some of their data.
   5. If the user approves, then Google gives your application a short-lived access token.
   6. Your application requests user data, attaching the access token to the request.
   7. If Google determines that your request and the token are valid, it returns the requested data.
   
   - Here's the OAuth 2.0 scope information for the Books API: [link](https://www.googleapis.com/auth/books)
   
  - Acquiring and using an API key:
   1. Open the Credentials page in the API Console.[link](https://console.developers.google.com/apis/credentials?pli=1)
   2. This API supports two types of credentials. Create whichever credentials are appropriate for your project:
     - OAuth 2.0: Whenever your application requests private user data, it must send an OAuth 2.0 token along with the request. Your application first sends a client ID and, possibly, a client secret to obtain a token. You can generate OAuth 2.0 credentials for web applications, service accounts, or installed applications.
     - API keys: A request that does not provide an OAuth 2.0 token must send an API key. The key identifies your project and provides API access, quota, and reports
     [To keep your API keys secure](https://cloud.google.com/docs/authentication/api-keys)
     

