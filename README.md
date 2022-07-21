# suckless
My config of some suckless software, especifically dwm, st and slstatus
## Install
clone this repo

`$ git clone --depth=1 https://github.com/grezzzo/suckless`

`cd suckless`
there are 6 folders, depending on what you want to install `cd` into it
now you can check and modify the config.h file or just `# make clean install`

## Especific dwm config
Using a text editor like nano or vim, edit the .xinitrc file in home directory add 

`exec dwm`

then you can use `startx` to enter dwm

**if you get errors at compiling, maybe you have some missing packages**
try installing

`base-devel`
`libX11`
`xorg-server`
`xorg-init`
`libxinerama`
`libxft`
