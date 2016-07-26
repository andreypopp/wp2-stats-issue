# Reproduction code for webpack issue

webpack/webpack#2803

* Clone repo
* `npm install`
* `./node_modules/.bin/webpack --watch`
* Edit `dep.js` (keeping incorrect export/import), see on each rebuild warnings
  are duplicated.
