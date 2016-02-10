Browserify boilerplate
========================================
Initial setup for projects using gulp and browserify.


How to use
-----------

- Download the boilerplate as a [zip file](https://github.com/JoanClaret/browserify-boilerplate/archive/master.zip)
- Run npm install from the project folder
- Run 'gulp'. You'll see a new `./dist/build.js` generated file.
- Add a new npm package `npm i max-char-limit-warning --save`
- Require the npm package in main.js file, simply adding `require('max-char-limit-warning');` at the end of the file.
- Run 'gulp' again. You'll see `max-char-limit-warning` included in `./dist/build.js` (after jQuery).

