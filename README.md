HP ZBook 14u G6 EFI Folder for Hackintosh based in OpenCore
=============================================================
Laptop Specs:
=============================================================
CPU: Intel Core i7-8565U

GPU: Intel UHD Graphics 620

     AMD Radeon Pro WX 3200 (disabled in BIOS, Advanced - Built-in device options - Graphics: UMA Graphics)
          
RAM: 32 GB DDR4

Wi-Fi and Bluetooth: Fenvi BCM94352Z 

Display: 13.6" 3840x2160 4K

--------------------------------------------------------------
Tested macOS: Monterey (12) and Ventura (13)

Note: Use GenSMBIOS to generate your own SMBIOS (Copy it on PlatformInfo›Generic) in order to be able to boot. P.S. I recommend MacBookPro15,1 SMBIOS.
______________________________________________________________

What works?
===
1. Graphics acceleration
2. Wi-Fi and Bluetooth
3. Continuity Features (AirDrop, Instant Hotspot, Handoff, Sidecar, Continuity Camera, Universal Control)
4. HP HD Webcam
5. Internal Speakers
6. Keyboard
7. Trackpad and Trackpoint
8. Ethernet
9. USB-A and USB-C ports
10. HDMI port

----------------------------------------------------

What doesn't work or haven't been tested?
==
1. Microphone (Tested, doesn't work)
2. SD Card Reader (Not tested, might not work since no related kext was added)
3. HP Slim Dock Port (Not tested, video outputs and USB port might work)
4. Fingerprint scanner (Not compatible due to T2 chip issues of Hackintosh)
5. SC slot (Not tested, should not work)

----------------------------------------------------
