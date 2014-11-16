slock - simple screen locker
============================
simple screen locker utility for X.


Requirements
------------
In order to build slock you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install


Running slock
-------------
Simply invoke the 'slock' command. To get out of it, enter your password.


Improvements in this fork
-------------------------

- You can press space or return to activate the password entering mode (show color), without adding this keystroke to the password buffer
- You can press ESC or RETURN to abort the password entering, even if nothing is entered yet
- You can set custom color using the `-c color` flag: You can use CSS-style hexcode `"#FF00FF"`, or a color name (`green`).
