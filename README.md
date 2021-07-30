# Build request for ubuntu 20.04
* apt install: flex libssl-dev gcc g++ bison u-boot-tools gcc-arm-linux-gnueabi gcc-arm-linux-gnueabihf gcc-aarch64-linux-gnu device-tree-compiler
* error while loading shared libraries:libmpfr.so.4: cannot open shared object file: No such file or directory.
  sudo ln -s /usr/lib/x86_64-linux-gnu/libmpfr.so.6 /usr/lib/x86_64-linux-gnu/libmpfr.so.4
# BPI-R64-bsp-5.4
Supports Banana Pi BPI-R64 (MT7622) (Kernel 5.4)
