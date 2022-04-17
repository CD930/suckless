# suckless
My config of some suckless software, especifically dwm, st and slstatus
## Install
clone this repo

`$ git clone --depth=1 https://github.com/grezzzo/suckless`

`cd suckless`
there are 3 folders, depending on what you want to install `cd` into it
now you can check and modify the config.h file or just `sudo make install`

## Especific dwm config
Using a text editor like nano or vim, edit the .xinitrc file in home directory add

`exec dwm`

then you can use `startx` to enter dwm

**if you can't compile dwm, maybe you have some missing packages**
