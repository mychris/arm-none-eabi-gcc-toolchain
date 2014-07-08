arm-none-eabi gcc toolchain
===========================

A small script to download and build binutils and GCC toolchain for
my Raspberry Pi (model B, rev. 2).

Other toolchains
----------------

Just a short list of other tool chains:

* [Arch Linux packages](https://www.archlinux.org/packages/?q=arm-none-eabi)
* [eLinux wiki](http://elinux.org/Toolchains)
* [gcc-arm-embedded](https://launchpad.net/gcc-arm-embedded)

GCC flags
---------

The eLinux wiki suggests the following GCC flags:

    -Ofast -mfpu=vfp -mfloat-abi=hard -march=armv6zk -mtune=arm1176jzf-s

See [eLinux wiki](http://elinux.org/RPi_Software#ARM)

Start coding bare metal
-----------------------

* [Raspberry Pi forums](http://www.raspberrypi.org/forums/viewforum.php?f=72)
* [osdev bare-metal RPI](http://wiki.osdev.org/ARM_RaspberryPi_Tutorial_C)
* [Cambridge Universitiy Baking Pi](http://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/)
* [valvers (Baking Pi in c?)](http://www.valvers.com/embedded-linux/raspberry-pi/step01-bare-metal-programming-in-cpt1)
* [dwelch67 examples](https://github.com/dwelch67/raspberrypi)

