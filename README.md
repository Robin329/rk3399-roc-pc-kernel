# rk3399-roc-pc-kernel 

[![Build Status](https://github.com/Robin329/rk3399-roc-pc/actions/workflows/master.yml/badge.svg)](https://github.com/Robin329/rk3399-roc-pc/actions/workflows/master.yml)

Porting rk3399-roc-pc 4.4 kernel version to newest linux v5.17

## 1. Compile Steps

### Full compile
build.py build_kernel

### Compile dtbs
build.py dtbs

### Compile Image
build.py Image

### Compile Modules
build.py modules

### Compile clean
build.py clean


## 2. Compile QEMU virto

### Full compile
build.py build_virt
