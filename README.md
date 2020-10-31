# Andrej's dmenu
Just a simple patched version of dmenu. The first patch is a simple <border> patch with ability to set the border width from shell script and the second patch is the <xyz> patch, which adds commands to set the coordinates.
# Installation
clone the repository and run:
<sudo make install>
# How I use it
My personal prefference is to have dmenu opened as a list, positioned in the center, but slightly to the right:

|‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾|
|                                |
|                                |
| |‾‾‾‾‾‾‾‾‾‾‾|                  |
| |dmenu      |                  |
| |___________|                  |
|                                |
|                                |
|________________________________|

So the command I put in my dwm config file, to be bound to a key is:
<dmenu_run -l 10 -bw 8 -x 500 -y 800 -w 1400 -nf "#bbbbbb" -sb "#18815f" -sf "#eeeeee">
