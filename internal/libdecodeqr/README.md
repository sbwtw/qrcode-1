# libdecodeqr

## Whta's this?

"libdecodeqr" is a C/C++ library for docoding QR code, which based on JIS X 0510 and ISO/IEC18004.

This library is able to decode miscellaneous images those are taken with a file, with a webcam, with a scanner, and so on.

## Features

 * Supports miscellaneous image formats and input devices.
 * Hi-Speed decoding.
 * Completely Free.

## Requirements

 * g++ / VC++6
 * [OpenCV](http://www.sourceforge.net/projects/opencvlibrary/) 0.9.7 or later
 * Gtk2 for UN*X (required by OpenCV) 

## Download

### Binary Release

Sorry, Not available yet.

### Latest Stable Source Code

 * version 0.9.3 http://trac.koka-in.org/libdecodeqr/attachment/wiki/WikiStart/libdecodeqr-0.9.3.tar.bz2

### Latest Development Source Code

We use Subversion for source revision control and code sharing.

	svn co svn://svn.koka-in.org/libdecodeqr/trunk

## How to use

### Build and Intstall

see BuildAndInstall for detail.

#### Windows

 1. open $(archive_dir)/src/libdecodeqr/libdecodeqr.dsw
 1. build the project (press [F7] key)

or

 1. start command prompt
 1. run VCVARS32.BAT
 1. nmake libdecodeqr.mak

The Libraly file and header files are NOT installed automaticaly.
After building, set places of decodeqr.h, qrtypes.h, qrerror.h and libdecodeqr.lib to your environments if you need.

#### UN*X

 1. $ cd $(archive_dir)/src/
 1. $ ./configure
 1. $ make
 1. $ sudo make install

### API Reference

see [ApiReference](https://github.com/chai2010/qrcode/blob/master/internal/libdecodeqr/doc/ApiReference.ja)

### Sample Codes

 * [latest simple usage](https://github.com/chai2010/qrcode/tree/master/internal/libdecodeqr/examples/simple/simpletest.cpp)
 * [latest with webcam](https://github.com/chai2010/qrcode/tree/master/internal/libdecodeqr/examples/webcam/webcam.cpp)

## How to Hack

see [HackingGuide](https://github.com/chai2010/qrcode/blob/master/internal/libdecodeqr/doc/HackingGuide.ja)

## Contact Us

### Web Page

http://trac.koka-in.org/libdecodeqr

### Mailing List

mailto:libdecodeqr@koka-in.org

To subscribe this list, please send the following phrase

	subscribe Your-Last-Name Your-First-Name 

e.g.

	subscribe NISHI Takao

in the mail body (not subject) to the address <libdecodeqr-ctl@koka-in.org>.

## Copying

```
Copyright (c) 2007 NISHI Takao <zophos@koka-in.org>, 
JMA (Japan Medical Association) and 
!NaCl (Network Applied Communication Laboratory Ltd.) All rights reserved.[[BR]]
This is free software with ABSOLUTELY NO WARRANTY.

You can redistribute and/or modify it under the terms of LGPL.
```

