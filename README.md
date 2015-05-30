### Inlining
Have a look: [Concatenating Web Components with Vulcanize](https://www.polymer-project.org/0.5/articles/concatenating-web-components.html)

 - Install vulcanize: `npm install -g vulcanize`
 - cd into /101/
 - run: `vulcanize index.html > build.html`

build.html file will have the web components inlined. It's even possible to inline scripts and stylesheets with `--inline-scripts` and `--inline-css` switches.