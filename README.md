### Thinkpad E490

##### Works
-  Nvme
- Realtek Gbe NIC
- Backlight level
- Internal Speakers
- Internal Mic
- Battery Level Status
- Type A USB Ports
- HDMI Video and Audio Output
- Built In MicroSD Reader

##### Doesnt Work
- Intel Wireless-AC 9260 (WiFi and Bluetooth)

##### Havent checked
- SATA
- Type C USB Video Output
- Headphone Jack
- Hibernation
- Webcam, disabled at BIOS

### Aditional Info
This EFI folder works with the Thinkpad E490 that comes with the i5-8265U (Intel UHD 620 iGPU), 4 GB RAM, 1 TB SATA Drive, Realtek R8111GUS Gigabit Ethernet, Intel Wireless-AC 9260 and no AMD eGPU. You can check the full Thinkpad E490 Platform Specification [HERE](https://psref.lenovo.com/syspool/Sys/PDF/ThinkPad/ThinkPad%20E490/ThinkPad_E490_Platform_Specifications.pdf)

Despite coming with a SATA drive, the very first thing I did was remove it and put a Nvme drive instead and put another 4GB stick on the 2nd RAM slot. If you need to open the laptop to make those changes, [check this video](https://www.youtube.com/watch?v=8LxfrYaKTZg), having a Guitar Pick is highly recommended.

##### Disclaimer
This was my first Hackintosh, and made lots of copy/paste form multiple sources, so a few things on the config.plist file may be wrong, use under your own risk.
