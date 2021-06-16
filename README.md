Melcha Gtk Theme
======

Meltcha is a flat Design theme for GTK 3, GTK 2 and Gnome-Shell which supports GTK 3 and GTK 2 based desktop environments like Gnome, Unity, Budgie, Pantheon, XFCE, Mate, etc. And suprisingly pastel pink themed!

And this theme is on it's turn based on vinceliuice's Matcha theme, mostly customized for my #FAACAC needs! 
vinceliuce - Matcha gtk theme: https://github.com/vinceliuice/Matcha-gtk-theme

The original theme is based on Arc gtk theme of horst3180. Thanks horst3180 sincerely for his great job!
horst3180 - Arc gtk theme: https://github.com/horst3180/Arc-theme

## Info

### GTK+ > 3.20

### GTK2 engines requirment
- GTK2 engine Murrine 0.98.1.1 or later.
- GTK2 pixbuf engine or the gtk(2)-engines package.

Fedora/RedHat distros:

    yum install gtk-murrine-engine gtk2-engines

Ubuntu/Mint/Debian distros:

    sudo apt-get install gtk2-engines-murrine gtk2-engines-pixbuf

ArchLinux:

    pacman -S gtk-engine-murrine gtk-engines

Solus:

    sudo eopkg it gtk2-engine-murrine gtk-engines

Other:
Search for the engines in your distributions repository or install the engines from source.

## Install

### Install from source file

Double-click to open that script file,
Or open the terminal at current directory.
Right now, since I don't plan to package this. This is the only way to do it!

Run

    ./install.sh

Usage:  `./install.sh`  **[OPTIONS...]**

|  OPTIONS:     | |
|:--------------|:-------------|
| -d, --dest    | Specify theme destination directory (Default: $HOME/.themes) |
| -n, --name    | Specify theme name (Default: Matcha) |
| -c, --color   | Specify theme color variant(s) **[standard/light/dark]** (Default: All variants) |
| -t, --theme   | Specify hue theme variant(s) **[aliz/azul/sea]** (Default: All variants) |
| -g, --gdm     | Install GDM theme, this option need root user authority! please run this with sudo |
| -r, --revert  | revert GDM theme, this option need root user authority! please run this with sudo |
| -h, --help    | Show this help |
