# Packet-Tracer ![Cisco_Packet_Tracer_Icon](https://user-images.githubusercontent.com/62524855/131155846-a456ba16-8060-4372-ad59-7bf58925277c.png)


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

![1_ls](https://user-images.githubusercontent.com/62524855/128856034-e38746c9-d65f-4392-910a-c8a11793451b.png)

2 `chmod` to give permissions

![2_chmod +x ](https://user-images.githubusercontent.com/62524855/128855621-8f60d8e6-6d49-40d6-a88d-9079dcf973ff.png)

3 `debtap` or `debtap -h`for help

![3_debtap_help](https://user-images.githubusercontent.com/62524855/128855724-f7960f2b-179e-4771-95c4-f295c1986fd9.png)

4 first thing, we need to update debtap database `sudo debtap -u`

![4_update_database](https://user-images.githubusercontent.com/62524855/128856594-af1680ac-584d-4c29-aa64-d5302d3f5d74.png)

5 converting from .deb package to Arch package `sudo debtap <package_name>`

![5_convert_deb_to_arch](https://user-images.githubusercontent.com/62524855/128856897-f62c529b-a52b-47da-97d9-2ca48b613e05.png)

6 enter a package name to be the name of the package after installation

![6_name](https://user-images.githubusercontent.com/62524855/128857278-a3ad6fbe-b3a4-43d1-b3b7-2eb01f069105.png)

7 license package 
write anything or gnu or keep it empty then press enter to continue

![7_license](https://user-images.githubusercontent.com/62524855/128857613-408909df-b188-46a4-b690-301939247c80.png)


8 her press enter to continue

![8_enter_to_continue](https://user-images.githubusercontent.com/62524855/128857688-23ff63c3-e333-421c-a600-9d086bbf99b0.png)

9 successfully created

![9_successfully_created](https://user-images.githubusercontent.com/62524855/128857738-49e384c3-167b-434b-b3ee-cdc40d7695ba.png)

10 the package after converting

![10_package](https://user-images.githubusercontent.com/62524855/128857829-20758a15-8ff8-4718-ae58-1a18f88fd69e.png)

11 `ls` to show the new package

![11_ls](https://user-images.githubusercontent.com/62524855/128858450-38bb72cf-20ed-4a65-9955-0971070bd633.png)

12 now we can install the package 
first thing , `chmod` to give permissions

![12_chmod +x _ ls](https://user-images.githubusercontent.com/62524855/128858684-7988b43c-415d-48b5-8159-0d023501e4c4.png)

13 now the package is ready to install 
`sudo pacman -U <package_name>`

![13_install](https://user-images.githubusercontent.com/62524855/128858881-275819c6-7865-413c-9adf-765c3d1129a2.png)

14 the package after installation

![Screenshot_117](https://user-images.githubusercontent.com/62524855/128859327-1533df7d-0ce9-4605-a312-e72480efabbe.png)



























