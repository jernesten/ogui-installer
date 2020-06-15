# :inbox_tray: ogui-installer

OGUI installer for debian & ubuntu systems
OGUI is a GUI App for google-drive-ocamlfuse writen in python. [More information](https://github.com/jernesten/ogui)

---

                      ||========================================================================||
                      ||                         OGUI INSTALLATION MENU                         ||
                      ||========================================================================||
                      ||                                                                        ||
                      || 1. Only install OGUI, GDrive Ocamlfuse is already installed            ||
                      || 2. Install both OGUI and GDrive Ocamlfuse                              ||
                      || 3. Uninstall OGUI                                                      ||
                      || 4. Uninstall both OGUI and GDrive Ocamlfuse (It will also remove PPA)  ||
                      || 5. Exit                                                                ||
                      ||                                                                        ||
                      ||========================================================================||
                      ||            Keep this Script to easily uninstall if needed              ||
                      ||========================================================================||
  

## :pushpin: What should the Installer be able to do?

- install gdrive ocamlfuse from PPA
- install OGUI
- uninstall gdrive ocamlfuse and delete the PPA
- uninstall OGUI

Only 2 small errors found:

||Problem|Solution|
|--|:-----:|:------:|
|**1: Openbox menu**| ~~Working but the menu can't launch $HOME/.local/share/applications/ogui.desktop~~ The application launcher don't need path anymore, so now it should work. Tested in a custom ubuntu + openbox with python3.6 and working. | Copy ~/.local/share/applications/ogui.desktop into an other directory and launch it from there.|
|**2: Custom Ubuntu XFCE**| In an ubuntu + xfce custom distro the launcher (~/.local/share/applications/ogui.desktop) has being build with errors (unknowed causes) | Use Installation guide in https://github.com/jernesten/ogui to build it correctly.|

## :wrench: How to use

- Clone or download the repo
```
git clone https://github.com/jernesten/ogui-installer
```
- extract if needed (if you downloaded a .zip)
- go to the extracted folder
- execute the script
```
chmod +x ogui-installer
sh ogui-installer
```
- choose your option in the menu
```
1. Only install OGUI, GDrive Ocamlfuse is already installed
2. Install both OGUI and GDrive Ocamlfuse
3. Uninstall OGUI
4. Uninstall both OGUI and GDrive Ocamlfuse (It will also remove PPA)
5. Exit            
```

