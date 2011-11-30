pianobar (now with notifications)
===========

**Works as of November, 29, 2011** (synced with master for API changes)

pianobar is a console client for the personalized web radio pandora
(http://www.pandora.com).

 - play and manage (create, add more music, delete, rename, ...) your stations
 - rate played songs and let pandora explain why they have been selected
 - show upcoming songs/song history
 - configure keybindings
 - last.fm scrobbling support (external application)
 - proxy support for listeners outside the USA
 - notifications displayed on song change

The sourcecode can be downloaded at http://github.com/tkahn6/pianobar/

Dependencies
---------------

Depends on libnotify, gtk-2.0, glib2, libao, libfaad, and libmad. On ubuntu you can get this with:

     sudo aptitude install libnotify-dev libglib2.0-dev libgtk2.0-dev libao-dev libfaad-dev libmad0-dev
