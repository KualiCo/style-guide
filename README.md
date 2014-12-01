Kuali.co Style Guide
====================

This repository lets us create css styles (and possibly components) that give our components nice defaults. 

View Examples
-------------

[Click here to view the examples](http://kualico.github.io/style-guide/)

Getting Started
---------------

Install as an NPM dependency

    npm install --save git+ssh://git@github.com:KualiCo/style-guide.git

Copy the files into your project using a postinstall script. Add to your package.json:

    "scripts": {
      "postinstall": "mkdir -p public/css/npm; cp node_modules/style-guide/css/*.css public/css/npm/"
    },

Then you can `.gitignore` the `public/css/npm` folder, and import the style

    <link rel="stylesheet" href="css/npm/styleguide.css">

Alternatively, you can symlink in the file instead.

What belongs here
-----------------

This should work like Foundation. It has classes to give our components a nice out-of-the-box look. Examples:

- the company logo
- consistent dropdowns
- consistent header bar
- typeahead search box styles (but not the component)

What doesn't belong here
------------------------

Complicated component behavior should probably be published as open source. Think about what parts to publish so another company could use the component and publish those. Examples:

- typeahead search box (but not the styles)






