# Prerequisites
* Xlib headers
* ttf-font-awesome - Provides pretty icons for each module
* mpc - Prints song artist & title if mpd is installed and configured
* pulsemixer - Display volume levels
* freetype2 - Display font-awesome glyphs correctly

# Installation
`cd` into the slstatus folder, and then run `sudo make clean install`. If using xinit, add `slstatus &` before `exec <wm>` to launch slstatus when X starts.
