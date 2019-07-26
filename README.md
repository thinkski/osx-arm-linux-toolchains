## About

Compiling cross-compilation toolchains is a tedious, time-consuming process. This site provides a small number of ready-to-use cross-compilation toolchains for Mac OS X, targetting the Linux operating system on a small number of architectures, currently `arm` and `aarch64`.

Based on [gcc](gcc.gnu.org) and [binutils](https://www.gnu.org/software/binutils/), toolchains are provided currently in one variant, namely [glibc](https://www.gnu.org/software/libc/), with support for [uClibc-ng](https://uclibc-ng.org/) and [musl](http://www.musl-libc.org/) possible in the future if there is interest. The toolchains are built using the [crosstools-ng](https://crosstool-ng.github.io/) build system.

## Downloads

| Toolchain | GCC | GDB | Linux headers | glibc | binutils |
|--|--|--|--|--|--|
| [aarch64-unknown-linux-gnu](https://github.com/thinkski/toolchains/releases/download/8.3.0/aarch64-unknown-linux-gnu.tar.xz) | 8.3.0 | 8.2.1 | 4.20.8 | 2.29 | 2.32 |
| [arm-unknown-linux-gnueabi](https://github.com/thinkski/toolchains/releases/download/8.3.0/arm-unknown-linux-gnueabi.tar.xz) | 8.3.0 | 8.2.1 | 4.20.8 | 2.29 | 2.32 |

## Support or Contact

If you find a problem or would like to see support for a new architecture or component combination, please [file an issue](https://github.com/thinkski/toolchains/issues).
