## Inlining
Have a look: [Concatenating Web Components with Vulcanize](https://www.polymer-project.org/0.5/articles/concatenating-web-components.html)

 - Install vulcanize: `npm install -g vulcanize`
 - cd into /101/
 - run: `vulcanize index.html > build.html`

build.html file will have the web components inlined. It's even possible to inline scripts and stylesheets with `--inline-scripts` and `--inline-css` switches.

## Resources

### Web Components

 - Web Components 101: https://www.youtube.com/watch?v=hEzmy93zr0Y 
 - HTML Imports: https://www.polymer-project.org/0.5/platform/html-imports.html 
 - HTML Imports: #include for the web: http://www.html5rocks.com/en/tutorials/webcomponents/imports/ 
 - Styling: Include stylesheets https://www.polymer-project.org/0.5/docs/polymer/styling.html#including-stylesheets-in-an-element (not 1.0 doc)
 - styling: https://www.polymer-project.org/1.0/docs/devguide/styling.html 
 - Shadow DOM: http://webcomponents.org/polyfills/shadow-dom/ 
 - Shadow DOM 101: http://www.html5rocks.com/en/tutorials/webcomponents/shadowdom/ 
 - Shadow DOM 201: http://www.html5rocks.com/en/tutorials/webcomponents/shadowdom-201/ 

### Polymer

 - Data binding helper elements: https://www.polymer-project.org/1.0/docs/devguide/templates.html (stuff like if binding, etc.)
 - Passing Arrays: https://www.polymer-project.org/0.5/docs/start/usingelements.html#objectarray
 - [Concatenating Web Components with Vulcanize](https://www.polymer-project.org/0.5/articles/concatenating-web-components.html)

### Bower Distribution
 - Register a bower package: http://bower.io/docs/creating-packages/ 
 - Distributing Components with Bower: https://www.polymer-project.org/0.5/articles/distributing-components-with-bower.html

### Dependency Injection for JavaScript
 - [Use requirejs and jquery, without clobbering global jquery?](http://stackoverflow.com/questions/4858431/use-requirejs-and-jquery-without-clobbering-global-jquery)
