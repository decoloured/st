# 🎛 *st*

the vaccine :

## patches

+ pywal support
+ anysize
+ boxdraw
+ font2
+ ligatures
+ newterm
+ sync

## keybindings

+ `alt+[c, v]` to copy/paste
+ `alt+enter` to create a new terminal with the same working directory
+ `alt+[up, down]` to increase/decrease font size
+ `alt+0` to reset font size

## building

+ clone this repository
+ replace `i9p` in `#include "/home/i9p/.cache/wal/colors-wal-st.h"` (`config.h` - line 108) with your username
+ execute `make clean install` as root

