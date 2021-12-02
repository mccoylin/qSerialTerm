ABOUT
=====

qSerialTerm is a Qt based serial port terminal emulator.

qSerialTerm can interpret the incoming serial data as:

+ Text
+ Plots
+ Images

qSerial can send data as:

+ Text
+ Frames

The frame mode is useful for servomotor control.

DEPENDENCIES
============

+ Qwt library
+ QtSerialPort API

Install library
 $ sudo apt install -y libqt5serialport5 libqt5serialport5-dev libudev-dev libqwt-qt5-dev

For installation steps, check the wiki at:
https://github.com/JorgeAparicio/qSerialTerm/wiki

BUILDING
========

 $ mkdir build
 $ qmake -o build/Makefile
 $ cd build
 $ make

DEVELOPMENT
===========

For further development Qt Creator is recommended.


NOTE
====
 Change the project to QT5, and build in Ubuntu 20.04

LICENSE
=======

The qSerialTerm code is released under the terms of the GNU General Public
License (GPL) version 3.

See COPYING.GPL3.txt for more details.
