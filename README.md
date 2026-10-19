# KQC — RP2040 PMOD

A **KiCad PCB design** for an **RP2040 PMOD** module: a Raspberry Pi RP2040-based add-on board exposing peripherals through PMOD connectors. Designed in KiCad 7.

## 🧩 Sub-circuits (schematics)

- `rp2040.kicad_sch` — RP2040 MCU core
- `supply.kicad_sch` — Power supply
- `wifi.kicad_sch` — Wi-Fi module
- `rf.kicad_sch` — RF
- `nfc.kicad_sch` — NFC
- `dio.kicad_sch` / `dio_oled.kicad_sch` — Digital I/O + OLED

## 📁 Project Files

```
KQC.kicad_pro          # KiCad project
KQC.kicad_pcb          # PCB layout
KQC.kicad_sch          # Top-level schematic
*.kicad_sch            # Sub-schematics
rp2040_pmod.zip        # Archived export
KQC-backups/           # Auto backups
```

## 🚀 Getting Started

### Prerequisites
- [KiCad](https://www.kicad.org/) 7.x or newer

### Open
1. Launch KiCad.
2. Open `KQC.kicad_pro`.
3. Use the Schematic Editor / PCB Editor to view or modify.

### Fabrication
- Generate Gerbers from the PCB Editor (File → Fabrication Outputs → Gerbers).
- The `rp2040_pmod.zip` contains a previous export.

## 📄 License
No license specified. (Hardware design — consider adding a hardware license such as CERN-OHL.)