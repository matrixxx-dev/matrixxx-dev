# matrixxx (a D.I.Y linux live system)
- a shell script collection

### The parts of the live system
  - boot-device content
    - contained in
      [github: matrixxx-boot-device-content][matrixxx-boot-device-content]
    - the base of a bootable flash device
  - the initramfs file
    - generated with [github: matrixxx-initrd-build][matrixxx-initrd-build]
  - the kernel and the corresponding kernel layer image as well as the firmware
    - generated with [github: matrixxx-kernel-build][matrixxx-kernel-build]
  - the OS
    - generated with [github: matrixxx-os-build][matrixxx-os-build]
  - the remaster base
    - generated with [github: matrixxx-remaster][matrixxx-remaster]

### Build a boot device (a basic system)
- Using the contents of the boot device and the files from the repository
  releases, it is possible to equip a USB stick (with a capacity of at least
  32 GB – so you have enough storage space to experiment) with the
  `matrixxx live system`, which can then be used to develop your own custom
  compilations (see [matrixxx boot-device HowTo])

[matrixxx-boot-device-content]:
https://github.com/matrixxx-dev/matrixxx-boot-device-content
[matrixxx-initrd-build]:https://github.com/matrixxx-dev/matrixxx-initrd-build
[matrixxx-kernel-build]: https://github.com/matrixxx-dev/matrixxx-kernel-build
[matrixxx-os-build]: https://github.com/matrixxx-dev/matrixxx-os-build
[matrixxx-remaster]: https://github.com/matrixxx-dev/matrixxx-remaster
[matrixxx boot-device HowTo]:
https://github.com/matrixxx-dev/matrixxx-boot-device-content/blob/main/readme-HowTo.md
