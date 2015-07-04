# aur-packages

My personal repository of [AUR packages](https://aur.archlinux.org/packages/?SeB=m&K=jweslley).


## Quick commands

### Prerequisite software

    pacman -S base-devel pkgbuild-introspection


## AUR4

### Submitting packages

    mksrcinfo
    git commit -am 'Update to 1.0.0'
    git push

## AUR3

### Building packages

    makepkg -s

### Checking package sanity

    namcap PKGBUILD
    namcap <package file name>.pkg.tar.xz

### Installing packages

    makepkg --install

### Submitting packages

    makepkg --source

## References

* https://wiki.archlinux.org/index.php/Arch_User_Repository
* https://wiki.archlinux.org/index.php/Creating_packages
* https://wiki.archlinux.org/index.php/PKGBUILD
