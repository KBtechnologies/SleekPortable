#	SleekPortable
###	A handheld UMPC designed for serious use

---

##	Rationale
The lack of portable computing options that ain't heavy laptops or anti-repair - design tablets is lacking.
- Espechally when it comes to devices with actual keyboards that people can type almost blindly on.
  - Shure, one could [take a Pi 400, strap a screen and battery bank to it](https://www.youtube.com/watch?v=guGffGw3uDg&t=49s) but that's *hardly compact* anymore!

---

##	Goal
###	Be compact
####  It needs to be portable as in "fitting into pockets"...
- The maximum feasible size for jackets is 12cm overall depth and an ultrawide form factor (See VAIO P11Z), but that's not an option besides Cargo Pants and deep-pocket Jackets.
- The maximum feasible size for Pants is that of the GBA SP [with a bit of wiggle room in terms of depth] as it's pretty chonky...

####  The exact case is [to be determined.](docs/case/TODO.md) Some Comparisons have been [noted down here.](docs/case/TODO.md)

###	Be useful
####  It needs to be able to run a useable Linux OS.
- [`_OS/1337`](https://github.com/OS-1337/OS1337) may be fine for some, but ideally it should be capable of more.
  - If in doubt, it needs to be able to fit a [Raspberry Pi Zero W](https://www.raspberrypi.com/products/raspberry-pi-zero-w/) [(2)](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/) for it's compute needs.
    - But generally any SBC in it's form factor should work.
- Make it a simple yet nifty system.
  - Not just for *"red teaming"* networks with Kali Linux.
  - Make it a nice PDA-esque system for efficient use on the go.

####  It needs to have sufficient connectivity.
- MicroSD (Boot Storage)
- USB (Additional Hardware)
  - Using the "Cartridge Slot" at the rear/underside for connectivity next to some ports.
  - internal parts?
    - Keyboard
    - Trackpoint + buttons
    - Hub to connect all of the external and internal ports
- [3,5mm TRRS (CTIA-Compliant)](https://en.wikipedia.org/wiki/Phone_connector_(audio)#TRRS_standards) Headset Jack
  - OMTP compatibility with passive adapters.
  - Optional Switch for AV-Out?
- [USB-C Power Delivery](https://en.wikipedia.org/wiki/USB_hardware#USB_Power_Delivery) [at least 5V @ 3A max.] for charging.
  - Port at the underside for a dock
    - Hardware switch: Power/charging only or power + data (i.e. for a Dock similar to the GPI Case 2 and [Analogue Pocket](https://en.wikipedia.org/wiki/Analogue_Pocket)).
- Nice to Haves:
  - 100Mbit/s Ethernet [via USB]
    - [Power over Ethernet](https://en.wikipedia.org/wiki/Power_over_Ethernet#Two-_and_four-pair_Ethernet) as either a port on the dock and or cartridge [similar to some Pi0 accessories](https://www.waveshare.com/product/iot-communication/wired-comm-converter/ethernet/poe-eth-usb-hub-hat.htm).
  - Cartridge Slot
    - The design and pinout [is to be determined.](docs/cartridges/TODO.md)
      - Some comparisons are [noted down here.](docs/cartridges/cartridges-comparison.tsv)

####  It needs to make sense.
- It needs to have useful features
  - hot-swappable [batteries](docs/battery/TODO.md)
    - it needs to have sufficient battery runtime anyway.
- It needs to be affordable
  - If it's as expensive as a Laptop + Smartphone, then there's no reason to use it.

---

##	Acknowledgements
####  This project is inspired by various devices beloved by many.
- [GameBoy Advance SP](https://en.wikipedia.org/wiki/Game_Boy_Advance_SP)
  - For being a compact handheld that feels great and just is super pocketable.
    - It's [dimensions & form factor](https://en.wikipedia.org/wiki/Game_Boy_Advance_SP#Technical_specifications) is the design inspiration
- [Anbernic RG34XXSP](https://en.wikipedia.org/wiki/Anbernic_RG35XXSP)
  - Obviously a copy of the GBA SP's design, but with a more modern ARM SoC used to play various Retro Games from microSD cards.
- [Retroflag GPi Case](https://retroflag.com/GPi-CASE.html) [(2)](https://retroflag.com/gpi_case_2.html), a popular case for Pi Zero W & CM4 W SBCs in the form factor of the original [GameBoy](https://en.wikipedia.org/wiki/Game_Boy).
- [Sony VAIO P](https://en.wikipedia.org/wiki/Sony_Vaio_P_series)
  - For showcasing what a [Netbook](https://en.wikipedia.org/wiki/Netbook) can do if budget isn't holding it down.
    - Unfortunately it's [garbage iGPU](https://en.wikipedia.org/wiki/Intel_GMA#PowerVR_GPU_series) made it age *worse* than the [original Eee PC](https://en.wikipedia.org/wiki/Asus_Eee_PC#Eee_700_series)
- [solder.party KeebDeck](https://www.solder.party/keeb/)
  - A tiny, [opensource](https://www.solder.party/docs/keebdeck/) Thumb Keyboard inspired by the [Blackberry Bold 9700](https://en.wikipedia.org/wiki/BlackBerry_Bold_9700) keyboard and it's diminishing stockpiles of replacements.
- [Xbox 360 Chatpad](https://en.wikipedia.org/wiki/List_of_Xbox_360_accessories#Messenger_Kit)
  - Another tiny Keyboard used mostly for Text Chatting on Xbox Live and typing in Text on the Xbox 360 instead of the on-screen keyboard.
- dreamGEAR MiniKey
  - A discontinued, [tiny USB Keyboard](https://projects-raspberry.com/2022-cyberdeck-contest-the-folding-mini-deck/) originally marketed for use on the [PlayStation 2](https://en.wikipedia.org/wiki/PlayStation_2) for entering game cheats.
- [violence.works VT-69 Terminal](http://violence.works)
  - A [stupid terminal](https://en.wikipedia.org/wiki/Computer_terminal) that is [portable and provides the ability to also host a Pi Zero (W)](https://www.youtube.com/watch?v=wYfpptgb6W8).
- [Pagers](https://en.wikipedia.org/wiki/Two-way_pager) like the iconic [NTT Pocket Bell](https://www.youtube.com/watch?v=xbX0MYLEx5o&t=362s), [BlackBerry 950](https://en.wikipedia.org/wiki/BlackBerry_950), [RockSTAR Burst](https://www.groundcontrol.com/product/rockstar-burst) & [GroundControl RockSTAR](https://www.groundcontrol.com/product/rockstar-global-satellite-messaging-tracking/) [the latter ones using the [Iridium 9602 Module](https://www.iridium.com/products/iridium-9602-module)].
- Flip Phones like the iconic [Motorola RAZR](https://en.wikipedia.org/wiki/Motorola_Razr).
- Marcin Plaza's [*upcycled foldable Phone*](https://www.youtube.com/watch?v=qy_9w_c2ub0) because it's cool.
- [Iridium 9555](https://www.iridium.com/products/iridium-9555)
  - Your [Chonky Brick Satellite Phone](https://www.youtube.com/watch?v=RjkNPvzCRKg) that only got beaten by the [Iridium 9575](https://www.youtube.com/watch?v=sZWN65NqNOc) &  [Iridium Extreme PTT](https://www.iridium.com/products/iridium-extreme-ptt).
  - Designed to be rugged and just work globally!

