# ogui-installer

ogui installer for debian & ubuntu systems

----
State: Testing some Dristos with different Desktop systems
----

## Tests results for installer and GUI Application

Only 2 small errors found:

|ID|Problem|Solution|
|--|:-----:|:------:|
|**1: Openbox menu**| Working but the menu can't launch ~/.local/share/applications/ogui.desktop and I couldn't find how work around it. | Copy ~/.local/share/applications/ogui.desktop into an other directory and launch it from there.|
|**2: Custom Ubuntu XFCE**| In an ubuntu + xfce custom distro the launcher (~/.local/share/applications/ogui.desktop) has being build with errors (unknowed causes) | Use Installation guide in https://github.com/jernesten/ogui to build it correctly.|

## What should the Installer be able to do?

- install gdrive ocamlfuse from PPA in the system
- install OGUI
- uninstall gdrive ocamlfuse and delete the PPA
- uninstall OGUI

## How to use

- Clone or download the repo
```
git clone https://github.com/jernesten/ogui-installer
```
- extract if needed (if you've download a zip)
- go to the directory
- execute script ('chmod +x ogui-installer' may be needed)
```
sh ogui-installer
```
-choose your option in the menu
```
1. Only install OGUI, GDrive Ocamlfuse is already installed
2. Install both OGUI and GDrive Ocamlfuse
3. Uninstall OGUI
4. Uninstall both OGUI and GDrive Ocamlfuse (It will also remove PPA)
5. Exit            
```

