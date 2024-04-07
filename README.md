# Namespace Bootstrap
 
When integrating Bootstrap on a website with pre-existing styles, namespace it to prevent any conflicts.

## Install latest version

``$npm install``

## Compile Bootstrap with a prefix

``$npx postcss node_modules/bootstrap/dist/css/bootstrap.css -o dist/css/bootstrap-prefixed.css``

### Custom prefix class

By default the CSS file will be generated with .bootstrap as a class that all your Bootstrap styles need to be nested in. To edit this class, simply edit the postcss.conf.js file.
