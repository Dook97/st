 __| |_   ___   __(_)_ __  _ __| |___  | |_ ___ _ _ _ __ (_)_ _  __ _| |
(_-<  _| |___| (_-< | '  \| '_ \ / -_) |  _/ -_) '_| '  \| | ' \/ _` | |
/__/\__|       /__/_|_|_|_| .__/_\___|  \__\___|_| |_|_|_|_|_||_\__,_|_|
                          |_|

=== st v0.9 ======================================

st is a simple terminal developed by suckless

This is my modification based off of st v0.9

Added features:

* scroll with alt+shift+j/k
* if upon resizing text doesn't fit in the window, it wraps instead of getting
  cut off
* spawn a new st window as an orphan process with win+shift+enter
* use a farbfeld format image for fake transparency
	-> to reload the image: pidof st | xargs kill -s USR1
* secondary fonts if your primary font doesn't support emoji or whatnot
* proper box-character rendering
* Luke Smith's externalpipe feature
	-> copy output of a command with alt+o
	-> copy URLs with alt+y
	-> follow URLs with alt+w
* delete key works like delete is supposed to

To enable the externalpipe feature, make sure the scripts from extpipe as well
as dmenu are in your PATH

==================================================

patched by dook97
