# rxvt customize (rxvt-unicode)

Autor : Dhn-nys.

## Install

Ubuntu.

``sudo apt-get install rxvt-unicode-256color ncurses-term``

``git clone https://github.com/muennich/urxvt-perls``

``mv urxvt-perls/{clipboard,keyboard-select,url-select} /usr/lib/urxvt/perls``

Arch.

``yaourt -S rxvt-unicode-patched urxvt-perls``

## Config

on ubuntu the file is in ``~/.Xdefaults``, while in arch linux it is ``~/.Xresources``. if it doesn't exist in ubuntu or arch, you first create the file.

## Use config

Ubuntu.

``sudo xrdb ~/.Xdefaults``

Arch.

``sudo xrdb ~/.Xresources``
