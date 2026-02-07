---
title: "Hypr Nano"
author: "@Jaydev"
description: "An RP2350B based Computer"
created_at: "2026-02-05"
---

# Day - 01 - 2026-02-06
## Started with the schematic

I'm trying to devlelop an RPi RP2350B based SBC-like devboard with lots of features like the [Adafruit's Fruit Jam](https://github.com/adafruit/Adafruit-Fruit-Jam-PCB/). It will have multiple ports (DVI over HDMI with HSTX, USB-Cs, Micro SD slot and a 3.5mm headphone jack too!). This will take RP2350B to the next level. Today I started with the schematic, here -

![Schematic Day - 01](https://github.com/user-attachments/assets/c2fcd174-1315-4c2d-b3e9-a8ad5a1b2506)

### Time spent - 1h

---

# Day - 02 - 2026-02-07
## Added Storage

Yesterday I had added the RP2350B MCU itself, the crystal and VREG unit. Today I looked for good storage options. I was thinking to add the 16 MB Flash + 16 MB PSRAM, but there were no 16 MB PSRAM available. So, I added the 16 MB Flash and an 8 MB PSRAM (the highest available). I have chosen the smallest footprint to keep the board minimal and modern.

![Schematic Day - 02](https://github.com/user-attachments/assets/ff710488-55c9-4561-8c52-7bc4555c7bc3)

### Time spent - 0.7h
