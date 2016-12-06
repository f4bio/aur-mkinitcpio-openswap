mkinitcpio-openswap (hook)
==========================

* original project: https://aur.archlinux.org/packages/mkinitcpio-openswap

### changes
* renamed `miscellaneous` to the more descriptive `cryptsetup_options`
* added `keyfile_device_mount_options` to allow keyfiles lying on subvolumes (e.g. btrfs)
