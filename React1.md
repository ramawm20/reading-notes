# ES6 and React Overview

## ES6

+ ES6 stands for ECMAScript 6. ECMAScript was created to standardize JavaScript, and ES6 is the 6th version of ECMAScript. It was published in 2015 and is also known as ECMAScript 2015.

+ Some of the changes that come with ES6:

     - Adding Let and Const for variable declaration.
     - Arrow functions.
     - Template literals:

        ```
        let str = `Release Date: ${date}`
        ```
    - Method definition shorthand =>          
      ES5
      
           
          var obj = {
          a: function (c, d) {},
          b: function (e, f) {},  }
      ES6
         ```
         let obj = {
         a(c, d) {},
         b(e, f) {},
          }

        obj.a() // call method a
          ```

   -  Classes/constructor functions
   - Inheritance.
----------------------------------------------------------------------------------------------------------------------------------------------------


## React 
  + Hello World =>
    -  This code  displays a heading saying “Hello, world!” on the page.
             
          const root = ReactDOM.createRoot(document.getElementById('root')); root.render(<h1>Hello, world!</h1>);
+  React-JSX =>
   - (Java Script XML) it allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods.
        It is called JSX, and it is a syntax extension to JavaScript. It recommended to used with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.
     
           const element = <h1>Hello, world!</h1>; 
           
+ Rendering Elements =>
  - To render a React element, first pass the DOM element to ReactDOM.createRoot(), then pass the React element to root.render():

        const root = ReactDOM.createRoot(
        document.getElementById('root')
        );
        const element = <h1>Hello, world</h1>;
        root.render(element);

+ Components and Props =>
  - Components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
