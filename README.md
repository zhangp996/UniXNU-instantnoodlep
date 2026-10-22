# UniXNU-instantnoodlep

Device repository for the OnePlus 8 Pro (IN2020 / instantnoodlep, SM8250).

- UEFI platform: `in2020-uefi/port/uefi-sheng/Platforms/OnePlus/instantnoodlepPkg`
- Kernel: UniXNU baseline (BCM2837 arm64, 4 KiB pages) with `ArmDTPlatform`
- Initial defconfig disables sheng-only drivers (NativeUfs, NativeAES, Adreno, legacy display), which still need SM8250 bring-up.
