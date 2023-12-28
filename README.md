# webbox
# version 1.0

COMMAND LIBRARY TERMUX :
- $ apt install gtk3 webkit2gtk-4.1

COMMAND LIBRARY LINUX :
- $ sudo apt install gtk3* libwebkit2gtk-4.1-dev

COMMAND INSTALL :
- $ dpkg -i webbox_0.1.deb
- $ cd webbox
- $ cp app_termux/* ~/Desktop #if u use termux
- $ cp app_linux/* ~/Desktop #if u use linux

