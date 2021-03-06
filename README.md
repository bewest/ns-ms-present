
## presentation

A presentation quickly hacked together.
Downloaded bunch of photos, got them to lexically sort by filename,
and generate a new slide for each one.

http://bewest.github.io/ns-ms-present/?theme=solarized#/nightscout-intro

* [WEB](http://bewest.github.io/ns-ms-present/?theme=solarized#/nightscout-intro)
* [PDF](http://bewest.github.io/ns-ms-present/presentation.pdf)

### colophon

Useful links:

* http://johnmacfarlane.net/pandoc/demo/example9/producing-slide-shows-with-pandoc.html
* https://gist.github.com/lmullen/c3d4c7883f081ed8692a 
* https://github.com/jgm/pandoc/issues/1051

Basically, `pandoc` renders a markdown file into a reveal.js
presentation.  While there are all kinds of features for influencing
slides, I ran out of time and had to suffice with a simple list.
Maybe slides that just go from left to right are just fine.

Patches to make this better are welcome.  There is supposed to be a way to
concatenate multiple files, as well as co-ordinate horizontal as well as
vertical slides.

The html file that pandoc creates must be siblings with the `images` directory
and with a checkout of `reveal.js`.  It's possible to use pandoc to create
other renderings of this as well.

