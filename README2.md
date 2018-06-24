# DIY Keycap dye sublimation

Some information of this post is derived from [Idea23's guide](https://www.reddit.com/r/MechanicalKeyboards/comments/6egoot/idea23_how_to_dye_sub_your_own_caps/).

I needed the following tools:

- Printer EPSON Workforce WF-2750DWF bought in a local retail store
- Dye sublimation paper, random brand: JetStream Digital Dye Sublimation Paper ([Link](https://www.amazon.fr/gp/product/B00YEIKFMC/ref=oh_aui_detailpage_o04_s00?ie=UTF8&psc=1))
- Dye sublimation ink
  - I mixed two brands because the first brand shipped me the wrong type of black ink.
  - If I were to buy more dyesub ink I would try the Stampa Continua brand.
- CISS (continuous ink supply system) from AliExpress ([Link](https://fr.aliexpress.com/store/product/4-Color-Set-T1631-T1634-Continuous-Ink-Supply-System-For-EPSON-WF-2650-WF-2660-WF/1653202_32590500568.html?spm=a2g0w.12010615.0.0.72f28cffvUBW24))
- 220°C (430°F) Heating element from AliExpress ([Link](https://fr.aliexpress.com/item/2-Pcs-Ptc-Heaters-Heating-Element-Hair-Dryer-Accessories-Curlers-Heater-80-120-220-Degrees-Celsius/32695646350.html?ws_ab_test=searchweb0_0%2Csearchweb201602_1_10152_10065_10151_10130_10068_10136_10137_10157_10060_10138_10155_10062_10156_437_10154_10056_10055_10054_10059_303_100031_10099_10103_10102_10096_10147_10052_10053_10107_10050_10142_10051_10084_10083_10080_10082_10081_10178_10110_519_10111_10112_10113_10114_10182_10185_10078_10079_10073_10123_142%2Csearchweb201603_16%2CppcSwitch_5&btsid=d9b33f4c-f63e-4adb-8c9c-402c51550ff0&algo_expid=33118be6-cc77-44b3-b2a0-9dc4772bf5b6-0&algo_pvid=33118be6-cc77-44b3-b2a0-9dc4772bf5b6))
- Heat resistant adhesive, random brand ([Link](https://www.amazon.fr/gp/product/B00EU83A2I/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1))
- A 12V power supply, I used a spare computer PSU

Salvage:
- Small pieces of wood
- Kitchenware silicon
- Regular adhesive tape

I downloaded the following:

- InkOwl ICC profiles for their brand of dye sublimation ink ([Link](https://www.inkowl.com/page/performance-d-icc-profiles/))
  - Note that I don't use their brand of ink
- EPSON Drivers ([Link](ftp://download.epson-europe.com/pub/download/6031/epson603119eu.exe))
  - There are some relevant notes about drivers in this post.

### About CISS kit and drivers

The CISS kit comes with a custom cartridge. This cartridge is only recognized after pressing a button on the cartridge. The printer will continue to function until it is powered off,

Whenever the cartridge is not recognized the button needs to be pressed again, which will engage a head cleaning cycle, which will waste ink. Therefore I suggest leaving the printer in sleep mode.

Also, some printer vendors use firmware updates to block custom cartridges, since most of their business model is the sales of ink cartridges. Be wary of that when installing drivers.

### Color management

One of the two worst parts of dye sublimation is color management.

Regular printers are made for printing documents or photos, therefore cartridge ink are usually calibrated so that it will look good when it's printed on paper or photo paper.

When printing with dye sublimation ink, the pictures will never look good on dye sublimation paper, because it's not meant to stay on that. In our cases, it's meant to be sublimated on PBT plastic, after which point the picture might look good.

The printer when purchased comes with installation cartridges with a very limited amount of ink, but enough ink for me to experiment with the printer's drivers. I have to print good quality color pictures on regular paper before I get any chance at sublimating something decent.

When experimenting with regular ink and dyesub ink, I kept traces of my work and took photos and descriptions of what I did configure and the timings and techniques used during sublimation. It helps when I need to replicate the correct configuration weeks later and figure out what I did wrong.

