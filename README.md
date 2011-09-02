normalize.css
=============

Normalize.css is a customisable CSS file that makes browsers render all elements more consistently and in line with modern standards. We researched the differences between default browser styles in order to precisely target only the styles that need normalizing.

[Check out the demo](http://necolas.github.com/normalize.css/demo.html)

Why *.sass?
-----------

* All possible variables are defined on top of the file, making them easy to spot and edit
* Maintain only the .sass file and compile to css (expanded and minified)
* Syntax similar to css, with benefits from sass (variables, calculations, mixins, ...)

How to compile the ".sass" file
-----------

Install compass: http://compass-style.org/install/

Then:

sass -t compressed normalize.sass css/normalize_compressed.css

sass -t expanded normalize.sass css/normalize.css

What does it do?
-----------

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Explains what code does using detailed comments.

How to use it
-----------

It is suggested that you read through the `normalize.css` file and customise it to meet the design requirements of a project, rather blindly including it as a "black box".

If you prefer to use a different CSS formatting style, consider using a tool like [Procssor](http://procssor.com/).

If you would like to minify the file, you can use a tool like this [online CSS compressor using YUI Compressor](http://www.refresh-sf.com/yui/) or perform the minification as part of your build process.

Browser support
-----------

* Google Chrome
* Mozilla Firefox 3+
* Apple Safari 4+
* Opera 10+
* Internet Explorer 6+

License
-----------

Public domain

Acknowledgements
------------

Normalize.css is a project by [Nicolas Gallagher](http://github.com/necolas) and [Jonathan Neal](http://github.com/jonathantneal).
