# Dook's build of st

------------------------------

st version 0.9

## Features:

* scroll with alt+shift+j/k
* if upon resizing text doesn't fit in the window, it wraps instead of getting
  cut off
* spawn a new st window as an orphan process with win+shift+enter
* use a farbfeld format image for fake transparency
* to reload the image: pidof st | xargs kill -s USR1
* secondary fonts if your primary font doesn't support emoji or whatnot
* proper box-character rendering
* Luke Smith's externalpipe feature
	-> copy output of a command with alt+y
	-> copy URLs with alt+o
	-> follow URLs with alt+w
* delete key works like delete is supposed to

To enable the externalpipe feature, make sure the scripts from extpipe are in
your PATH
