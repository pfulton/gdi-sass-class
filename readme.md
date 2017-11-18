Intro to Sass
================================
## Author Information
This is the [Girl Develop It Intro to Sass](https://github.com/gdi-curriculum-review/gdi-sass-intro) course. Materials by [Catherine Farman](https://github.com/cfarm), based on [Intermediate HTML/CSS materials](https://github.com/girldevelopit/gdi-core-intermediate-html-css) by Girl Develop It.

## Modified September 2017
Modified by [Philip Zastrow](http://twitter.com/zastrow) for [GDI Dayton](http://gdidayton.com)
---------------------

## Modified November 2017
Modified by [Patrick Fulton](http://twitter.com/patrickfulton) for [GDI Pittsburgh](https://www.girldevelopit.com/chapters/pittsburgh)

## Building the slide deck:

The slide deck is available as is and ready to run in the `docs` directory. A Node-base build process has been built around the slide deck to allow the deck to be broken down into manageable chunks, as well as Sass for CSS generation.

- To install Node modules run `npm install`
- To generate and serve the slide deck run `npm start`

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});
```
