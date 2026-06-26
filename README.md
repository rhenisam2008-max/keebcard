# KeebCard

A 3-key macropad keychain with an OLED display, built for Hack Club's Stardance event.

## Macropad Design
![Macropad Render](render.png)

## Schematic
![Schematic](schematic.png)

## PCB Layout
![PCB Layout](pcb_layout.png)

## Case (3D)
![Case 3D Bottom View](bot_case.png)
![Case 3D Top View](top_case.png)

## Bill of Materials

| Part | Qty |
|---|---|
| Seeed XIAO RP2040 microcontroller | 1 |
| MX-style mechanical push switches | 3 |
| 0.91" 128×32 I2C OLED display | 1 |

## Firmware
Built with QMK. See `/Firmware` for source.

## Build folders
- `CAD/` — 3D printed case model
- `PCB/` — KiCad schematic and PCB design files
- `Firmware/` — QMK firmware source
- `production/` — Manufacturing-ready files (Gerbers, STEPs, compiled firmware)
