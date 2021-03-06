#Front-end Job Interview Questions

This file contains a number of front-end interview questions that can be used when vetting potential candidates. It is by no means recommended to use every single question here on the same candidate (that would take hours). Choosing a few items from this list should help you vet the intended skills you require.

**Note:** Keep in mind that many of these questions are open-ended and could lead to interesting discussions that tell you more about the person's capabilities than a straight answer would.

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Testing Questions](#testing-questions)
  1. [Performance Questions](#performance-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)

## Getting Involved

  1. [Contributors](#contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)

#### General Questions:

* What did you learn yesterday/this week?
* What excites or interests you about coding?
* What is a recent technical challenge you experienced and how did you solve it?
* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
* Talk about your preferred development environment.
* Which version control systems are you familiar with?
* Can you describe your workflow when you create a web page?
* If you have 5 different stylesheets, how would you best integrate them into the site?
* Can you describe the difference between progressive enhancement and graceful degradation?
* How would you optimize a website's assets/resources?
* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
* Name 3 ways to decrease page load (perceived or actual load time).
* If you jumped on a project and they used tabs and you used spaces, what would you do?
* Describe how you would create a simple slideshow page.
* If you could master one technology this year, what would it be?
* Explain the importance of standards and standards bodies.
* What is Flash of Unstyled Content? How do you avoid FOUC?
* Explain what ARIA and screenreaders are, and how to make a website accessible.
* Explain some of the pros and cons for CSS animations versus JavaScript animations.
* What does CORS stand for and what issue does it address?

#### HTML Questions:

* What does a `doctype` do?
* What's the difference between full standards mode, almost standards mode and quirks mode?
* What's the difference between HTML and XHTML?
* Are there any problems with serving pages as `application/xhtml+xml`?
* How do you serve a page with content in multiple languages?
* What kind of things must you be wary of when design or developing for multilingual sites?
* What are `data-` attributes good for?
* Consider HTML5 as an open web platform. What are the building blocks of HTML5?
* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.
* Describe the difference between `<script>`, `<script async>` and `<script defer>`.
* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?
* What is progressive rendering?
* Have you used different HTML templating languages before?

#### CSS Questions:

* What is the difference between classes and IDs in CSS?
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?
* Describe Floats and how they work.
* Describe z-index and how stacking context is formed.
* Describe BFC(Block Formatting Context) and how it works.
* What are the various clearing techniques and which is appropriate for what context?
* Explain CSS sprites, and how you would implement them on a page or site.
* What are your favourite image replacement techniques and which do you use when?
* How would you approach fixing browser-specific styling issues?
* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
* What are the different ways to visually hide content (and make it available only for screen readers)?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* Are you familiar with styling SVG?
* How do you optimize your webpages for print?
* What are some of the "gotchas" for writing efficient CSS?
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
* How would you implement a web design comp that uses non-standard fonts?
* Explain how a browser determines what elements match a CSS selector.
* Describe pseudo-elements and discuss what they are used for.
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* List as many values for the display property that you can remember.
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them?
* Have you played around with the new CSS Flexbox or Grid specs?
* How is responsive design different from adaptive design?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why?
* ans: https://neal.codes/blog/front-end-interview-css-questions/
#### JS Questions:

* Explain event delegation  
  Event delegation allows us to attach a single event listener, to a parent element, that will fire for all descendants matching a selector, whether those descendants exist now or are added in the future.

* Explain how `this` works in JavaScript  
  The ECMAScript Standard defines this as a keyword that "evaluates to the value of the ThisBinding of the current execution context" (§11.1.1). ThisBinding is something that the JavaScript interpreter maintains as it evaluates JavaScript code, like a special CPU register which holds a reference to an object.

* Explain how prototypal inheritance works  
  A prototype is an internal object from which other objects inherit properties. Its main purpose is to allow multiple instances of an object to share a common property. Thus, object properties which are defined using the prototype object are inherited by all instances which reference it.

* What do you think of AMD vs CommonJS?
* Explain why the following doesn't work as an IIFE: `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?
  (function () { … })();  
  !function () { … }();  
  ~function () { … }();  
  -function () { … }();  
  +function () { … }();  

* What's the difference between a variable that is: `null`, `undefined` or undeclared?
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one?  
  https://medium.com/@rlynjb/js-interview-question-what-is-a-closure-and-how-why-would-you-use-one-b6fd45ea95f6#.b1n1lwbf1

* What's a typical use case for anonymous functions?  
  http://helephant.com/2008/08/23/javascript-anonymous-functions/

* How do you organize your code? (module pattern, classical inheritance?)
* What's the difference between host objects and native objects?  
  http://stackoverflow.com/questions/7614317/what-is-the-difference-between-native-objects-and-host-objects

* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
  function declaration, function expression; instance of class `Person`

* What's the difference between `.call` and `.apply`?
  http://stackoverflow.com/questions/1986896/what-is-the-difference-between-call-and-apply  
  The difference is that apply lets you invoke the function with arguments as an array; call requires the parameters be listed explicitly. A useful mnemonic is "A for array and C for comma."  
  theFunction.apply(valueForThis, arrayOfArgs)  
  theFunction.call(valueForThis, arg1, arg2, ...)  

* Explain `Function.prototype.bind`.
  bind allows you to set which object is treated as this within the function call.

* When would you use `document.write()`?
  document.write() shouldn’t be used after the page has loaded to change the content as it will overwrite the entire page; when to use: when working with 3rd party libs, such as executing a script code segment will block page loading / executing, with doc.write can work in acync way

* What's the difference between feature detection, feature inference, and using the UA string?
  When you check if a certain feature exists, that’s feature detection. When you make an assumption that because one feature is present (or not) another one will also be present (or not): feature inference.

* Explain Ajax in as much detail as possible.
  AJAX is an acronym standing for `Asynchronous JavaScript and XML` and this technology help us to load data from the server without a browser page refresh.  
  AJAX stands for Asynchronous JavaScript and XML. In a nutshell, it is the use of the XMLHttpRequest object to communicate with server-side scripts. It can send as well as receive information in a variety of formats, including JSON, XML, HTML, and even text files. AJAX’s most appealing characteristic, however, is its "asynchronous" nature, which means it can do all of this without having to refresh the page. This lets you update portions of a page based upon user events.  
  * Step 1 – How to make an HTTP request  
    1. an instance of class that provide this functionality. IE:XMLHTTP; Mozilla, Safari and other browsers:   XMLHttpRequest. 
    2. decide what you want to do after you receive the server response to your request. define: httpRequest.onreadystatechange = nameOfTheFunction;
    3. make the request. call `open()` and `send()`. httpRequest.open('GET', 'http://www.example.org/some.file', true);
      httpRequest.send(null);
  * Step 2 – Handling the server response
    1. check state of the request. XMLHttpRequest.DONE. 0 (uninitialized); 1 (loading); 2 (loaded); 3 (interactive); 4 (complete)
    2. check the response code of the HTTP server response. `200 OK`
    3. two options to deal with response data:
      * httpRequest.responseText – returns the server response as a string of text
      * httpRequest.responseXML – returns the response as an XMLDocument object you can traverse using the JavaScript DOM functions

* What are the advantages and disadvantages of using Ajax?  
  http://stackoverflow.com/questions/2583223/what-are-the-advantages-and-disadvantages-of-making-ajax-calls-using-jquery

* Explain how JSONP works (and how it's not really Ajax).
  overcomes the Same-origin Policy; https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy  
  http://stackoverflow.com/questions/5943630/basic-example-of-using-ajax-with-jsonp
  JSONP create a `script` tag with src and send to server the url with `call_back` parameter, such that the server will return `call_back` with responsed data (as params), meaning the `call_back` will executed automatically.

* Have you ever used JavaScript templating? 
  * If so, what libraries have you used?
    As soon as we find ourselves including HTML inside JavaScript strings we should be starting to think about what benefits JavaScript templates could give us.  
    https://www.sitepoint.com/overview-javascript-templating-engines/
* Explain "hoisting".
  Hoisting is when a JS declaration is lifted (“hoisted”) to the top of it’s scope by the JS interpreter. What this really means is that a variable or function isn’t necessarily declared where you think it is.http://lucybain.com/blog/2014/hoisting/    
  1. Hoisting variables 

  ```javascript
  function containsHoisting() {
      console.log(hoistedVariable);
      var hoistedVariable = "I was hoisted!";
  }
  containsHoisting(); // logs undefined
  // What the interpreter changed it to:
  function containsHoisting() {
      var hoistedVariable; // <-- this line here!
      console.log(hoistedVariable);
      hoistedVariable = "I was hoisted!";
  }
  ```
  ```javascript
  var hoistedVariable = 1;
  function scopingFunction() {
      if (!hoistedVariable) {
          var hoistedVariable = 10;
      }
      return hoistedVariable;
  }
  scopingFunction(); // returns 10
  // reason: In Javascript scopes are defined at function level. Many other languages define scope at a block level (as in an if block or for loop). This is an important difference to remember.
  var hoistedVariable = 1;
  function scopingFunction() {
      var hoistedVariable; // <-- this line here!
      if (!hoistedVariable) {
          hoistedVariable = 10;
      }
      return hoistedVariable;
  }
  scopingFunction(); // returns 10
  ```  
  2. Hoisting functions  

  ```javascript
  function containingFunction() {
    var hoistedVariable = 2 + 2;
    function hoistedFunction() {
        return hoistedVariable;
    }
    return hoistedFunction();
  }
  containingFunction() // returns 4
  // js interpretor
  function containingFunction() {
    // this is the hoisted section
    var hoistedVariable;
    function hoistedFunction() {
        return hoistedVariable;
    }

    // here's the rest of the code
    hoistedVariable = 2 + 2;
    return hoistedFunction();
  }
  containingFunction() // returns 4
  ```
  ```javascript
  function containingFunction() {
    var hoisted = "I'm the variable";
    function hoisted() {
        return "I'm the function";
    }
    return hoisted(); // results in a TypeError
  }
  containingFunction()
  // js interpretor re-writes
  function containingFunction() {
    // hoisted section
    var hoisted;
    function hoisted() {
        return "I'm the function";
    }
    // rest of the code
    hoisted = "I'm the variable";
    return hoisted();
  }
  containingFunction() // results in a TypeError
  ```
* Describe event bubbling.
  http://stackoverflow.com/questions/4616694/what-is-event-bubbling-and-capturing  
  Event bubbling and capturing are two ways of event propagation in the HTML DOM API, when an event occurs in an element inside another element, and both elements have registered a handle for that event. The event propagation mode determines in which order the elements receive the event.
  
* What's the difference between an "attribute" and a "property"? http://lucybain.com/blog/2014/attribute-vs-property/  
  JS DOM objects have properties. Attributes are in the HTML itself, rather than in the DOM. when handling `read-only` fields, prefer `attribute`, retrieving `attr` after updating will still get default value if they have.
* Why is extending built-in JavaScript objects not a good idea?
  http://lucybain.com/blog/2014/js-extending-built-in-objects/

* Difference between document load event and document DOMContentLoaded event?  
  The DOMContentLoaded event will fire as soon as the DOM hierarchy has been fully constructed, the load event will do it when all the images and sub-frames have finished loading.
* What is the difference between `==` and `===`?
* Explain the same-origin policy with regards to JavaScript.  
  The same-origin policy restricts how a document or script loaded from one origin can interact with a resource from another origin. It is a critical security mechanism for isolating potentially malicious documents.
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
function duplicate(arr) {
  return Array.isArray(arr) && arr.concat(arr);
}
```
* Why is it called a Ternary expression, what does the word "Ternary" indicate?  
condition ? expr1 : expr2 

* What is `"use strict";`? what are the advantages and disadvantages to using it?  
http://lucybain.com/blog/2014/js-use-strict/
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
```javascript
for(var i = 1; i <= 100; ++i) {
  console.log(!(i%15) ? 'fizzbuzz '+i : !(i%3) ? 'fizz '+i : !(i%5) ? 'buzz '+i : '');
}
```

* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?  
http://lucybain.com/blog/2014/js-dont-touch-global-scope/  
  1. It’s harder to read the code and reason about it when variables seem to appear out of thin air (but really from the global scope).
  2. Anyone can update a global variable from any point in the program at any time (and from any thread if there’s more than one going).
  3. General code smell - if you're too lazy to put the variable only where it needs to be then what other corners are you cutting?
  4. It’s probable that you'll encounter global variable name clashes. Since there’s only one namespace you're more likely to double up on a variable name.
* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
The load event fires at the end of the document loading process. At this point, all of the objects in the document are in the DOM, and all the images and sub-frames have finished loading.  

* Explain what a single page app is and how to make one SEO-friendly.  
Single-Page Applications (SPAs) are Web apps that load a single HTML page and dynamically update that page as the user interacts with the app. SPAs use AJAX and HTML5 to create fluid and responsive Web apps, without constant page reloads. However, this means much of the work happens on the client side, in JavaScript.

Here are a few of the other benefits of using a javascript framework to produce a single-page web application:  
  1. As previously mentioned, a front-end framework distributes the processing work across multiple client computers.
  2. A front-end framework is extensible. Provided that you build your API in a RESTful way (which most frameworks encourage you to do), you can easily swap out server-side technologies with little front end changes. You could easily prototype your application using a technology like Firebase or Parse, and then migrate to a hosted solution when cost becomes prohibitive.
  3. A front-end framework can easily be turned into a mobile application. Technologies like Phonegap and Cordova make it remarkably easy to transform HTML, CSS, and Javascript into a hybrid native application.
  
  how to make one SEO-friendly?  https://www.getambassador.com/blog/single-page-webapp-seo
  * Optimizing Single Page Apps for SEO: Pretty URLs
  * Optimizing Single Page Apps for SEO: Cache Rules Everything Around Me
  * Optimizing Single Page Apps for SEO: sitemap.xml & GMT

* What is the extent of your experience with Promises and/or their polyfills?
What is a promise?  
A promise is a proxy for a value not necessarily known at its creation time. With promises, rather than an asynchronous call accepting a callback, it instead returns a promise. The calling code can then wait until that promise is fulfilled before executing the next step. To do so, the promise has a method named then, which accepts a function that will be invoked when the promise has been fulfilled. 

```javascript
// without promise
function isUserTooYoung(id, callback) {
    openDatabase(function(db) {
      getCollection(db, 'users', function(col) {
        find(col, {'id': id},function(result) {
          result.filter(function(user) {
            callback(user.age < cutoffAge)
          })
        })
      })
    })
}
// with promise
function isUserTooYoung(id) {
    return openDatabase(db)
      .then(getCollection)
      .then(find.bind(null, {'id': id}))
      .then(function(user) {
          return user.age < cutoffAge;
    });
}
```
* What are the pros and cons of using Promises instead of callbacks?
promise: flexitibility; It all depends on what you need to do and how you need it done.  For code that relies on short local reactions to asynchronous events go with a callback.  For more complex interactions and data flows promises bring order to what could potentially be callback hell.
* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
  may be difficult to debug and there might be performance concerns when the code has to be compiled and translated into Javascript.
* What tools and techniques do you use debugging JavaScript code?
* What language constructions do you use for iterating over object properties and array items?
* Explain the difference between mutable and immutable objects.
  * What is an example of an immutable object in JavaScript? All types except objects define immutable values (primitive values)
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
* Explain the difference between synchronous and asynchronous functions.
* What is event loop?  
The event loop got its name because of how it's usually implemented, which usually resembles:
```javascript
while(queue.waitForMessage()){
  queue.processNextMessage();
}
```
queue.waitForMessage waits synchronously for a message to arrive if there is none currently.
  * What is the difference between call stack and task queue?
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop
* Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`  
`function declaratoin` vs `function expression` https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/

#### Testing Questions:

* What are some advantages/disadvantages to testing your code?
* What tools would you use to test your code's functionality?
* What is the difference between a unit test and a functional/integration test?
* What is the purpose of a code style linting tool?

#### Performance Questions:

* What tools would you use to find a performance bug in your code?
* What are some ways you may improve your website's scrolling performance?
* Explain the difference between layout, painting and compositing.

Layout:-

Browser will determine how much space each element takes up and where to place it.

Painting:-

This is the process of filling in pixels. It involves drawing out elements.

Compositing:-

Browser draws element to the screen in the correct order so the page renders correctly.
#### Network Questions:

* Traditionally, why has it been better to serve site assets from multiple domains?
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
* What are the differences between Long-Polling, Websockets and Server-Sent Events?
* Explain the following request and response headers:
  * Diff. between Expires, Date, Age and If-Modified-...
  * Do Not Track
  * Cache-Control
  * Transfer-Encoding
  * ETag
  * X-Frame-Options
* What are HTTP methods? List all HTTP methods that you know, and explain them.

#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

*Question: What is the value of `foo.x`?*
```javascript
var foo = {n: 1};
var bar = foo;
foo.x = foo = {n: 2};
/*
foo.x = foo = {n: 2};

Here foo refers to {n:1} object before assignment i.e. before the statement is executed.

The statement can be re-written as foo.x = (foo = {n:2});

In object terms the above statement can be re-written as {n:1}.x = ( {n:1} = {n:2} );

Since assignment happens from right to left only. So here we just have to keep a check that foo is referring to which object before execution starts.

On solving the R.H.S: foo = {n:2}; Now foo is referring to {n:2};

Coming back on the problem we are left with:

foo.x = foo;

Now foo.x on L.H.S is still {n:1}.x whereas foo on R.H.S is {n:2}.

So after this statement gets executed {n:1} will become { n:1, x:{n:2} } with bar still referring to it. Where as foo will now be referring to {n:2}.

So on execution foo.x gives undefined as there is only 1 value in foo which is {n:2}.

But if you will try executing bar.x it will give {n:2}. Or if you will just execute bar the result will be

Object {n: 1, x: Object}
*/
```

*Question: What does the following code print?*
```javascript
console.log('one');
setTimeout(function() {
  console.log('two');
}, 0);
console.log('three');
```

#### Fun Questions:

* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Who inspires you in the front-end community?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
* How do you like your coffee?


#### Contributors:

This document started in 2009 as a collaboration of [@paul_irish](https://twitter.com/paul_irish) [@bentruyman](https://twitter.com/bentruyman) [@cowboy](https://twitter.com/cowboy) [@ajpiano](https://twitter.com/ajpiano)  [@SlexAxton](https://twitter.com/slexaxton) [@boazsender](https://twitter.com/boazsender) [@miketaylr](https://twitter.com/miketaylr) [@vladikoff](https://twitter.com/vladikoff) [@gf3](https://twitter.com/gf3) [@jon_neal](https://twitter.com/jon_neal) [@sambreed](https://twitter.com/sambreed) and [@iansym](https://twitter.com/iansym).

It has since received contributions from over [100 developers](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors).
