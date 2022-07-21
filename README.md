uboot-qp64
==========

This is the Rockchip downstream ("BSP") version of u-boot for the RK3588,
with patches on top as I see fit for the QuartzPro64 dev board.

For the original u-boot README, see the "README" file.

This repository is provided "as-is", I may delete it at any time or abandon it,
no guarantees about its quality, functionality or fitness-for-purpose are
provided.

## Building

Make sure you have a cross compiler in your `$PATH`, adjust the make.sh as
necessary if it's not prefixed `aarch64-linux-gnu-`

```
make mrproper
./make.sh rk3588
```

## Next Steps

Flash your `rk3588_spl_loader_v*.bin` and `uboot.img` as
[described on the wiki](https://wiki.pine64.org/wiki/QuartzPro64_Development#U-Boot_+_Kernel_On_SD,_RootFS_On_eMMC).
