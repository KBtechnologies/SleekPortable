#	SleekPortable Cartridge
##	`TODO`

---

- Define [mechanical an electical interfaces.](./cartridges-comparison.tsv)
  - USB 2.0
    - Potentially USB 3.0
    - [USB-C Connector](https://en.wikipedia.org/wiki/USB-C#USB_Type%E2%80%91C_cable_and_connector_specifications)
      - Higher Cycle lifetime
        - As per [USB-C Specification 3.18.1.3 (EIA 364-09)](https://www.usb.org/sites/default/files/USB%20Type-C%20Spec%20R2.0%20-%20August%202019_0.pdf): 10.000 Cycles minimum
      - [USB 2.0 Mode](https://en.wikipedia.org/wiki/USB-C#Cables_2)
      - [Audio Accessory Mode](https://en.wikipedia.org/wiki/USB-C#Audio_Adapter_Accessory_Mode) needs to be enabled/supported
      - [Debug Accessory Mode](https://en.wikipedia.org/wiki/USB-C#Debug_Accessory_Mode)?
      - [Power Delivery Support](https://en.wikipedia.org/wiki/USB_hardware#USB_Power_Delivery)?
  - 3,5mm TRRS Headset Jack [equivalent]
    - CTIA pinout
      - For connecting WWAN modules and allow voice calling
  - Connector Selection
    - Choosing one of these connectors to save costs:
      - [Sub-D Connectors](https://en.wikipedia.org/wiki/D-subminiature)
        - [DA-26](https://www.amazon.de/dp/B0FG756DWF)
        - [DB-44](https://www.amazon.de/dp/B0F66LKDKH)
        - DC-62 [(female)](https://www.amazon.de/dp/B0F6JVH55D) [(male)](https://www.amazon.de/dp/B0F66HRNFK)
        - [LFH 60-pin](https://de.aliexpress.com/item/1005006720208976.html) [(male)](https://www.alibaba.com/product-detail/Accessory-15922250-60-Position-D-Type_1601930355517.html) [(female)](https://www.alibaba.com/product-detail/LFH-60Pin-Male-DVI-Stainless-Steel_1601808212469.html)
          - Basically identical to [DMS-59](https://en.wikipedia.org/wiki/DMS-59) just with [all 60 pins present](https://en.wikipedia.org/wiki/Low-force_helix)
      - [2,54mm pitch IDC dual-row connectors](https://de.aliexpress.com/item/1005007307830993.html)

      - [SATA](https://en.wikipedia.org/wiki/SATA#Data_connector)
        - [SATA Slimline](https://en.wikipedia.org/wiki/SATA#Slimline_power_connector_(6_pins))
        - [SATA micro](https://en.wikipedia.org/wiki/SATA#Micro_connector)
        - [eSATA](https://en.wikipedia.org/wiki/ESATA)
          - [eSATAp](https://en.wikipedia.org/wiki/ESATA#eSATAp)
      - [miniPCIe](https://en.wikipedia.org/wiki/PCI_Express#Mini-SATA_(mSATA)_variant)
      - [M.2](https://en.wikipedia.org/wiki/M.2#Form_factors_and_keying)
        - [G-Key](https://de.aliexpress.com/item/1005001411642615.html)
      - [DisplayPort](https://de.aliexpress.com/item/1005006099055034.html)
      - [DVI-I 24+5 pin](https://de.aliexpress.com/item/1005004244293520.html)
- Define mechanical dimensions
  - Slot dimensions
  - Mating Surfaces
  - Connector Area
  - "Safe Areas" (no extension allowed)
  - "Open Areas" (Modules are allowed to extend this way)


