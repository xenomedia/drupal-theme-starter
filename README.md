
# Xeno Media - Demeter - Drupal 8 Theme Starter

This is a starter Drupal 8 theme that uses the Bootstrap 3 Frontend Framework.

## Setup

Make a copy of this theme and rename RENAME to your new theme name in these files:

- /bootstrap/Gruntfile.js
- /bootstrap/less/bootstrap.less
- /RENAME.info.yml
- /RENAME.libraries.yml

Rename the folder at:
- /bootstrap/less/~RENAME/

## Compile Bootstrap
- cd into /bootstrap and run `npm install`
- run `grunt dist` to compile
- You can also run `grunt watch` to autocompile

## Add LESS files
- Add new less files you nees in /bootstrap/less/~NEWTHEMENAME/
- Add them to be included in /bootstrap/less/bootstrap.less
