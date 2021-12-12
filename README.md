# Webpack Setup with Bootstrap 5 & PurgeCSS

* This is also using esbuild-loader for faster compilations.

## Installing dependencies

* Install dependencies with `npm install`

## Running Dev Server

* Start server endpoint with `npm run watch`
* Now you can visit [`localhost:9000`](http://localhost:9000) from your browser.
* `npm run watch` will not output build files to css/js directories. The CSS/JS is automatically served by the webpack server. To build files read below.

## Building Files

* Build (output css/style.css & js/script.js with `npm run build`

## Customize Safelist in PurgeCSS

* To customize `safelist`, add list of classes under `new PurgecssPlugin(...)` function block in `webpack.config.js`
