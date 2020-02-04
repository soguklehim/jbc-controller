# Changelog for v3.x

### v3.31

- PCB changes for optimizing heat dissipation. No functional changes.

---

### v3.3

-   Cartridge shield is now hard grounded.
-   Stand/holder support is improved.
    -   In addition to microswitch support, electrical detection is now possible. Refer the stand/holder detection guide for detailed information.
    -   Delayed activation feature added.
-   New matte front panel option
    -   [Check it out here](https://imgur.com/a/MTaETZB). Limited time only.
-   Control loop retuned
    -   Due to changes required for grounded shield, control loop need to be changed. It is now more aggressive and responsive. May result occasional temperature overshoot.
-   Miscellaneous optimizations and fixes. 

### Information about the hard grounded tip

The JBC C245 cartridge design and electrical characteristics is different from other soldering tips. This cartridge design made difficult to driving with DC. Previously our controllers used the soft ground approach, combined with the unusual cartridge internal design made the shield floating at DC potential while driving. It had some unique advantages but due to popular request **with v3.3, soldering cartridge and the handle ring is always connected to DC ground.** You can connect the controller DC ground to PE if you need it, thus earthing the tip. The aluminum controller casing is also connected to ground.

**Do not power anything other than the controller using the same DC power supply and/or do not ever try to solder anything that connected to same DC power supply, this will damage your device AND the controller by making a direct short.**

---

### v3.2 and below

* Changelog is currently not published for these versions.

