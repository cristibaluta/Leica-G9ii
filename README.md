# Leica G9II

> The internals of a Panasonic Lumix G9II inside a Leica M-style body — featuring custom CNC-machined parts and redesigned flex cables and buttons.

---

## 📸 Overview

This project is an attempt to make a beautiful small camera from a Lumix G9II body. The camera is focused on street photography and has some buttons removed.

- Why Lumix MFT? Because the Panasonic-Leica lenses have an aperture ring and they work only on Lumix 
- Why the G9II? Because it was the newest and most capable MFT
- Why Leica M? Because it is the most beautiful camera ever made

If you are an expert in any relevant field and see mistakes you are welcome to correct them or open issues for discussion, my only qualification to do this is that I was into electronics a long time ago.

<img src="images/front.jpg" width="600"/>

---

## 🛠️ What's Included

- `/3D-models/` – STEP files for CNC machining, including threads sheets
- `/FPCBs/` – Schematics and gerber files for the flex cables
- `/docs/` – Assembly guide and exploded diagrams
- `/materials/` – List of extra items and purchase links

---

## 🧰 Materials

| Part                | Description                      | Notes |
|---------------------|----------------------------------|-------|
| Top plate           | Milled aluminum                  | Included in 3D-models |
| Base plate          | Milled aluminum                  |  |
| Front               | Milled aluminum                  |  |
| Back                | Milled aluminum                  |  |
| Heatsink            | Milled copper                    |  |
| Flex cable          | Internal routing rework          | Included in FPCBs |
| Screws              | M1.6 and M2                      | Refer to threads sheets in 3D-models |
| Body (G9II)         | Donor camera                     ||

---

## 🧪 Build Instructions

> ⚠️ Advanced DIY skills required: electronics, soldering, camera disassembly, some original parts will need modifications

1. Disassemble Lumix G9II (see [https://www.youtube.com/@CameraSurgery])
2. Machine or print parts from `/3D-models/` (did it with [https://jlcpcb.com])
2. Print flex cables from `/FPCBs/`
3. Install shutter
4. Install sensor
5. Install PCB
6. Connect the flex cables
7. Install buttons
8. Install screen
9. Install viewfinder
10. Install wifi module
11. Assemble
12. Add leatherete

---

## 📜 License

This project is open-source under the MIT License. Feel free to modify and use — but no commercial use without permission.

---

## Parts removed

1. Lens release push detector (not sure what it was doing beside displaying some info on the screen). There is not enough space to add this detector

---

## TO DO:
1. The dials are too lose
2. The buttons are too short
3. Thread missing from the lever clicker
4. Back wheel not grippy enough
5. Dials gaskets too thin, must be wider
6. 2nd shutter button bigger
7. Front and back could be extended up and down for better strength

---

## 💬 Credits

Created by [Cristian Baluta]  
Youtube: [https://www.youtube.com/@CameraSurgery]
