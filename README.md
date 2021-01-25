## Linux Kernel PKGBUILD with QCA6390 (AX500-DBS) support

This `PKGBUILD` generates two packages that contains the patchset from [Kalle Valo](https://github.com/kvalo)'s
[`ath11k-qca6390-bringup` branch](https://git.kernel.org/pub/scm/linux/kernel/git/kvalo/ath.git/log/?h=ath11k-qca6390-bringup).

Build and install them in your Arch or Manjaro Linux, and then you'll get the stable WiFi support
in your [Dell XPS 13" 9310](https://wiki.archlinux.org/index.php/Dell_XPS_13_(9310)):

```
$ makepkg -s
...
$ pacman -U linux510-qca6390-*.pkg.tar.*
...
```
