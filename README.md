# MobiusOS
Mobius OS is a GNU/Linux distribution made from scratch. It uses ~~KDE Plasma~~ Sway (for now) as its DE.
# WARNING!
This GNU/Linux distro:
1. Is **very** experimental *for now*.
2. Doesn't actually use GNU ~~(unless I'm dumb and busybox is just GNU stuff anyway, afaik its not)~~ *yet*
3. Has X.org, Wayland, Sway and that's mostly it for graphical stuff. ~~I might have to build xfce4 manually since I cannot suffer building the modular (yet probably resource gobbler when building) KDE Plasma 6~~ 
# To do
1. Some package manager that just runs scripts to build target packages (maybe just configure the buildroot one)
2. A rootfs 
~~3. The initramfs (though not strictly neccessary if the filesystem is FAT, NTFS, BTRFS, ext2-4 then the kernel just mounts the rootfs by itself and runs SysV init OpenRC for now before systemd gets added instead) (you fool that isnt all it does so we will do an initramfs)~~ EDIT: sh nor is toybox init working so we ball with no initramfs
