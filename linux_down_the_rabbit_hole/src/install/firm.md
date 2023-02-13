# System Firmwares: BIOS vs UEFI

## What is Firmware?
*Firmware* is the lowest level software that provides control over hardware components. The firmware my provide basic functions and abstractions to allow an operating system to interact with and control hardware components. For modern computers, the component known as the *motherboard* has firmware that facilitates control of the entire system and its components. Firmware is essentially an intermediary between hardware and software. The firmware is often stored in non-volatile, read-only or flash memory. Firmware can sometimes be updated on devices, like motherboards, to allow for new and upgraded features or expanded hardware support.

# Types of PC Firmwares
On modern day PCs there are two types of firmwares: the legacy BIOS or *Basic Input/Output System* and the more modern and used by default UEFI or *Unified Extensible Firmware Interface*. It is highly recommended you utilize the UEFI for this book unless you are on older hardware that does not support the UEFI. If your hardware supports both, ensure it is in UEFI mode. The UEFI and BIOS are contrasted below to illustrate the UEFI's advantages over its predecessor.

|Type   |Age   |Boot Speeds   |# of Partitions   |Drive Capacity   |Secure Boot   |UI   | Partition Table  |
|---|---|---|---|---|---|---|---|
|UEFI   |2002   |Faster Boots   | Unlimited  |9.4 Zettabytes  |Yes   |User Friendly & Verbose   | GPT  |
|BIOS   |1975   |Slower Boots   |  4 partitions per drive  |2.2 Terabytes   |No   |Dated & Less Functional |MBR   |

As you can gleam from the about table, the UEFI and BIOS only support a single, respective *partition table*. You will come to understand partition tables in the following chapter: [Partition Tables](./part.md).
