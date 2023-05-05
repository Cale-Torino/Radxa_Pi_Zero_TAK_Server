# Radxa Pi Zero TAK Server

*Developed by C.A Torino, TECHRAD Radical Technology*
* Links to wiki.radxa.com
    * [Radaxa Wiki](https://wiki.radxa.com/Zero)
    * [Getting Started](https://wiki.radxa.com/Zero/getting_started)
    * [Download Images](https://wiki.radxa.com/Zero/downloads)
    * [Models](https://wiki.radxa.com/Zero/hardware/models)
    * [Hardware](https://wiki.radxa.com/Zero/hardware/zero)
    * [GPIO](https://wiki.radxa.com/Zero/hardware/gpio)

# Summary

The Radaxa Pi Zero SBC has the same form factor as the raspberry Pi Zero however the SBC has higher specs such as more CPU cores and more RAM.

There is very low power consumption the SBC can run on 5v 1A chargers with cables that can tolerate 1A.

The max power consumption of Radxa Zero without USB peripheral is 3.3W.

With it's low price point (at least here in South Africa) and powerful specs I'd say it's a suitable replacement/competitor to the Raspberry Pi 4 boards.

- For Radxa Zero model with 512MB or 1GB memory, it comes with AP6212 module.
- For Radxa Zero model with 2GB or 4GB memory, it comes with AP6256 module.

# Index
- Summary
- SBC Specs
- Project

# SBC Specs

Do note that there are specific boards of the Radaxa Pi Zero which have different specs.

Namely: 
- 512MB RAM & 0GB EMMC storeage
- 1GB RAM & 0GB EMMC storeage
- 2GB RAM & 8GB EMMC storeage
- 4GB RAM & 32GB EMMC storeage
- 4GB RAM & 64GB EMMC storeage
- 4GB RAM & 128GB EMMC storeage

I got the `4GB RAM & 32GB EMMC storeage` version

Specs:
- Memory: 4GB LPDDR4, 64bit dual channel 3200Mb/s
- EMMC Storage: 32GB
- CPU: Amlogic S905Y2 64bit Quad core processor, Cortex-A53, 1.8GHz, 12nm
- GPU: Mali G31 MP2 GPU, supports OpenGL ES 1.1 /2.0 /3.1 /3.2, Vulkan 1.1, Open CL 1.1 1.2, 2.0 Full Profile
- Storage: eMMC 5.1 soldered high performance eMMC 5.1 with capacities of 8/16/32/64/128GB (depending on model)
- MicroSD card: microSD slot supports up to 128GB
- Video Decoding: HD codec H265/VP9 decode 4Kx2K@60
- Display Micro HDMI: HDMI 2.1, 4K@60 HDR
- Wifi/BT Antenna: Wifi/BT On Board
- WIFI4/BLE4 for 512MB and 1GB models
- WIFI5/BLE5 for 2GB and 4GB models
- Crypto Engine
- One button
- Size: 66 x 30 mm
- Power Requirement : 5V 1A USB C

# Project

Leverange the low power but powerful RAM and CPU specs of the Radxa Pi Zero in order to run TAK server for small to medium traffic.

This project needs to always remain affardable (like the old Raspberry Pi boards).

Try get the most specs for the lowest price point where the server will run reliably.

4GB memory should be enough but will keep an eye out for 8GB versions at an affordable price.


