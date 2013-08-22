dbus-c++
========

A fork of the dbus-c++ library at version 0.5.0 with fixes.
The first set are added from patches in the RedHat 6.x releases.

The other patches are for bugs discovered at Stratus - and include:

- fix for deadlock when calling a method within a message handler.
