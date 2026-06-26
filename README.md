# KeebCard

A 3-key macropad keychain with an OLED display, built for Hack Club's Stardance event.

## Macropad Design
![Macropad Render](path/to/your-render-screenshot.png)

## Schematic
![Schematic](path/to/your-schematic-screenshot.png)

## PCB Layout
![PCB Layout](path/to/your-pcb-screenshot.png)

## Case (3D)
![Case 3D View](path/to/your-case-3d-screenshot.png)

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
