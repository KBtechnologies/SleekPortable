#	SleekPortable
A handheld UMPC designed for serious use

##	Schematic 

---

### Board Layout

```
[Keyboard]   [Trackpoint] <--- [Mouse Buttons] [PoE Extractor - 5V DC] <---> [PoE-Capable Ethernet Port]
  /\                /\                                 /\
  ||                ||                                 ||
[USB 2.0]       [USB 2.0]                        [10/100Base-T]
  ||                ||                                 ||
  \/                \/                                 \/
[LAN 9514 USB 2.0 Hub with built-in 10/100Base-T Ethernet Controller]
 /|\                /\                                 /\ 
 |||                ||                                 ||
[USB 2.0]       [USB 2.0]                          [USB 2.0]
[Uplink]            ||                                 ||
[Port]              \/                                 \/
 |||            [USB-C: Bottom Dock Port] [USB-C - Cartridge Port]
 |||
 \|/
[Backplate (USB 2.0 | 5VDC | HDMI)] <===[USB 2.0 + Mini-HDMI]===> [SBC: Pi Zero (W(2)) or port-compatible]
  | 
  |
  +---[HDMI (or eDP)]---> [ (Display Controller) ---> (Screen) ]
```

---
