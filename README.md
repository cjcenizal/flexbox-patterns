# Flexbox Patterns

This repository contains the original CSS used for the
components at [www.flexboxpatterns.com](http://www.flexboxpatterns.com).
Feel free to use these styles however you like!

## Getting started

Assuming you have Node installed, you can install the project dependencies with
`npm install`. This will install PostCSS and Autoprefixer; two critical tools
for making your CSS cross-browser compatible.

## Commands

`npm run build`

This command will concatenate the source CSS files into a single CSS file, and
then use PostCSS to add various vendor-prefixed properties. Open up
`dist/index.html` to see a demo page of the various flexbox patterns in the
browser.

## Things to keep in mind

_I don't recommend copy-pasting these examples directly into production code._
I'm only trying to demonstrate different ways of using flexbox through these
examples, so they may not incorporate some accessibility best practices (such as using semantic HTML5 elements and the `role` attribute). Before using this
code in production you should make sure it meets your accessibility needs.
