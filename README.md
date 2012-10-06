ISOMounter
==========

*ISOMounter* is a tool to allow changing a mounted ISO image
according to the requirements of another gui-based application.

While the applicaiton is active, ISOMounter sits on the side 
and allows ISO images to be selected and mounted.

Usage
-----

    isomounter /path/to/application

or

    isomounter /path/to/application /path/to/iso-directory

In the first form, *ISOMounter* will look for ISO images in
an `./iso` subdirectory.

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
