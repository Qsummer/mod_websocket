mod_websocket [![Build Status](https://secure.travis-ci.org/nori0428/mod_websocket.png)](http://travis-ci.org/nori0428/mod_websocket)
=============

What is this?
-------

mod_websocket.c provides a WebSocket extension for
lighttpd HTTP server ver 1.4.28 - 1.4.31( http://www.lighttpd.net/ )

How does mod_websocket work?
------

Please see these figures.

* http://picasaweb.google.com/lh/photo/fb97lbN-O1Q5VkfJXyqN2w?feat=directlink
* http://picasaweb.google.com/lh/photo/KnX-73pr7ApCabc9NqBqNQ?feat=directlink

How can I use this?
------

First, please do like this.

  $ git clone git://github.com/nori0428/mod_websocket.git

and follow the instructions in INSTALL.

for QUICK START, plz read Wiki.

https://github.com/nori0428/mod_websocket/wiki

Changes
------

* Support dual protocols: hybi-00(for iOS) and RFC-6455(Chrome, Firefox etc.)
  by specifying --with-websocket or --with-websocket=ALL
* Automatic base64 {en, de}code on hybi-00 spec by specifying "bin" type in websocket.conf.
  ( my answer of https://github.com/nori0428/mod_websocket/issues/19 )
  A more detailed description has been described in the INSTALL.

Roadmaps for near future
------

I'll delete IETF-00 option when iOS supports RFC-6455 specs.

see below for browser support
[Can I use...](http://caniuse.com/#feat=websockets)

LICENCE
------
see COPYING.(same as lighty's LICENCE) and see lighttpd LICENCE.

great thanks to
------
Taiyo Fujii(@t_trace), Kensaku Komatsu(@komasshu),
Toshiro Takahashi(@tohirot), Nobuyoshi Miyokawa(@nmiyo),
Takezo(@velvetpass),
Aaron Mitchell,
and lighty developpers!

