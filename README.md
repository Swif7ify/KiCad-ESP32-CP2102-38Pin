# KiCad Library: ESP32 DevKit V1 (38-Pin CP2102)

This repository contains a verified **KiCad Symbol** and **Footprint** for the 38-pin version of the ESP32 DevKit V1 (often featuring the CP2102 USB driver).

I created this library to accurately reflect the physical 38-pin module commonly found on Amazon/AliExpress.

### Features

-   **Correct Pin Count:** 38 Pins total.
-   **Accurate Pinout:** Includes the "Flash Memory" pins often marked as `S02`, `S03`, `CMD`, `CLK`, `SD0`, `SD1`.
-   **Dual Labeling:** Schematic symbol includes both the GPIO number and the board label (e.g., `GPIO09 / S02`) for easier wiring and coding.
-   **Production Ready:**
    -   Pad Type: Through-Hole (THT).
    -   Drill Size: 1.0mm (Standard fit).
    -   Pin Pitch: 2.54mm.
    -   Correct "U-Shape" counter-clockwise numbering.
    -   Includes Pin 1 indicator on Silkscreen.

## 📂 Files Included

-   `ESP32_DevKit_38Pin.kicad_mod` (The Footprint / PCB Layout)
-   `ESP32_DevKit_38Pin.kicad_sym` (The Schematic Symbol)

## 📏 Physical Dimensions Checked

-   **Row Spacing:** Fits standard breadboard-friendly width (approx 25.4mm pitch between rows).
-   **Pad Size:** 2mm x 2mm Square pads for easy hand-soldering.

## How to Use

1.  Download the files.
2.  In KiCad, go to **Preferences > Manage Symbol/Footprint Libraries**.
3.  Add the downloaded `.kicad_sym` file to your Global or Project libraries.
4.  Add the `.kicad_mod` file (or the folder containing it) to your Footprint libraries.
