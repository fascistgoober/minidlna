I lifted some guy's code and had to fix two or three things.
So, this is my fork of it.


----------

My personal fork with the following patches:
- Cygwin port
- No cover resize option
- Prepend title with disc and track numbers options
- Read mkv metadata
- Read SSA and ASS subtitles

==================

How to compile:

```
$ ./autogen.sh
$ ./configure
$ make -j
$ sudo make install
$ sudo /usr/local/sbin/minidlnad -R -f /etc/minidlna.conf
```

==================

MiniDLNA project
(c) 2009 Justin Maggard
Portions (c) 2006-2007 Thomas Bernard
webpage: http://sourceforge.net/projects/minidlna/

This directory contains the MiniDLNA daemon software.
This software is subject to the conditions detailed in
the LICENCE file provided with this distribution.

Parts of the software including the discovery code are
licensed under the BSD revised license which is detailed
in the LICENSE.miniupnpd file provided with the distribution.
More information on MiniUPnPd can be found at http://miniupnp.free.fr.


The MiniDLNA daemon is an UPnP-A/V and DLNA service which
serves multimedia content to compatible clients on the network.
See http://www.upnp.org/ for more details on UPnP
and http://www.dlna.org/ for mode details on DLNA.

See the INSTALL file for instructions on compiling, installing,
and configuring minidlna.

Prerequisites
==================

- libexif
- libjpeg
- libid3tag
- libFLAC
- libvorbis
- libsqlite3
- libavformat (the ffmpeg libraries)


Justin Maggard
