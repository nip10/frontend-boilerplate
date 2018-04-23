# Frontend boilerplate

A frontend boilerplate for simple html/js/scss projects.

# Gulp tasks
## Build (default)
For build'ing the app.
## Serve
For development. Runs default taks + browser-sync (web server) w/ hot reloading, ONE time. Then, it watches all files, and re-runs the tasks related to those files.
## Production
For production. Runs linters before the default tasks. Adds different features in other tasks related to minification, uglifying, etc..

# Gulp sub-tasks
## Clean
Cleans dist dir.
## Scripts
Transpiles w/ babel, concats all files, creates sourcemaps. In prod, also uglifies.
## Styles
Converts sass to css, adds prefixes, creates sourcemaps. In prod, also cleans unused code.
## Images
Minifies images.
## Fonts
Just copy fonts files.
## HTML
Just copy html files.
## Lint-sass
Lints scss files using sass-lint
## Lint-js
Lints js files using eslint

# Linter config

I'm also including my own linters/transpiler options/configs since they are pretty much the same on this kind of projects. Everything required to run this repo is on the package.json file, so it doesn't depend on global packages.
