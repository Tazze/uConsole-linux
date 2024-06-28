Linux kernel with patching for Clockwork Pi uConsole
====================================================

I am forking https://github.com/raspberrypi/linux to easily get up to date versions of the kernel with the patch from the uConsole repo (https://github.com/clockworkpi/uConsole/blob/master/Code/patch/cm4/20230630/0001-patch-cm4.patch), which can't be applied on a current version of the raspberry kernel due to it depending on a commit from ***APRIL 29, 2021***
I have applied most of the modifications made by the patch (except the ones for arch/arm64/configs/bcm2711_defconfig because honestly it looks like a load of garbage and I'm trying to see if I can get away with not touching it), however, since they seem to be quick and dirty hacky workarounds with absolutely 0 polish I won't even ***THINK*** about trying to upstream this
