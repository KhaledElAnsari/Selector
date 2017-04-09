# Selector
A modern micro JS library that replaces the most common functionality of jQuery. 

This jQuery replacement is meant to be used on projects that require jQuery-like functionality without the jQuery bloat.

### file size comparison between jQuery and selector.js

#### jquery (uncompressed)
jquery-3.2.0.js (**271 KB**)

jquery-3.2.0.min.js (**84.5 KB**)

jquery-3.2.0.slim.js (**217 KB**)

jquery-3.2.0.slim.min.js (**67.9 KB**)


#### jquery (gzip compressed)
jquery-3.2.0.js (**74.7 KB**)

jquery-3.2.0.min.js (**28.6 KB**)

jquery-3.2.0.slim.js (**60 KB**)

jquery-3.2.0.slim.min.js (**22.7 KB**)


#### selector.js (uncompressed)
selector.js (**65.1 KB**)

selector.min.js (**17.5 KB**)


#### selector.js (gzip compressed)
selector.js (**11.3 KB**)

selector.min.js (**4.75 KB**)


### Supported jQuery selector functions
* add
* addClass
* after
* animate (requires Velocity.js)
* append
* attr
* before
* children
* closest
* css
* each
* empty
* eq
* filter
* find
* first
* get
* has
* hasClass
* height
* hide
* html
* index
* innerHeight
* innerWidth
* is
* last
* map
* next
* not
* off
* offset
* offsetParent
* on
* one
* outerHeight
* outerWidth
* parent
* parents
* position
* prepend
* prev
* prop
* ready
* remove
* removeAttr
* removeClass
* removeProp
* serialize
* show
* siblings
* slice
* stop (requires Velocity.js)
* toggle
* toggleClass
* val
* width

### Supported jQuery objects
* $

### Supported jQuery functions
* $.ajax
* $.extend

### Unsupported jQuery functionality
* jQuery object
* all jQuery plugins


## Disclaimer
This project is in beta and has been tested in Chrome 51+, IE8+ (using ie-shim.js), Safari 9+, and iOS 6+. Use at your own risk. 
