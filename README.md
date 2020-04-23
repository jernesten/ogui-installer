# ogui-installer

ogui installer for debian & ubuntu systems

----
State: in development
----

## Tests results

| Distro             | Result  |
| ------------------ |--------:|
| Bunsenlabs Debian  | see *1  |
| Ubuntu + Openbox   | see *1  |
| Linuxmint Cinnamon | Working |
| Xubuntu            | Working |
| Lubuntu            | soon    |
| Kubuntu            | soon    |

***1:** Working but the menu don't read ~/.local/share/applications/ogui.desktop and cant'be manually added

Solution: Copy ~/.local/share/applications/ogui.desktop in othe directory and launch it from there.

## What should the Installer be able to do?

- install gdrive ocamlfuse from PPA in the system
- install OGUI
- uninstall gdrive ocamlfuse and delete the PPA
- uninstall OGUI


