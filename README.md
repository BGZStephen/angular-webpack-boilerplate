# Angular-Webpack boilerplate

A boilerplate for Angular RC 6 + Webpack 4.x projects.

Features:

* TS Transpiling
* JS Bundling
* CSS extraction
* HTML file extraction
* Font file extraction
* Image extraction
* Quiet progress bar webpack compilation

Commands:

`yarn dev` run a webpack-dev-server hosted version of the app, served on port 4200
`yarn build` build a development version of the app, output to the dist folder with a NODE_ENV of development
`yarn build:prod` build a production version of the app, output to the dist folder with a NODE_ENV of production. Enables minification + uglification
