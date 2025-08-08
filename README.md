<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://www.ti.com/content/dam/ticom/images/identities/ti-brand/ti-logo-hz-1c-white.svg" width="300">
  <img alt="Texas Instruments Logo" src="https://www.ti.com/content/dam/ticom/images/identities/ti-brand/ti-hz-2c-pos-rgb.svg" width="300">
</picture>

# cc33xx-linux-mpu-ports

The CC33XX LINUX MPU ports is a project meant to provide customers with a single place to find patches required to port the CC33XX-LINUX-MPU SDK to LTS kernels and other HW platforms(NXP, STMicro, AM62x, etc.) 

[Summary](#summary) | [Features](#features) | [Background](#background) | [Related Repos](#related-repos) | [Setup Instructions](#setup-instructions) | [Build Instructions](#build-instructions) | [Supported Devices](#supported-devices) | [Licensing](#licensing) | [Contributions](#contributions) | [Developer Resources](developer-resources)
</div>

## Summary

The kernel patches for each kernel version may not be the latest.
Therefore, the following lists the cc33xx SDK for the supported kernel
version:

| Kernel | CC33xx SDK |
| ------------- | ------------- |
| 4.4.y | [1.0.0.6](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.6) |
| 4.14.y | [1.0.0.6](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.6) |
| 5.4.y | [1.0.0.6](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.6) |
| 5.10.y | [1.0.0.9](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.9) |
| 5.15.y | [1.0.0.8](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.8) |
| 6.6.y | [1.0.2.10](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.2.10) |
| 6.12.y | [1.0.2.10](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.2.10) |
| ti-linux-6.6.y | [1.0.0.8](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.0.8) |
| ti-linux-6.12.y | [1.0.2.10](https://www.ti.com/tool/download/CC33XX-LINUX-MPU/1.0.2.10) |

## Features

- Linux Kernel 6.1 Patches for Wi-Fi driver on versions:
  - 4.4.y
  - 4.14.y
  - 5.4.y
  - 5.10.y
  - 6.6.y
  - 6.12.y
  - ti-linux-6.6.y
  - ti-linux-6.12.y

## Supported Devices

- [BP-CC3351](https://www.ti.com/tool/BP-CC3351)
- [BP-CC33-BBB-ADAPT](https://www.ti.com/tool/BP-CC33-BBB-ADAPT)
- [SK-AM62B-P1](https://www.ti.com/tool/SK-AM62B-P1)
- [M2-CC3301](https://www.ti.com/tool/M2-CC3301)
- [8MPLUSLPD4-EVK](https://www.nxp.com/design/development-boards/i-mx-evaluation-and-development-boards/evaluation-kit-for-the-i-mx-8m-plus-applications-processor:8MPLUSLPD4-EVK)
- [M2-CC3301](https://www.ti.com/tool/M2-CC3301)

## Setup Instructions

[Setup Instructions](https://dev.ti.com/tirex/explore/content/CC33XX_LINUX_MPU_1_00_00_05__all/docs/linux/html/linux/getting-started/getting-started-linux.html#)


## Build Instructions

[Build Instructions](https://dev.ti.com/tirex/explore/content/CC33XX_LINUX_MPU_1_00_00_05__all/docs/linux/html/linux/migration-guide.html#)


### Related Repos

  - [TI-linux-kernel Repo](https://git.ti.com/cgit/ti-linux-kernel/ti-linux-kernel/)
  - [Linux-IMX Repo](https://github.com/nxp-imx/linux-imx.git)


## Licensing

[LICENSE.md](./manifest.html)


## Contributions

This repository is not currently accepting community contributions.

---
## Developer Resources
[TI E2E™ design support forums](https://e2e.ti.com) | [Learn about software development at TI](https://www.ti.com/design-development/software-development.html) | [Training Academies](https://www.ti.com/design-development/ti-developer-zone.html#ti-developer-zone-tab-1) | [TI Developer Zone](https://dev.ti.com/)
