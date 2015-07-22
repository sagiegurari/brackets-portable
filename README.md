# brackets portable

## Overview
Brackets is an open source code editor for web designers and front-end developers.

With brackets portable you can now 'install' it on a USB and have it with you at all times.

This portable launcher (with brackets embedded) will not leave any file/registry leftovers in your PC and will store all information in the portable folder.

All custom extensions you install will also be stored in the portable folder and will carried with you in your USB.

You can also replace the brackets installation inside this portable version with any version you like.

The portable launcher uses the [portableapps.com](http://portableapps.com/) installer which also allows you to better integrate with your [portableapps.com](http://portableapps.com/) installation (this is of course optional).

For portable chrome support please use the second 'BracketsPortableWithPortableChromeSupport.exe' exe file (requires admin permissions).

## Download
In order to download please look at the releases tab at: https://github.com/sagiegurari/brackets-portable/releases/latest and download the exe file.

## License
Developed by Sagie Gur-Ari and licensed under the MIT open source license.

## Building From Source
In order to build from source there are few steps to be taken:
* Build exe files - This one actually needs to be handled only once, even if upgrading the brackets.io installation<br>
To generate the exe files, you must use the portableapps.com launcher generator and point it to the main directory (git root).<br>
The generator uses the files in the AppInfo directory to generate the exe files.<br>
You can later on modify the launcher ini files without any need of regenerating the exe files.
* Build setup.exe - This step needs to be taken for any change (including upgrade of the brackets.io installation)
  * Update the brackets.io files in the Brackets folder
  * Update the version in the appinfo.ini
  * Use the portableapps.com installer to generate the new installer
