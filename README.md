Getting Started
Installation
Minimum Requirements
Python Installation
Java Installation
Build SSTools4MC Installer by yourself
Clone this Repository
Install NSIS
Verify Files
Edit .nsi file
Compile the Installer
Copyright and Disclaimer
Important and Acknowledgments

You can follow this steps if you want to build the SSTools4MC Installer from the source code by yourself. Please note that this is not mandatory. You can always download the latest version of the installer from the GitHub Releases page.

Clone this Repository
First, clone/download this repository:

git clone https://github.com/ngdplnk/SSTools4MC.git
Install NSIS
You need to install the latest NSIS (Nullsoft Scriptable Install System) version to build the installer. You can download it from NSIS Official Website. Be sure to follow the on-screen instructions to complete the installation.

Verify Files
Navigate to the 3-launcher folder in the cloned repository and there select a release channel that you want to build the launcher for (continue in subdirectory 1-stable-channel for Stable channel or in subdirectory 2-dev-channel for Dev Channel). Ensure that you have the following files (there may be more, but you need to have at least these):

If you are building the launcher for the Stable channel:

build.nsi
icon.ico
launcher.pyw
If you are building the launcher for the Dev channel:

build-dev.nsi
icon-dev.ico
launcher-dev.pyw
If any of these files are missing, please download them directly from the repository.

You will use the main.py from the 1-stable folder if you are building the Stable Channel Launcher, or the dev.py file from the 2-dev folder as your bundled version in the launcher you are building.

Edit .nsi File
Open the build.nsi or build-dev.nsi file in a text editor and replace the placeholders <TYPE THE XXXX PATH HERE> with the actual paths to your files, respectively. Save the changes.

Compile the Installer
Open NSIS.
Select the option "Compile NSI Scripts".
Drag and drop the file you just edited into the NSIS window.
An installer for your desired SSTools4MC release channel will be created.
Enjoy!
Copyright and Disclaimer
SSTools4MC and each of its tools are not official Minecraft products and are not endorsed by Mojang.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (SSTools4MC), to use the software without restriction, including, but not limited to, the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, and to permit persons to whom the software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the software.
THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

"Minecraft" is a registered trademark of Mojang Synergies AB and is not affiliated with this software.

Oracle, Java, and MySQL are registered trademarks of Oracle and/or its affiliates. Other names may be trademarks of their respective owners.

This repository or its owner does not own or store any Mojang Synergies AB products, and the availability of these products is not dependent on him or this repository.

This repository or its owner does not own or store any Oracle products, and the availability of these products is not dependent on him or this repository.

All Mojang Synergies AB-related elements and names are used in compliance with the Minecraft Commercial Usage Guidelines and Brand and Asset Usage Guidelines.

All Oracle-related elements and names are used in compliance with the Oracle Terms of Use and Trademarks.

Credits and Acknowledgements
So many thanks to @naicoooossj and @LegalizeNuclearBombs :shipit: for testing and giving new ideas to this project.

Credits to Alfredo Creates on Flaticon for creating the icons used in SSTools4MC: (1) and (2)- Both licensed under CC 3.0 BY

Thank you for using SSTools4MC!

Licensed under MIT License - Copyright © 2025 ngdplnk
