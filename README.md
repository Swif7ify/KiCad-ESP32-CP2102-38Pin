# KiCad Library: ESP32 DevKit V1 (38-Pin CP2102)

This repository contains a verified **KiCad Symbol** and **Footprint** for the 38-pin version of the ESP32 DevKit V1 (often featuring the CP2102 USB driver).

![ESP32 38-Pin Board](https://github.com/user-attachments/assets/3b9140f2-401f-44b7-a4f1-67e71d4ffaad)
<br>
*A 38-pin ESP32 CP2102 module, which this library is designed to represent.*

I created this library to accurately reflect the physical 38-pin module commonly found on Amazon/AliExpress, as standard libraries often miss the correct pinout for this specific version.

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

### Schematic Symbol (`ESP32_DevKit_38Pin.kicad_sym`)

![KiCad Symbol Screenshot](https://github.com/user-attachments/assets/a20a4426-06b7-4d49-b357-4a3b04aba17e)
<br>
*The schematic symbol, showing the 38 pins with dual labeling for GPIO and board-specific names.*

### Footprint / PCB Layout (`ESP32_DevKit_38Pin.kicad_mod`)

![KiCad Footprint Screenshot](https://github.com/user-attachments/assets/f9de7f36-780c-476d-8ab3-9d072e645541)
<br>
*The PCB footprint, featuring 1.0mm through-hole pads with a 2.54mm pitch and a clear pin 1 indicator on the silkscreen.*

## 📏 Physical Dimensions Checked

-   **Row Spacing:** Fits standard breadboard-friendly width (approx 25.4mm pitch between rows).
-   **Pad Size:** 2mm x 2mm Square pads for easy hand-soldering.

## How to Use

1.  Download the files from this repository.
2.  In KiCad, go to **Preferences > Manage Symbol Libraries** and add the `.kicad_sym` file.
3.  Go to **Preferences > Manage Footprint Libraries** and add the `.kicad_mod` file (or the folder containing it).
4.  You can now search for `ESP32 CP2102` in your schematic editor!
