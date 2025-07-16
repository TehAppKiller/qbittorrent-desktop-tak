# qbittorrent-desktop-tak
[![qbittorrent-desktop-tak](https://snapcraft.io/qbittorrent-desktop-tak/badge.svg)](https://snapcraft.io/qbittorrent-desktop-tak)
![snap arch](https://badgen.net/snapcraft/architecture/qbittorrent-desktop-tak)
![snap size](https://badgen.net/snapcraft/size/qbittorrent-desktop-tak/amd64/stable)

## Snap Description
UnOfficial release of qBittorrent for Desktop (with graphical UI)\
https://snapcraft.io/qbittorrent-desktop-tak

(For Server edition see [qbittorrent-tak](https://github.com/TehAppKiller/qbittorrent-tak))

## qBittorrent Description
<img src="/icon.svg" width="100">
qBittorrent is a free and open-source BitTorrent client
based on the Qt toolkit and libtorrent-rasterbar library.

See https://www.qbittorrent.org for more details.

## Information
qBittorrent Release 5+\
Snap dependencies required: kf6-core24, gtk-common-themes

**!!! Files can only be written in a directory owned by `user` !!!**

This is due to current behavior and restrictions of snaps by Canonical.\
Please use Server edition if you need to write in `root`-owned folders: https://snapcraft.io/qbittorrent-tak

## FAQ
See my common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).
### How to access Configuration file
You need to access the snap in shell mode and edit the file with Vim:
```
sudo snap run --shell qbittorrent-desktop-tak.qbittorrent
vi $SNAP_USER_DATA/.config/qBittorrent/qBittorrent.conf
```
One help sheet of Vim commands available [here](https://devhints.io/vim).

## Building
See my common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).

## Versionning
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
