INCEPTION Boilerplate : a project boilerplate for SCSS, Jasmine, Coffeescript, and html 5
=============
Bits and pieces put together from various projects to get started writing an application that uses:
* [SCSS](http://sass-lang.com) via [Compass](http://compass-style.org) to quickly and efficiently build CSS
* [Coffeescript](http://jashkenas.github.com/coffee-script/) to quickly and efficiently write Javascript
* [Jasmine](http://pivotal.github.com/jasmine/) hookups with Coffeescript with the help of the [InstantJasmineCoffee project](https://github.com/krismolendyke/InstantJasmineCoffee) (I would have linked it in here rather than copying the files, but I had to change the paths around a bit.)
* The [Html5 Boilerplate](http://html5boilerplate.com/) boilerplate, modified with links to the output of the previous projects plus [Yepnope](http://yepnopejs.com/) and [Modernizr](http://www.modernizr.com)

You'll want the SCSS and Compass ruby gems installed; their sites explain how.

You'll also want node.js and Cofeescript installed; their sites also explain how.

Usage
-------
The src/ directory holds things that need to be compiled (SCSS, Coffeescript.)

To compile your SCSS, from the root directory, use 'compass compile.'

To compile your Coffeescript, run 'cake build:all'. There are a lot more options in the Cakefile, Kris Molendyke did a pretty awesome job.

License
-------
Licensed under the WTFPL. http://sam.zoy.org/wtfpl/COPYING
