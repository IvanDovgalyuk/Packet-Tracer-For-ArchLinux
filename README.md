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
![1_ls](https://user-images.githubusercontent.com/62524855/128854991-7a2bf790-fb17-4a54-aca5-776c310ef1b0.png)

2 `chmod` to give permissions
![2_chmod +x ](https://user-images.githubusercontent.com/62524855/128855621-8f60d8e6-6d49-40d6-a88d-9079dcf973ff.png)

3 `debtap` for help
![3_debtap_help](https://user-images.githubusercontent.com/62524855/128855724-f7960f2b-179e-4771-95c4-f295c1986fd9.png)






