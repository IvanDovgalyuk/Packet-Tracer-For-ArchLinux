# Packet-Tracer

This repo for Packet_Tracer Binary File for Arch Linux

# first things install debtap : 

to install just run one of these commands

`yay -S debtap`  if you use AUR package manager

and `sudo pacman -S debtap` if you use Pacman package manager


or The solution is found here [main repo](https://aur.archlinux.org/packages/debtap)

Download the [debtap snapshot](https://aur.archlinux.org/cgit/aur.git/snapshot/debtap.tar.gz) then 

Extract and make:
==================

    $ tar zvxf ~/Downloads/debtap.tar.gz -C ~/arch
    $ cd ~/arch/debtap 
    $ makepkg -s 
    $ sudo pacman -U debtap-3.1.4-2-any.pkg.tar.xz


also you can read [this repo](https://github.com/mmsaeed509/debtap) for helping


# Converting Debian Binary Package to Arch Binary Package


we will convert Packet_Tracer now 

open up the terminal and change the directory to the Binary Package directory then run these commands

1 `ls` to show the package
