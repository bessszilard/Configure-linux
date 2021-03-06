# Custimize Ubuntu 18.04 LTS

* [30 Things to do After Installing Ubuntu 18.04 LTS (all-in-one video)](https://www.youtube.com/results?search_query=things+to+change+after+installing+ubuntu+18.04)
* [Ubuntu 18.04 - Super + Number keys aren't working when “Dash to panel” is active](https://askubuntu.com/questions/1061811/utuntu-18-04-super-number-keys-arent-working-when-dash-to-panel-is-active)
* Move save button (file dialog) on to the buttom: [Move GNOME file dialog buttons](https://askubuntu.com/questions/1031665/move-gnome-file-dialog-buttons)
* Change language layout with ALT+SHIFT: [18.04 ctrl+shift to change language](https://askubuntu.com/questions/1029588/18-04-ctrlshift-to-change-language)
  * The best layout is: `102/QWERTY/dot/dead keys`
* Easily switch between sound devices: [How can I easily switch audio output in Ubuntu 17.10 and later with GNOME?](https://askubuntu.com/questions/970323/how-can-i-easily-switch-audio-output-in-ubuntu-17-10-and-later-with-gnome)
* [Nautilus not showing mounted drives in side bar](https://askubuntu.com/questions/1036773/nautilus-not-showing-mounted-drives-in-side-bar)
* [How to snap a window to the top/bottom with GNOME?](https://superuser.com/a/1431887)
* [Setting LTS 18.04 to High Performance mode](https://askubuntu.com/a/604870)
* [Minimize keyboard shortcut on ubuntu](https://askubuntu.com/questions/123223/what-is-the-keyboard-shortcut-to-minimise-a-window-to-launcher-in-unity)
  * Keyboard shortcuts -> Hide Window

## Install
* [Github Desktop](https://github.com/shiftkey/desktop/releases)
  * I was not able to login, because the firewall was blocked it
* Open arc menu with super key
  * right click on the menu
  * Arc Menu Settings
  * Arc Menu Hotkey
  
## Fix
  * [How to enable the Edit button in Shutter?](https://askubuntu.com/questions/1029085/how-to-enable-the-edit-button-in-shutter)
  * [Reset notification panel](https://askubuntu.com/a/1117115) ```(Alt+F2) gnome-shell --replace```
  * Search only in the local folder (skip subfolders): [gsettings set org.gnome.nautilus.preferences recursive-search 'never'](https://superuser.com/a/1395223)
  * [« Could not read the contents of '/media': Permission denied »](https://askubuntu.com/questions/1178148/could-not-read-the-contents-of-media-permission-denied)
    * Solution is not to use snaps.
  * [Prevent KWrite backup files](https://www.linuxquestions.org/questions/linux-newbie-8/how-to-prevent-backup-file-creation-kate-and-kwrite-940857/)
```
    Settings > Configure Kate > Editor Component > Open/Save > Advanced
    Uncheck the box next to local files under Backup on Save
```

## [Remap mouse button](Remap-Mouse-buttons-to-copy-paste.md)

## VS Code
* [Visual Studio Code - Terminal Blank Screen](https://stackoverflow.com/questions/54092486/visual-studio-code-terminal-blank-screen)
