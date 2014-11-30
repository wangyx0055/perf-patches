### Perf-Patches

Port for the 3.14 kernel of some performance patches for the ar71xx architecture found here:

https://www.codeaurora.org/patches/external/qca/qsdk-base-1.0.112.patch

## Usage

Copy them in the target/linux/ar71xx/patches-3.14 directory of OpenWRT.

## Disclaimer

They are barely tested: the kernel at least doesn't panic.

The SRAM option doesn't work for my router (Netgear WNDR3800), maybe the CPU has no SRAM.

No performance test done so far, YMMV.
