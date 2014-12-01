Kuali.co Style Guide
====================

This repository lets us create css styles (and possibly components) that give our components nice defaults. 

View Examples
-------------

[Click here to view the examples](http://kualico.github.io/style-guide/)


Getting Started
---------------

There are multiple ways to import this into your project, but this is what I recommend:

Install as an NPM dependency

    npm install --save git+ssh://git@github.com:KualiCo/style-guide.git

Create a symlink into your public folder. If your public folder is under ./public

    cd public
    ln -s ../node_modules/style-guide

Then you can import the style, images, or anything else

    <link rel="stylesheet" href="style-guide/css/styleguide.css">
    
    <img src="style-guide/img/logo.png">

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






