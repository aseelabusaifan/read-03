# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

 * a lot of storage space
on the client
* that persists beyond a page refresh
and isn’t transmitted to the server

a collection of objects that represent the HTML elements on the page. Every element — every <p>, every <div>, every <span> — is represented in the DOM by a different object. (There are also global objects, like window and document, that aren’t tied to specific elements.)

here is no modernizr_init() function to call. When it runs, it creates a global object called Modernizr, that contains a set of Boolean properties for each feature it can detect. For example, if your browser supports the canvas API, the Modernizr.canvas property will be true. If your browser does not support the canvas API, the Modernizr.canvas property will be false.