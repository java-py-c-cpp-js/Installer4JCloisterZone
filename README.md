# Installer4JCloisterZone

This repository contains my ideas that belongs to https://github.com/farin/JCloisterZone/issues/293.
It contains the configuration files for launch4j and Inno Setup Compiler for creating a simple to use setup for installing JCloisterZone on Windows.

# Download

To download the ready-to-use setup, go to the release tab on GitHub: https://github.com/java-py-c-cpp-js/Installer4JCloisterZone/releases

## How to build the Installer4JCloisterZone.exe

Prerequirements: 

 - Windows (or maybe Linux with wine? - I have not tested that yet, but maybe that works, too)
 - Inno Setup Compiler (https://jrsoftware.org/isdl.php#stable)
 - Launch4J (https://sourceforge.net/projects/launch4j/).

For compiling, you first have to download the current JCloisterZone.7z file and extract it to this directory.
After that, you should open the JCloisterZone_launch4j.cfg.xml file with Launch4J. A click on the gear ("Build wrapper") starts building an .exe-file for launching JCloisterZone.
If this is done, you can open JCloisterZoneInno.iss with the Inno Setup Compiler and build the setup file. 
It will appear in the ./Output/ folder.

## License of this installation software for JCloisterZone, the provided binary and the regarding configuration files in this repo:

(Info: The copyright of Jordan Russell and Martijn Laan belongs to Inno Setup, used for creating the setup file. The copyright of Grzegorz Kowal belongs to Launch4J, used for creating an .exe executable for the main .jar file. The copyright of Roman Krejcik belongs to the bundeled JClositerZone, which is installed by this installation program.)

    Installer4JCloisterZone
    Copyright (C) 2020 java-py-c-cpp-js
    Portions Copyright (C) 2004-2014 Roman Krejcik
    Portions Copyright (C) 1997-2020 Jordan Russell. All rights reserved.
    Portions Copyright (C) 2000-2020 Martijn Laan. All rights reserved.
    Portions Copyright (C) 2005-2017 Grzegorz Kowal 
    
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.
    
    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
