mirrorcheck for Arch Linux
==========================

Major updates via pacman tend to break the system if the mirror that
one's using is not fully synced to the main server. Most of the pain
would go away if there was a way to check the sync status of the
different servers.

What does mirrorcheck do?
=========================

The aim of this code is to compare the package list on the main server
to the one on the mirror. If there are discrepancies between the versions,
the user is notified, and can decide whether it is really the right time
to perform a 'pacman -Syu'.

Other useful things
===================

 * Check your mirror's last update time: [mirrorstatus]
 * Check the latency of the available mirrors: [archalice] (might be merged into this project later)

[mirrorstatus] https://www.archlinux.de/?page=MirrorStatus "ArchLinuxDE MirrorStatus"
[archalice] http://github.com/imrehg/archalice

