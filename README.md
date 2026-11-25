![Device](https://img.shields.io/badge/Device-POCO_M3_Pro_5G-blue)
![Codename](https://img.shields.io/badge/Codename-camellian-green)
![Linux
Version](https://img.shields.io/badge/Linux-4.14.186--BlackFalcon--%F0%9F%87%B5%F0%9F%87%B8-informational)

## Device Information

-   **Device:** POCO M3 Pro 5G
-   **Codename:** camellian
-   **Platform:** MediaTek MT6833
-   **Architecture:** ARM64
-   **Linux Version:** 4.14.186-BlackFalcon-🇵🇸


``` text
   _____    _ _                  
  |  ___|_ _| | ___ ___  _ __  
  | |_ / _` | |/ __/ _ \| '_ \ 
  |  _| (_| | | (_| (_) | | | |
  |_|  \__,_|_|\___\___/|_| |_|

       LINUX FALCON KERNEL
          Fly Beyond Limits.
```


## About

Linux Falcon Kernel is a custom Linux kernel developed for POCO M3 Pro
5G (camellian).

## Build Requirements

**Recommended OS:** - Ubuntu 22.04 LTS - Ubuntu 24.04 LTS

Required dependencies and toolchains are automatically downloaded and
installed by the build script.

## Clone Source

``` bash
git clone --depth=1 https://github.com/sigmahfuj/camellia_falcon_oss_kernel.git
cd camellia_falcon_oss_kernel
```

## Build

``` bash
chmod +x build-falcon.sh
bash build-falcon.sh
```

## Build Output

``` text
out/arch/arm64/boot/Image.gz-dtb
```

## Disclaimer

-   Intended for POCO M3 Pro 5G (camellian).
-   Always back up your boot image before flashing.
-   Flash at your own risk.
-   The developer is not responsible for any damage or data loss.

## Sources & Attributions

-   [MiCode](https://github.com/MiCode/Xiaomi_Kernel_OpenSource/tree/camellian-t-oss)
    Initial base kernel source
-   [Error](https://github.com/error)
    Missing driver source

## License

Follows the applicable licenses of the upstream kernel source and
individual components.
