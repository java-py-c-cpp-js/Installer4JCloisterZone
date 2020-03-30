# Installer4JCloisterZone

This repository contains my ideas that belongs to https://github.com/farin/JCloisterZone/issues/293.
It contains the configuration files for launch4j and Inno Setup Compiler for creating a simple to use setup for installing JCloisterZone on Windows.

## Compile the Installer4JCLoisterZone.exe

Prerequirements: 

 - Windows (or maybe Linux with wine? - I have not tested that until now, but maybe that works, too)
 - Inno Setup Compiler (https://jrsoftware.org/isdl.php#stable)
 - Launch4J (https://sourceforge.net/projects/launch4j/).

For compiling, you first have to download the current JCloisterZone.7z file and unzip it.
Then you have to change each "C:\Users\Nutzer\Downloads" in the config files and replace it with the real location of the unzipped data.
Also, you have to download the license file of JCloisterZone from the official JCloisterZone repo and the icon, converted to .ico format, that can be found in this repo, and update the corresponding paths in the config files.
After that, you should install Launch4j and open the JCloisterZone_launch4j.cfg.xml file with it. A click on the gear ("Build wrapper") starts building an .exe-file for launching JCloisterZone.
If this is done, you can open JCloisterZoneInno.iss with the Inno Setup Compiler and build the setup file.
