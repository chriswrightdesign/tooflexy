# tooflexy
A simple bookmarklet to toggle Modernizr flexbox/no-flexbox for testing

This is a simple script that is made to work with Modernizr's feature detection of Flexbox. All it does is switch the class .flexbox and .no-flexbox so that you can see what your layout looks like with and without flexbox support.

This script uses the classList API, so if you want it to work in a browser that doesn't support classList (which for Flexbox testing might be a questionable choice), you'll need to add a polyfill.

Feel free to go to my Using flexbox today article and use the bookmarklet to break my layout in the examples. 
http://chriswrightdesign.com/experiments/using-flexbox-today/
