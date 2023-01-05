## Assignment chapter 01 

#### Q1. What is emmet?
  Emmet  is plugin for IDE like Vscode which is used to short expression can be used to generate HTML css markup.

#### Q2. Difference between library and framework ? 
>Library 
 is a collection of pre-defined helper functions, objects, classes, modules that can be used in code to boost the development. By using a library, you can control the flow of the application and call the library. Eg: React, JQuery, Lodash

>Framework 
Foundation upon which applications are built. In contrast, when you use a framework, the control is inverted, i.e., the framework controls the flow and calls your code. Eg: Node JS, Angular, Spring.

#### Q3.What is CDN ? Why do we use it ?
A CDN also called a content distribution network, is a group of geographically distributed and interconnected servers. They provide cached internet content from a network location closest to a user to speed up its delivery.

#### Q4. Why is React known as React?
React was developed for applications (Facebook) that have constantly changing data. Since React is a front-end framework or the “View” in MVC, this means that as the user clicks around and changes the app’s data, the view should “react” or change with those user events. User events being mouse clicks, typing, submitting a form.

#### Q5. What is cross-origin in script tag ?
The 'crossorigin' attribute sets the mode of the request to an HTTP CORS Request. A cross-origin request is a request for a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain. CORS i.e. Cross-Origin Resource Sharing is used to manage cross-origin requests.

#### 6. What is difference between React and ReactDOM?
React library contains functionality utilised in web and mobile apps (react native). ReactDOM library contains functionality utilised in web browser. It contains DOM manipulation utilities. 

#### Q7.What is the difference between react.production.js and react.development.js ?
- react.production.js - production code of react library that is minified and production ready.
- react.development.js - More readable and developer friendly react library code that can be used to debug.

#### Q8. What is async and defer - check Akshay Saini's Youtube channel?
Without async/defer : Browser stops the html parsing once script tag is encountered. It resumes parsing only after script is fetched and executed.

Async : Html parsing is done in parallel while scripts are being fetched from the network and executed. Once the script is done with execution, html parsing is resumed. This can be used for external scripts like google analytics. It is better to avoid async for scripts that are dependent on other scripts since we dont know in which order script will be executed.

Defer : Similar to async, Html parsing is done in parallel while scripts are being fetched from the network. But scripts are executed only after the html parsing is done
