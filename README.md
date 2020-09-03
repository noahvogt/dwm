# Noahs's build of dwm

This is suckless software, the source code is the documentation! Check out their [website](https://dwm.suckless.org).

## Please install `libxft-bgra`!

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.

If libxft-bgra won't work, you can try uninstalling all suckless software and after that installing the libxft pactch. If this also won't work you can try [libxft-bgra-git] (https://aur.archlinux.org/packages/libxft-bgra-git/) (also form the AUR) instead.
