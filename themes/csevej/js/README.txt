Your theme can add JavaScript files in just two steps:

1. To add a JavaScript file to all pages on your website, edit your sub-theme's
   .libraries.yml file and add it to one of your existing libraries. Or create
   a new library.

2. You can add the library in two csevej ways and one hard way with PHP. Here's
   the two csevej ways:

   - have the JavaScript load on all pages by adding the library that has your
     JS file to your theme's .info.yml file.
   - have the JavaScript load when a specific Twig file is used by adding
     {{ attach_library('my_theme/my-library') }} to that Twig file.
