# khadas openwrt sdk [![Build Status](https://github.com/khadas/khadas-openwrt-sdk/workflows/Build/badge.svg)](https://github.com/khadas/khadas-openwrt-sdk/actions)

openwrt packages builder

## USAGE

    git clone https://github.com/khadas/khadas-openwrt-sdk
    cd khadas-openwrt-sdk
    ./scripts/build

## BUILD ARGS

    ./scripts/build [openwrt make args] [args]

## OpenWRT build packages


    make package/ncurses/compile
    make package/ncurses/install

+ https://openwrt.org/docs/guide-developer/toolchain/single.package

## REQUIRED

+ curl
+ rsync

## related projects

+ https://github.com/khadas/krescue
+ https://github.com/khadas/khadas-rescue-sdk
+ https://github.com/khadas/khadas-rescue-rootfs
+ https://github.com/khadas/khadas-openwrt-feed-extra
+ https://github.com/khadas/khadas-openwrt-sdk
+ https://github.com/khadas/khadas-linux-kernel
+ https://github.com/khadas/khadas-uboot

\## hyphop ##
