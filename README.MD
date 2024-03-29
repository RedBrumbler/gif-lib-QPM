= GIFLIB =

This is the README file of GIFLIB, a library for manipulating GIF files.

This version of GIFLIB was compiled for use with oculus quest mods, distribution through qpm

Latest versions of GIFLIB are currently hosted at:
    http://sourceforge.net/projects/giflib

== Overview ==

GIF is a legacy format; we recommend against generating new images in
it.  For a cleaner, more extensible design with better color support
and compression, look up PNG.

giflib provides code for reading GIF files and transforming them into 
RGB bitmaps, and for writing RGB bitmaps as GIF files.

The (permissive) open-source license is in the file COPYING.

You will find build instructions in build.adoc

You will find full documentation of the API in doc/ and on the 
project website.

Please report bugs to the bug tracker on sourceforge:

http://sourceforge.net/tracker/?group_id=102202

The project has a long and confusing history, described in history.adoc

The project to-do list is in TODO.

== Authors ==

Gershon Elber <gershon[AT]cs.technion.sc.il>
	original giflib code

Toshio Kuratomi <toshio[AT]tiki-lounge.com>
        uncompressed gif writing code
        former maintainer

Eric Raymond <esr[AT]snark.thyrsus.com>
        current as well as long time former maintainer of giflib code

There have been many other contributors; see the attributions in the
version-control history to learn more.
