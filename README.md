# Reproduction code for webpack issue

* Clone repo
* `npm install`
* `./node_modules/.bin/webpack --watch`
* Edit `dep.js` (keeping incorrect export/import), see on each rebuild warnings
  are duplicated.
