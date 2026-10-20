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
qBittorrent Release\
Snap dependencies required: kf6-core24, gtk-common-themes

**!!! Files can only be written in a directory owned by `user` !!!**

This is due to current behavior and restrictions of snaps by Canonical.\
Please use Server edition if you need to write in `root`-owned folders: https://snapcraft.io/qbittorrent-tak

## FAQ
See my common doc about [FAQ](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#FAQ).

### How to access Configuration file
You can access the snap data in 2 ways:

#### - Directly
With default snapd installation:
```
/home/<user>/snap/qbittorrent-desktop-tak/current/.config/qBittorrent/qBittorrent.conf
```

#### - Via shell
In shell mode you can edit the file with Vim:
```
snap run --shell qbittorrent-desktop-tak.qbittorrent
vi $HOME/.config/qBittorrent/qBittorrent.conf
```
One help sheet of Vim commands available [here](https://devhints.io/vim).

## Building
The snap works on Core24 because of `kde-neon-6` dependency.\
See my common doc about [building a snap](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Building).

## Versionning
See my common doc about [versionning](https://github.com/TehAppKiller/Snapcraft-common-doc/tree/main#Versionning).
