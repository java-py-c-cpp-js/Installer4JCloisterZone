# Installer4JCloisterZone

This repository contains my ideas that belongs to https://github.com/farin/JCloisterZone/issues/293.
It contains the configuration files for launch4j and Inno Setup Compiler for creating a simple to use setup for installing JCloisterZone on Windows.

## Hot to build the Installer4JCLoisterZone.exe

Prerequirements: 

 - Windows (or maybe Linux with wine? - I have not tested that yet, but maybe that works, too)
 - Inno Setup Compiler (https://jrsoftware.org/isdl.php#stable)
 - Launch4J (https://sourceforge.net/projects/launch4j/).

For compiling, you first have to download the current JCloisterZone.7z file and extract it to this directory.
After that, you should open the JCloisterZone_launch4j.cfg.xml file with Launch4J. A click on the gear ("Build wrapper") starts building an .exe-file for launching JCloisterZone.
If this is done, you can open JCloisterZoneInno.iss with the Inno Setup Compiler and build the setup file. 
It will appear in the ./Output/ folder.