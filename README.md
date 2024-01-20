## Hackintosh_Monterey_OC_SF314-54G

## Specs

- Processor   : Intel Core i5-8250U
- RAM         : 12 GB DDR4 @ 2400 MHz (4 + 8 GB)
- VGA         : Intel UHD 620
- Audio       : Realtek ALC256
- Ports       : 1xUSB 3.1 Gen-1 Type-C, 2xUSB 3.0, 1xUSB 2.0, 1xHDMI (full-size), 1xAudio jack
- SSD         : V-Gen NVme 120GB
- Wifi        : Intel AC-7265
- Bluetooth   : ORICO BT USB
- Screen      : 14-inch 1920 x 1080 IPS

## OS
- This is for Monterey, I've tested this in 12.7.2. If you want to use other version you must change `AirportItlwm.kext` to match your version and update `config.plist`.

- Use GenSMBIOS to Generate SMBIOS and insert your SMBIOS, this EFI not include SMBIOS, so Generate SMBIOS yourself.

![img](https://github.com/maemo3/Hackintosh_Monterey_OC_SF314-54G/blob/main/img.png)

## Usefull Tools

- GenSMBIOS     : https://github.com/corpnewt/GenSMBIOS
- ProperTree    : https://github.com/corpnewt/ProperTree
- Opencore      : https://github.com/acidanthera/OpenCorePkg

## Working

- Graphics  
    - Intel UHD Graphics 620 1536 МB

- Audio
    - Speakers and headphones 

- Keyboard

- USB
    - Mapped

- Webcam

- WiFi

- Bluetooth
    - Use BT USB Dongle

- HDMI

- Line In Mic with Headset
    - Use ComboJack

- Built-in SD card reader


## What is NOT working

- Internal Mic

- Touchpad
    - Enable with Kext

- Internal Bluetooth
    - Enable with Kext

