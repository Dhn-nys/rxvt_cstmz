# rxvt customize (rxvt-unicode)
urxvt-unicode commonly known as rxvt, is a color VT102 terminal emulator for X windows systems. urxvt was written by Marc Lehmann in 2003. urxvt can run in daemon mode, that is, it reduces memory usage and loading during terminal usage.

## Install

Ubuntu.

``sudo apt-get install rxvt-unicode-256color ncurses-term``

``git clone https://github.com/muennich/urxvt-perls``

``mv urxvt-perls/{clipboard,keyboard-select,url-select} /usr/lib/urxvt/perls``

Arch.

``yaourt -S rxvt-unicode-patched urxvt-perls``

or

``pacman -Sy rxvt-unicode``

## Config

on ubuntu the file is in ``~/.Xdefaults``, while in arch linux it is ``~/.Xresources``. if it doesn't exist in ubuntu or arch, you first create the file.

## Use config

Ubuntu.

``sudo xrdb ~/.Xdefaults``

Arch.

``sudo xrdb ~/.Xresources``
