# Kameleon (Plymouth)

This theme is part of the Kameleon project

## Project

Kameleon is a project to create a full desktop theming to (I know, I know) looking like Windows 10. Nowadays Windows 10 seems to looking like KDE so ...

## Installation

### Debian

Settings this theme as default on Debian :

```
sudo plymouth-set-default-theme -R kameleon
```

### Ubuntu

Settings this theme as default on Ubuntu :

```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/kameleon/kameleon.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
```

## Credits

This theme is adapt from original Deb10. All copyrights, credits and everything goes to their original authors.
