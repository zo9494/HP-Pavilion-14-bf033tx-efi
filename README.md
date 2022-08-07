# HP Pavilion 14-bf033tx

| Part       | Info                                                 |
| ---------- | ---------------------------------------------------- |
| Model      | HP Pavilion 14-bf033tx                               |
| CPU        | Intel Core i5-7200U                                  |
| Mem        | 12GB DDR4 2400 MHz                                   |
| SSD        | 250GB + 500GB (SATA)                                 |
| IGPU       | Intel HD Graphics 620                                |
| DGPU       | Nvidia GeForce 940MX                                 |
| Sound Card | Realtek ALC295 (Layout ID = 13, 28 or 77)            |
| WIFI / BT  | Intel Corporation Dual Band Wireless-AC 3168NGW      |
| Ethernet   | RTL8100/8169 PCI Express Gigabit Ethernet Controller |
| CardReader | Realtek PCIE Card Reader                             |



# Notes
-Disable Secure boot. <br>
-Before installing use TOOLS/gensmbios for generatiing a serial key, mld and uuid of MacBookPro14,2/MacBookPro14,3 for your hackBook. <br>
-This EFI is strictly for MacOS monetery only !! <br>
-dGPU ( 940mx ) is disabled via boot parameter (-wegnoegpu) <br>
-You need to change the wifi kext according to your macOS version (this repo uses monetery)

## Not Working

1. Nvidia DGPU ( As you know, Optimus is not supported at the moment )
2. You will face Fairplay4.0 issues

## Working

1. Intel iGPU
2. Sound
3. USB
4. Ethernet
5. WiFi
6. Bluetooth
7. Battery
8. Touchpad
9. Sleep
10. CPU power management
11. Every func keys (Eg- Volume up/Down, Brightness up/Down)
12. Card reader
13. HDMI-output (audio and video)


## Credits

[HP Pavilion au624tx](https://github.com/kumarayush2104/OC-Hackintosh)