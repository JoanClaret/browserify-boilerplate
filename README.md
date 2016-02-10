Browserify boilerplate
========================================
Initial setup for projects using gulp and browserify.


How to use
-----------

- Download the boilerplate as a [zip file](https://github.com/JoanClaret/browserify-boilerplate/archive/master.zip)
- Run npm install from the project folder. It will install `gulp`, `browserify`, and `vinyl-source-stream`.
- Add a new npm package. Example: `npm i max-char-limit-warning --save`
- Require the npm package in main.js file, simply adding `require('max-char-limit-warning');` at the end of the file.
- Run 'gulp'. You'll see `max-char-limit-warning` included in `./dist/build.js` (after jQuery).

Adding jQuery
-----------
- Add jQuery as a new dependency: `npm i jquery --save`
- Require jQuery in the main.js file `var $ = jQuery = require('jquery');`
- Run 'gulp' again.
