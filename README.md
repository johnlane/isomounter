ISOMounter
==========

*ISOMounter* is a tool to manage mounting of optical discs or
ISO image files according to the requirements of another gui-
based application.

While the applicaiton is active, ISOMounter sits on the side 
and allows ISO imagefiles or optical drives to be selected
and mounted.

Usage
-----

    isomounter /path/to/application

or

    isomounter /path/to/application /path/to/iso-directory

In the first form, *ISOMounter* will look for ISO images in
an `./iso` subdirectory.

A menu is provided listing all the ISO images that are found
plus all the optical drives that are found.

When a mount is in place the menu also includes an option to
do an unmount. Unmounting is performed automatically when a 
new item is selected so use of this option is usually un-necessary.
The reason for this option is to allow an optical medium to be
un-mounted so that it can be replaced with another.

*ISOMounter* exits automatically when the application exits.

Prerequisites
-------------

*ISOMounter* uses `sudo` to perform mount/unmount operations.

Rationale
---------

Like many useful utilities, ISOMounter was written to serve a
pressing need: running the [X-Plane](http://www.x-plane.com)
installer while quickly changing DVDs as required when loading
scenery.

License
-------

MIT License: See LICENSE file

Latest Version
--------------

Obtain the latest version from [GitHub](https://github.com/johnlane/isomounter).
