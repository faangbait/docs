# Development PC Documentation

## Hardware Components

| Component         | Description                                              | MPN        |
|-------------------|----------------------------------------------------------|------------|
| Motherboard       | Gigabyte Z690 AORUS MASTER EATX LGA1700 Motherboard      | [Z690AORUSMASTER](./Z690AORUSMASTER.md)
| CPU               | Intel Core i7-12700K 3.6 GHz 12-Core Processor           | [BX8071512700K](./BX8071512700K.md)
| CPU Heatsink      | Noctua NH-D15S chromax.Black                             | [NH-D15S](./NH-D15S.md)
| CPU Fan           | NF-A15 140mm PWM Fan                                     | [NF-A15](./NF-A15.md)
| Memory            | Corsair Vengeance 16GB DDR5-4800 CL40                    | [CMK32GX5M2A4800C40](./CMK32GX5M2A4800C40.md)
| Memory            | Corsair Vengeance 16GB DDR5-4800 CL40                    | [CMK32GX5M2A4800C40](./CMK32GX5M2A4800C40.md)
| Memory            | Corsair Vengeance 16GB DDR5-4800 CL40                    | [CMK32GX5M2A4800C40](./CMK32GX5M2A4800C40.md)
| Memory            | Corsair Vengeance 16GB DDR5-4800 CL40                    | [CMK32GX5M2A4800C40](./CMK32GX5M2A4800C40.md)
| Power Supply      | SeaSonic FOCUS GX 850W 80+ Gold                          | [SSR-850FX](./SSR-850FX.md)
| Graphics Card     | Sapphire Radeon RX Vega 64 8GB HBM2  	                   | [21275-02-20G](./21275-02-20G.md)
| SSD               | Samsung 970 Evo Plus 1TB M.2-2280 NVME                   | [MZ-V7S1T0B/AM](./MZ-V7S1T0B-AM.md)
| SSD               | Samsung 970 Evo Plus 1TB M.2-2280 NVME                   | [MZ-V7S1T0B/AM](./MZ-V7S1T0B-AM.md)
| SSD               | Samsung 970 Evo 500GB M.2-2280 NVME                      | [MZ-V7E500BW](./MZ-V7E500BW.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | Western Digital 4TB WD Red Plus NAS 5400 RPM 3.5"        | [WD40EFZX](./WD40EFZX.md)
| HDD               | WP Arsenal 10TB SATA 7200RPM                             | [OOS10000G](./OOS10000G.md)
| Case              | be quiet! Silent Base 802 ATX Mid Tower                  | [BGW39](./BGW39.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm 3-pin               | [BL047](./BL047.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm 3-pin               | [BL047](./BL047.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm 3-pin               | [BL047](./BL047.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm PWM                 | [BL040](./BL040.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm PWM                 | [BL040](./BL040.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm PWM                 | [BL040](./BL040.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm PWM                 | [BL040](./BL040.md)
| Case Fan          | be quiet! Pure Wings 2 61.2CFM 140mm PWM                 | [BL040](./BL040.md)
| HDD Tray          | be quiet! HDD Cage                                       | [BGA05](./BGA05.md)
| HDD Tray          | be quiet! HDD Cage                                       | [BGA05](./BGA05.md)
| HDD Tray          | be quiet! HDD Cage                                       | [BGA05](./BGA05.md)
| HDD Tray          | be quiet! HDD Cage                                       | [BGA05](./BGA05.md)
| UPS               | APC BX1500M                                              | [BX1500M](./BX1500M.md)
| Primary Monitor   | DELL 32"                                                 | S3221QS
| Secondary Monitor | DELL 23"                                                 | U2311H
| Secondary Monitor | DELL 23"                                                 | U2311H
| Dashboard/Events  | LG 48"                                                   | OLED48C1PUB

## Filesystems
| Mountpoint        | Type / Usable Space                                      | Drives                 |
|-------------------|----------------------------------------------------------|------------------------|
| /                 | RAID1 / 1TB                                              | 2x [970 Evo Plus](./MZ-V7S1T0B-AM.md) 
| /var/cache        | 500GB                                                    | 1x [970 Evo](./MZ-V7E500BW.md)
| /build            | RAMFS                                                    | N/A
| /gob              | Stratis                                                  | 6x [WD Red 4TB](./WD40EFZX.md)

## Software
- See antennae/dotfiles repo

## Incident Reports
- 2022-Apr: Strange RAID1 behavior. Drives disappearing from BIOS after being added to mirrored array. Investigate why this board is nuking drives.
