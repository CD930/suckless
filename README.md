# suckless
My config of some suckless software, especifically dwm, st and slstatus
## Install
clone this repo

`$ git clone --depth=1 https://github.com/grezzzo/suckless`

`cd suckless`
there are 3 folders, depending on what you want to install `cd` into it
now you can check and modify the config.h file or just `sudo make clean install`

by the way, you will need the package "font-awesome5" if you want to have icons in the top bar

## Especific dwm config
Using a text editor like nano or vim, edit the .xinitrc file in home directory add

`exec dwm`

then you can use `startx` to enter dwm

**if you can't compile dwm, maybe you have some missing packages**
try installing

`base-devel`

`libX11`

`xorg-server`

`xorg-init`

`libxinerama`

`libxft`
