# macfand 
Fan control daemon for Apple Computers running Linux through the applesmc kernel module.

## Configuration
See the [Configuration](https://github.com/ablakely/macfand/wiki/Configuration) wiki page

## Installing

    make
    sudo make install
    
    sudo systemctl enable --now macfand

macfand is available in the Arch User Repository (AUR) as [macfand-git](https://aur.archlinux.org/packages/macfand-git)


## Compatibility

See [Compatibility.md](https://github.com/ablakely/macfand/blob/master/Compatibility.md)

## libconfig
macfand requires [libconfig](http://hyperrealm.github.io/libconfig/) which is available on many distrobutions.

### Debian / Ubuntu / Mint / Elementary OS / MX / Pop!_OS / Zorin

    sudo apt-get install libconfig-dev

### Arch / Manjaro / EndeavourOS 

    sudo pacman -S libconfig

### Fedora / CentOS / Rocky

    sudo yum install libconfig

### Gentoo

    sudo emerge dev-libs/libconfig

### openSUSE

    sudo zypper install libconfig-devel

### Alpine

    sudo apk add libconfig



---
See the manual page `macfand(1)` for more information.

Copyright &copy; 2022 Aaron Blakely


Support for this software is available on [IRC](https://webchat.ephasic.org/?join=ephasic)
