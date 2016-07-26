# quick-gulp-setup

A personally built task runner meant for rapid development geared towards front-end static pages with minimal setup. It currently watches, bundles and auto-reloads the browser when changes are made to SCSS, JS files, and a main html file. The compiled files will be stored in the /dist folder.

Modules used in this setup include:

- gulp
- browser-sync
- browserify
- gulp-sass
- gulp-uglify
- vinyl-buffer
- vinyl-source-stream

Will add an image optimizer soon!

#### Grab code and resolving dependencies

    $ git clone https://github.com/binhxn/quick-gulp-setup.git
    $ cd quick-gulp-setup
    $ npm install

#### Build/Run local envionment

    $ gulp serve
    or
    $ npm start

## SCSS

To compile all SCSS files, you must import them to one main SCSS file (i.e. style.scss). Example included in /scss folder.

## JS
All JS files affecting front-end development should live in the /client folder. In addition, files can be 'required'. Example included in /client folder.
Note*: When building your local environment, only CSS is compiled on command. You MUST save a JS file in the /client folder in order for you to compile the bundle.js file in the dist folder. Will fix in future iterations.