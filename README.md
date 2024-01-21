# webbox
# version 1.0

INFO :
- running apps web window
- just running on desktop xfce4

COMMAND INSTALL TERMUX :
- $ apt install gtk3 webkit2gtk-4.1
- $ cd webbox
- $ dpkg -i webbox_xfce4_termux_0.2.deb

COMMAND INSTALL LINUX :
- $ sudo apt install gtk3* libwebkit2gtk-4.1-dev
- $ cd webbox
- $ dpkg -i webbox_xfce4_linux_0.2.deb

COMMAND PENGGUNAAN :
- $ mv icon_name.png icon_name.svg
- $ webbox -b <[icon_name]> <[app_name]> <[url]> <[hsize]> <[vsize]>
  |__ create costum app
- $ webbox -d <[icon_name]> <[app_name]>
  |__ delete costum app