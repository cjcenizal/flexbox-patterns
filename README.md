# Flexbox Patterns

This repository contains the original SCSS used for the
components at [www.flexboxpatterns.com](http://www.flexboxpatterns.com).
Feel free to use these styles however you like!

## Getting started

Assuming you have Node installed, you can install the project dependencies with
`npm install`. This will install PostCSS and Autoprefixer; two critical tools
for making your CSS cross-browser compatible.

This project also requires you have [SASS](http://sass-lang.com/) installed
(`sudo gem install sass`).

## Commands

`npm run build`

I've chosen to write the styles with SCSS since it's widely adopted and I've
found that it makes me more productive. This command will compile the SCSS into
CSS and add various vendor-prefixed properties. Open up `dist/index.html`
to see a demo page of the various flexbox patterns in the browser.
