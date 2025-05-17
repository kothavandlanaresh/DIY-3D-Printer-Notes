# CoreXY 3D Printer Inventory and Flowchart

## 📋 Inventory Overview

| **Category**      | **Component**                                | **Status**          | **Quantity** | **Notes**                                                                 |
|--------------------|----------------------------------------------|---------------------|--------------|---------------------------------------------------------------------------|
| **Structural Frame** | 2040 Aluminum Extrusions                   | Available           | 12 pieces    | Sufficient for frame, but connectors (corner brackets, T-nuts) needed.   |
|                    | Corner Brackets + T-Slot Nuts               | Missing             | N/A          | Required for assembling the frame.                                       |
| **Motion System**  | GT2 Timing Belt (5m x 6mm)                  | In Stock            | 1 piece      | Adequate for CoreXY belt system.                                         |
|                    | MGN12H Linear Rail (300mm)                  | Available           | 3 pieces     | Enough for X, Y, and Z axes.                                             |
|                    | Nema 17 Stepper Motors                      | In Stock            | 5 pieces     | Enough for X, Y, Z axes and extruder.                                    |
|                    | Pulleys, Idlers, and Belt Tensioners         | Missing             | N/A          | Required for GT2 belt system.                                            |
|                    | Lead Screws and Nuts                        | Missing             | N/A          | Needed for Z-axis linear motion.                                         |
| **Extruder and Hotend** | Ganzmetall-Titan-Aero-Extruder          | In Cart             | 1 piece      | Direct drive extruder for flexible filament support.                     |
|                    | Titan Aero Extruder Idler Arm               | In Cart             | 1 piece      | Compatible with Titan Aero extruder.                                     |
|                    | A1 Mini/A1 Hotend Kit                       | Available           | 2 sets       | Compatible with CoreXY with custom mounting.                             |
|                    | MK7/MK8 Drive Gears                         | In Cart             | 2 pieces     | For filament grip in extruder.                                           |
|                    | Cooling Fans (3010/4010/5010 DC)            | In Cart             | 1 piece      | Includes hotend and part cooling fans.                                   |
| **Build Platform** | Heated Bed (235x235x3mm, 24V)               | In Cart             | 1 piece      | Suitable size for CoreXY.                                                |
|                    | Magnetic PEI Sheet (235mm)                  | In Cart             | 1 piece      | Great for print adhesion and easy removal.                               |
|                    | Bed Mounting Brackets/Springs               | Missing             | N/A          | Needed to secure the heated bed to the frame.                            |
|                    | Bed Insulation                              | Missing             | N/A          | Recommended for efficient heating.                                       |
| **Electronics and Control** | Bigtreetech Octopus Pro V5.0        | Available           | 1 piece      | High-performance controller board.                                       |
|                    | TMC2226 Stepper Drivers                     | Available           | 5 pieces     | Silent and efficient stepper motor operation.                            |
|                    | ESP32 WROOM (Wi-Fi + Bluetooth)             | Available           | 1 piece      | For wireless control and IoT features.                                   |
|                    | Limit Switches                              | In Cart             | 5 pieces     | For endstop detection.                                                   |
|                    | Makerbase 3D Touch Sensor                   | In Cart             | 1 piece      | Auto bed leveling sensor.                                                |
|                    | Wiring Harnesses/Connectors                 | Missing             | N/A          | Needed for motors, sensors, and fans.                                    |
|                    | Cable Management (Chains/Spiral Wraps)      | Missing             | N/A          | For clean and organized wiring.                                          |
| **Power Supply**   | MW UHP-500-24 (24V, 500W)                   | Available           | 1 piece      | Adequate power supply for the system.                                    |
| **Cooling System** | Fans (3010/4010/5010 DC)                    | In Cart             | 1 piece      | Required for hotend and electronics cooling.                             |
| **Tools and Assembly** | Crimping Tools, Soldering Iron, etc.     | Available           | Complete Set | Comprehensive set for wiring and assembly tasks.                         |

---

## 🔧 Flowchart for CoreXY 3D Printer Design

```plaintext
START
  |
  v
[Structural Frame]
  |--> 12x 2040 Aluminum Profiles (Available)
  |--> Corner Brackets + T-Nuts (Acquired)
  |
  v
[Motion System]
  |--> GT2 Timing Belt (Available)
  |--> 3x MGN12H Linear Rails (Available)
  |--> Lead Screws + Nuts for Z-Axis (Missing)
  |--> Pulleys, Idlers, Belt Tensioners (Missing)
  |--> 5x Nema 17 Stepper Motors (Available)
  |
  v
[Extruder + Hotend]
  |--> Titan Aero Extruder + Idler (In Cart)
  |--> A1 Mini/A1 Hotend Kit (Available but may need custom mount)
  |--> MK7/MK8 Drive Gears (In Cart)
  |--> Cooling Fans (In Cart)
  |
  v
[Build Platform]
  |--> Heated Bed (In Cart)
  |--> Magnetic PEI Sheet (In Cart)
  |--> Bed Mounting Brackets + Springs (Missing)
  |--> Bed Insulation (Missing)
  |
  v
[Electronics + Control]
  |--> Bigtreetech Octopus Pro V5.0 (Available)
  |--> TMC2226 Stepper Drivers (Available)
  |--> Limit Switches (In Cart)
  |--> Makerbase 3D Touch Sensor (In Cart)
  |--> Wiring Harnesses + Connectors (Missing)
  |--> Cable Management (Missing)
  |
  v
[Power Supply]
  |--> MW UHP-500-24 (Available)
  |
  v
[Cooling System]
  |--> Fans for Hotend + Electronics (In Cart)
  |
  v
[Next Steps]
  1. Procure missing components (lead screws, pulleys, etc.).
  2. Assemble frame with linear rails and Z-axis lead screws.
  3. Test-fit the A1 Mini Hotend with Titan Aero extruder or design a custom mount.
  4. Wire electronics and configure firmware (Klipper).
  5. Perform calibration and test printing.
  |
  v
  END
```
