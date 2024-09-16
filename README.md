# DISCONTINUATION OF PROJECT #  
This project will no longer be maintained by Intel.  
Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project.  
Intel no longer accepts patches to this project.  
 If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the open source software community, please create your own fork of this project.  
  
# UEFI EDK2 branches for fuzzing with kAFL

WARNING - this project contains experimental and unsupported software for purpose of research. Do not use for production.

Branches Overview:

* `master` tracks upstream edk2 master at https://github.com/tianocore/edk2
* `kafl/*` contain feature branches of edk2 for kAFL
* `TDVF` tracks upstream development at https://github.com/tianocore/edk2-staging/tree/TDVF
* `TDVF_SDV` contains a modified TDVF for booting in SDV emulation
* `TDVF_fuzz_hello` adds a basic kAFL harness on top of TDVF_SDV branch to fuzz TDX HobList

See also:
* [kAFL Project](https://github.com/IntelLabs/kAFL)
* [Fuzzing UEFI with kAFL](https://github.com/IntelLabs/kafl.targets/tree/master/uefi_ovmf_64)

<!-- reviewed, 9/11/2023 michaelbeale-il -->
