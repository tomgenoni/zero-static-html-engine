Gulp Static Generator
=====================

Output a static site using Gulp tasks based on [Considering a Static Site Tool? Learn Gulp.](https://medium.com/objects-in-space/considering-a-static-site-tool-learn-gulp-2fd5f9821fc4)

## Features

- Templates, including subfolders, and partials
- Sass/Compass compilation
- Preview server
- Watch processes recompiles HTML, Sass, and any assets
- Everything is compiled into the `_site` directory

## Usage

Install gulp dependencies:

     npm install

In a terminal window run:

     gulp

And visit [http://localhost:1337/](http://localhost:1337/). This displays the flat-file content of the `_site` directory.

## Troubleshooting

- If you're unable to run npm install without errors try running the following as you may have a permissions issue. Taken from solution to [NPM throws error without sudo](http://stackoverflow.com/questions/16151018/npm-throws-error-without-sudo).

     ``sudo chown -R `whoami` ~/.npm``
