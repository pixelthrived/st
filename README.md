# st
My own fork of the Suckless Terminal (ST).

# What is ST?
ST, The suckless terminal / The simple terminal is a terminal developed by suckless. It is very minimal, fast and lightweight. Functionality can be added via ptching the terminal as well.

# What things does this build have?
This build provides scrolling via the mouse,

8 themes to choose from ( can be selected via the keyboard )

The MesloLGS NerdFont Regular ( will be installed automatically when you compile this build ) with the size of 20

Fullscreen functionality

Font size can be modified as well ( you need to run ./path/to/st -z [your fontsize])

The bold is not bright patch

And lastly, the clipboard patch.

# Dependencies
On Arch Linux (Arch-based Distributions)

```
sudo pacman -S base-devel libx11 libxft libxinerama freetype2 fontconfig git
```

On Debian GNU/Linux (Debian-based Distributions)

```
sudo apt install build-essential libx11-dev libxft-dev libxinerama-dev libfreetype6-dev libfontconfig1-dev git
```

# Installation
```
git clone https://github.com/BogdanInfinity2078/st
cd st
sudo make clean install
```
Done. Run ST with 'st' command.

# Keybindings
Change colors         = 		ALT + 1-8

Enter/Exit fullscreen =			F11

Scroll Back	      =			Mouse Wheel Up (go up), Mouse Wheel Down (go down) / Shift + Mouse Wheel Up/Down (go up/down), Shift + PbUp/PbDown (go up/down)
