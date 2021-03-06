# Archlinux Ultimate Install Script

Install and configure archlinux has never been easier!

You can try it first with a `virtualbox`

## Prerequisites

- A working internet connection
- Logged in as 'root'

## How to get it
### With git
- Upgrade your system: `pacman -Syu`
- Install git: `pacman -S git`
- get the script: `git clone git://github.com/helmuthdu/aui`

### Without git
- Upgrade your system: `pacman -Syu`
- get the script: ` wget --no-check-certificate https://github.com/helmuthdu/aui/tarball/master -O - | tar xz`

## How to use
- default mode: `cd <dir> && ./aui`
- ais mode: `cd <dir> && ./aui --ais`

## Archlinux Install Script Mode
- Configure keymap
- Select editor
- Create partition
- Format device
- Install system base
- Configure fstab
- Configure hostname
- Configure timezone
- Configure hardware clock
- Configure locale
- Configure mkinitcpio
- Install/Configure bootloader
- Configure mirrorlist
- Configure root password

## Default mode
- Backup all modified files
- Install additional repositories
- Install and configure reflector
- Create and configure new user
- Install and configure sudo
- Configure pacman package signing
- Automatic enable services in systemd
- Install an AUR Helper [yaourt, packer]
- Install base system
- Install systemd
- Install Preload
- Install Zram
- Install Xorg
- Install GPU Drivers
- Install CUPS
- Install Additional wireless/bluetooth firmwares
- Ensuring access to GIT through a firewall
- Install a Desktop Environment [Cinnamon, E17, GNOME, KDE, LXDE, OpenBox, XFCE]
- Install Developement tools [Vim, Emacs, Eclipse...]
- Install Office apps [LibreOffice, GNOME-Office, Latex...]
- Install System tools [Wine, Virtualbox, Grsync, Htop]
- Install Graphics apps [Inkscape, Gimp, Blender, MComix]
- Install Internet apps [Firefox, Google-Chrome, Jdownloader...]
- Install Multimedia apps [Rhythmbox, Clementine, Codecs...]
- Install Games [HoN, World of Padman, Wesnoth...]
- Install Fonts [Liberation, MS-Fonts, Google-webfonts...]
- Install and configure Web Servers
- Many More...

If you like my work, please consider a small Paypal donation at helmuthdu@gmail.com :)
