# FluffyPGP-Applet
The FluffyPGP Applet implements the OpenGPG Card v 2.0.1 specification without using secure channels or Global Platform for portability.

Card Requirements
==================
- Java card version 2.2.2 (2.2.1 might work but it is untested)
- Global platform 2.1.1 or above to use the loading scripts.
- 2048 bit RSA keys
- Random number generation
- Private DOs

License 
=======
The source code is released under GPL3 and is free, you can redistribute it and/or modify it under the terms of the GNU General Public License.

Building
===

Using [JCIDE](http://javacardos.com/javacardforum/viewtopic.php?f=26&t=43?ws=github&prj=fluffyPGP) open this project,  Click "Buid All Packages(F7)" to build the source code and click "Debug" or "Run" you can Debug/run this project using Java Card Simulator.


Brief Usage:
============

The easiest way is to use [pyApduTool](http://javacardos.com/javacardforum/viewtopic.php?f=3&t=38?ws=github&prj=fluffyPGP)  to install the CAP file

The actual parameters used to load the applet on the card depend on the card manufacturer, version and state.

Discussion
===
Have doubts? You can visit [Here](http://javacardos.com/javacardforum/viewforum.php?f=35?ws=github&prj=fluffyPGP) to ask and discuss.
