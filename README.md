# Raspberry Pi system image

This repository contains default BuildRoot
configuration for Raspberry Pi in Hexapod.

# How to build

Copy the file `hexapod_defconfig` to `configs/`
in BuildRoot project's root directory and run:
```
make hexapod_defconfig
make -j(number of threads)
```
