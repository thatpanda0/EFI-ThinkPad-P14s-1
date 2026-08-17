# EFI-ThinkPad-P14s-1 (Alpha)

Booting macOS Sonoma on the ThinkPad P14s Gen 1, 20S5-XXXXX device model.  
Do not seriously use this, it barely works at all yet. 
### Device information

#### Required
If you don't have the same devices, DON'T USE THIS!!! Your USB drive will not boot. 

* i7-10610U @ 1.80 GHz (comes with Intel UHD Graphics 620)
* Intel Wi-Fi 6 AX201 M.2 (soldered?)
* No WWAN card
* nVidia Quadro P520 (Laptop / 2GB VRAM) 
* Original 1920x1080 display

#### Optional / personal
* 32GB DDR4 RAM (doesn't matter, mine is 16GB 2400MHz (expansion) + 16GB 3200MHz (soldered))
* 1 TB NVME M.2 2280 SSD Gen 3 (Mine is OEM from Samsung)


### Working (tested)

* Booting into macOS Recovery (Sonoma)
* Battery percentage
* OpenCore Boot Picker GUI
* Keyboard and trackpad (trackpad is a bit slow)

### Untested

* Bluetooth (5.1)
* Port mapping (theoretically works)

### Not working

* Wi-Fi (AirportItlwm)
* Graphics (?)
  * macOS recovery looks absolutely abysmal, but you can technically see everything
  * Garbled display (Black) for ~60 seconds before Apple logo
* Online macOS installation (no WiFi)


