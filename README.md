# 🎮 Fog Lamp Side Quest

> Broken OEM switch → PCB reverse engineering → perfboard prototype → mission accomplished.

A friend's bike fog-lamp switch stopped working because its PCB pushbuttons had failed. Rather than replace the entire assembly, I opened it up, traced the board, studied the circuit, and built a replacement.

The whole repair and initial KiCad design took approximately **12 hours**, alongside my other work.

## 📸 Build Gallery

### 1. The Original Problem

The damaged OEM switch PCB that started the side quest.

![Damaged original PCB](./damaged_oem.jpg)

### 2. Understanding the Original Design

I inspected the PCB, traced its connections by hand, documented the tracks, and measured the resistors to understand how the circuit worked.

### 3. OEM Board vs. Perfboard Replacement

I measured the original board, shaped a double-sided perfboard to fit, positioned the pushbuttons to match the original mounting points, and soldered the replacement connections and components.

![Original PCB and perfboard replacement](./oem_vs_perfboard.jpg)

### 4. Back on the Bike

The repaired switch was reinstalled in the bike's existing switch assembly and tested.

![Repaired switch installed on the bike](./fixed_on_bike.jpg)

### 5. Installation — Rear View

A second view of the completed installation.

![Rear view of the repaired switch](./fixed_on_bike_back.jpg)

### 6. Original Mount, Working Again

The replacement fitted into the original mount, keeping the repair compact and practical.

![Replacement installed with the original mount](./installed_with_mount.jpg)

## 🛠️ What I Did

- Reverse-engineered the original PCB without an available schematic.
- Traced and documented the PCB connections manually.
- Measured resistors and analysed the circuit.
- Built a dimension-matched, double-sided perfboard replacement.
- Positioned and soldered the replacement pushbuttons and components.
- Reinstalled and tested the repair.
- Designed a custom PCB in KiCad as the next step toward a fabricated board.

## 🧰 Tools & Materials

- Double-sided perfboard
- Replacement pushbuttons and resistors
- Soldering tools
- Multimeter
- Pen-and-paper PCB track tracing
- KiCad for the custom PCB design

## 🏁 Quest Status

- [x] Inspect the failed OEM PCB
- [x] Trace the circuit connections
- [x] Build the perfboard replacement
- [x] Install and test the repair
- [x] Design a custom PCB in KiCad
- [ ] Fabricate and validate the custom PCB (if not yet completed)

## 💡 What I Learned

- PCB reverse engineering and connectivity tracing
- Practical circuit analysis and component measurement
- Translating a physical board into a replacement layout
- Soldering and fitting a prototype within existing mechanical constraints
- Moving from a quick repair to a documented PCB design

## Notes

This is a personal repair and learning project. The successful test refers to the installed perfboard prototype; the custom PCB is a separate design stage. This project is not a certified automotive component or a claim of long-term reliability.

The original product and OEM PCB are not my design. This repository documents my repair process and replacement work; any third-party rights remain with their respective owners.

---

**Side quest completed in approximately 12 hours.** 🔧
