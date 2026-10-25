# Supported SSDs

Below is a list of NVMe SSDs that have been tested by Uptime Lab and community members.

### Benchmarks

[pibenchmarks.com](https://pibenchmarks.com) is a popular site to upload micro SD, eMMC, SSD, and other storage benchmarks for Raspberry Pi and Pi clones. You can find benchmarks for some of the NVMe SSDs listed below.

## Crucial

| Product                       | Model        | Controller         | Capacity | Tester                                          |
| :---------------------------- | :----------- | :----------------- | :------- |:----------------------------------------------- |
| Crucial P2                    | CT500P2SSD8  |                    | 500GB    | [xvzf](https://github.com/xvzf)                 |
| Crucial P3                    | CT4000P3SSD8 |                    | 4TB      | [Uptime](https://github.com/uptime-lab)         |
| Crucial P3                    | CT2000P3SSD8 |                    | 2TB      | [khrystoph](https://github.com/khrystoph)       |
| Crucial P3                    | CT1000P3SSD8 |                    | 1TB      | [dstewart1673](https://github.com/dstewart1673) |
| Crucial P3                    | CT500P3SSD8  | Phison PS5021-E21T | 500GB    | [pxpunx](https://github.com/pxpunx)             |
| Crucial P5 Plus <sup>1</sup>  | CT500P5PSSD8 |                    | 500GB    | [lwbt](https://github.com/lwbt)                 |

<sup>1</sup> _This SSD boots fine on Ubuntu, but required several reboots when used in a Talos Linux K8s cluster._

## Intel

| Product                       | Model          | Controller                         | Capacity     | Tester                              |
| :---------------------------- | :------------- | :--------------------------------- | :----------- | :---------------------------------- |
| Intel 670p                    | SSDPEKNU512GZ  | Silicon Motion SM2265G             | 512GB        | [pxpunx](https://github.com/pxpunx) |
| Intel Optane H10              | HBRPEKNX0101A  | Silicon Motion SM2263, Intel SLL3D | 16GB + 256GB | [pxpunx](https://github.com/pxpunx) |
| Intel Optane M10 <sup>1</sup> | MEMPEK1J032GAD | Intel, Unknown                     | 32GB         | [pxpunx](https://github.com/pxpunx) |

<sup>1</sup> _This SSD will not function as a boot disk._

## Kingston

| Product            | Model              | Controller          | Capacity | Tester                              |
| :----------------- | :----------------- | :------------------ | :--------| :---------------------------------- |
| Kingston NV2       | SNV2S/250G         | Varies              | 250GB    | [pxpunx](https://github.com/pxpunx) |
| Kingston NV2       | SNV2S/1000G        |                     | 1TB      | [xvzf](https://github.com/xvzf)     |
| Kingston NV3       | SNV3S/1000G        |                     | 1TB      | [ruflin](https://github.com/ruflin) |
| Kingston SNS8154P3 | RBUSNS8154P3256GJ1 | Phison PS5008-E8-10 | 256GB    | [pxpunx](https://github.com/pxpunx) |


## KIOXIA

| Product                       | Model              | Controller    | Capacity | Tester                                |
| :---------------------------- | :----------------- | :------------ | :------- | :------------------------------------ |
| KIOXIA-EXCERIA SSD            | LRC10Z500GG8       |               | 500GB    | [xvzf](https://github.com/xvzf)       |
| KIOXIA BG4                    | KBG40ZNS128G       | Custom Kioxia | 128GB    | [pxpunx](https://github.com/pxpunx)   |
| KIOXIA BG5 <sup>1</sup>       | KBG50ZNV512G       |               | 512GB    | [xvzf](https://github.com/xvzf)       |
| KIOXIA EXCERIA G2             | LRC20Z002TG8       |               | 2TB      | [mookie-](https://github.com/mookie-) |

<sup>1</sup> _Might cause slightly increased CM4 temperature, but stability & performance is not impacted (reported by [xvzf](https://github.com/xvzf)) ._

## Micron

| Product                       | Model              | Controller           | Capacity | Tester                              |
| :---------------------------- | :----------------- | :------------------- | :------- | :---------------------------------- |
| Micron 2450                   | MTFDKBA256TFK      | Phison PS5019-E19-35 | 256GB    | [pxpunx](https://github.com/pxpunx) |
| Micron 3400                   | MTFDKBA512TFH      | MICRON DM02A1        | 512GB    | [pxpunx](https://github.com/pxpunx) |

## Patriot

| Product                       | Model              | Controller | Capacity | Tester                                    |
| :---------------------------- | :----------------- | :--------- | :------- | :---------------------------------------  |
| Patriot P310                  | P310P240GM28       | Unknown    | 240GB    | [pxpunx](https://github.com/pxpunx)       |
| Patriot P310                  | P310P192TM28       |            | 1920GB   | [adriano](https://github.com/Adriano8899) |
| Patriot P300                  | P300P2TBM28        |            | 2TB      | [adriano](https://github.com/Adriano8899) |

## PNY

| Product                       | Model              | Controller           | Capacity | Tester                              |
| :---------------------------- | :----------------- | :------------------- | :------- | :---------------------------------- |
| PNY CS1030                    | M280CS1030-250-RB  | Phison PS5013-E13-31 | 250GB    | [pxpunx](https://github.com/pxpunx) |

## Raspberry Pi

| Product                       | Model                  | Controller                 | Capacity | Tested CM | Tester                                          |
| :---------------------------- | :----------------------| :------------------------- | :------- | :-------- | :---------------------------------------------- |
| Raspberry Pi SSD (256GB)      | MZ9LQ256HBJD-00BVL.    | Samsung                    | 256GB    | CM4 & CM5 | [remonlam](https://github.com/remonlam)         |
| Raspberry Pi SSD (512GB)      | BIWIN CE430T5D100-512G | MaxioTech MAP1202 (Cougar) | 512GB    | CM5       | [remonlam](https://github.com/remonlam)         |


## Samsung

| Product                       | Model              | Controller      | Capacity | Tester                                          |
| :---------------------------- | :----------------- | :-------------- | :------- | :---------------------------------------------- |
| Samsung 970 EVO               | MZ-V7E500          | Samsung Phoenix | 500GB    | [pxpunx](https://github.com/pxpunx)             |
| Samsung 970 EVO Plus          | MZ-V7S1T0B         |                 | 2TB      | [Uptime](https://github.com/uptime-lab)         |
| Samsung 960 PRO               | MZ-V6P512BW        |                 | 500GB    | [Uptime](https://github.com/uptime-lab)         |
| Samsung 970 PRO               | MZ-V7P512BW        |                 | 500GB    | [Uptime](https://github.com/uptime-lab)         |
| Samsung 980 PRO               | MZ-V8P1T0B         |                 | 1TB      | [Uptime](https://github.com/uptime-lab)         |
| Samsung 990 PRO               | MZ-V9P1T0B/AM      |                 | 1TB      | [dstewart1673](https://github.com/dstewart1673) |
| Samsung PM991a                | MZ9LQ256HBJD       | Custom Samsung  | 256GB    | [pxpunx](https://github.com/pxpunx)             |

## SK hynix

| Product                       | Model              | Controller              | Capacity | Tester                                  |
| :---------------------------- | :----------------- | :---------------------- | :------- | :-------------------------------------- |
| SK hynix BC711                | HFM256GD3JX016N    | Unknown                 | 256GB    | [pxpunx](https://github.com/pxpunx)     |
| SK hynix PC611                | HFS001TD9TNI       |                         | 1TB      | [Uptime](https://github.com/uptime-lab) |
| Solidigm P41 Plus             | SSDPFKNU512GZ      | Silicon Motion SM2269XT | 512GB    | [pxpunx](https://github.com/pxpunx)     |

## Synology

| Product                       | Model              | Controller | Capacity | Tester                                  |
| :---------------------------- | :----------------- | :--------- | :------- | :-------------------------------------- |
| Synology SNV3510              | SNV3510-400G       |            | 400GB    | [Uptime](https://github.com/uptime-lab) |

## TeamGroup

| Product                       | Model              | Controller         | Capacity | Tester                              |
| :---------------------------- | :----------------- | :----------------  | :------- | :---------------------------------- |
| TEAMGROUP MP33                | TM8FP6256G0C101    | Phison PS5013-E13T | 256GB    | [pxpunx](https://github.com/pxpunx) |
| TEAMGROUP MP33 PRO            | TM8FPD001T0C101    |                    | 1TB      | [dlohin](https://github.com/dlohin) |

## Toshiba

| Product                       | Model              | Controller     | Capacity     | Tester                              |
| :---------------------------- | :----------------- | :------------- | :----------- | :---------------------------------- |
| Toshiba BG3                   | KBG30ZMS128G       | Custom Toshiba | 256GB        | [pxpunx](https://github.com/pxpunx) |

## Transcend

| Product                       | Model              | Controller              | Capacity | Tester                              |
| :---------------------------- | :----------------- | :---------------------- | :------- | :---------------------------------- |
| Transcend 110S                | TS256GMTE110S      | Silicon Motion SM2263XT | 256GB    | [pxpunx](https://github.com/pxpunx) |

## Verbatim

| Product                       | Model              | Controller | Capacity | Tester                                  |
| :---------------------------- | :----------------- | :--------- | :------- | :-------------------------------------- |
| Verbatim Vi3000               | 49374              |            | 512GB    | [LauLaman](https://github.com/LauLaman) |

## Western Digital (WD)

| Product                       | Model              | Controller     | Capacity | Tester                                   |
| :---------------------------- | :----------------- | :------------- | :------- | :--------------------------------------- |
| WD Black SN770                | WDS250G3X0E        | Custom SanDisk | 250GB    | [pxpunx](https://github.com/pxpunx)      |
| WD Black SN770                | WDS500G3X0E        |                | 500GB    | [Uptime](https://github.com/uptime-lab/) |
| WD Blue SN550                 | WDS100T2B0C        |                | 1TB      | [lwbt](https://github.com/lwbt)          |
| WD Blue SN570                 | WDS250G3B0C        | Custom SanDisk | 250GB    | [pxpunx](https://github.com/pxpunx)      |
| WD Blue SN580                 | WDS100T3B0E        |                | 1TB      | [lwbt](https://github.com/lwbt)          |
| WD Green SN350                | WDS240G2G0C        | Custom SanDisk | 240GB    | [pxpunx](https://github.com/pxpunx)      |
| WD Green SN3000               | WDS500G4G0E        | Custom SanDisk | 500GB    | [khrystoph](https://github.com/khrystoph)|
| WD Red SN700                  | WDS500G1R0C        | Custom SanDisk | 500GB    | [pxpunx](https://github.com/pxpunx)      |
| WD SN520                      | SDAPNUW-256G-1006  | Custom SanDisk | 256GB    | [pxpunx](https://github.com/pxpunx)      |
| WD SN530                      | SDBPTPZ-256G-1012  |                | 256GB    | [Tom](https://github.com/nyx0)           |
