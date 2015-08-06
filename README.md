# Gulp-donderstarter
Base for static front-end development using gulp, sass and bower

## Features
- Gulp;
- Bower to manage dependencies;
- CSS pre-compile through SASS;
- JShint;
- SASS and JS minification and concatenation;

## Requirements
- [nodejs](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Install
Install the dependencies with `npm install` or `sudo npm install`. Then just run `gulp`.

## Gulp tasks
- ** gulp ** will build the files inside the /dist folder and perform a watch. You are ready to start developing
- ** gulp clean ** will clean the dist folder
- ** gulp release ** will do the same build but with a js uglify in the end