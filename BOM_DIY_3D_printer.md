# DIY 3D Printer - Bill of Materials (BOM)

This document captures the essential components and estimated costs for building a DIY 3D printer on a budget.

---

## **Optimized Cost Breakdown**

| **Component**         | **Budget Option**                                  | **Estimated Cost (EUR)** |
|------------------------|---------------------------------------------------|--------------------------|
| **Frame (Aluminum)**   | 30x30 profiles, cut-to-size (800–1000mm lengths). | €30–50                  |
| **Hotend**             | Creality MK8 or clone of E3D V6 (AliExpress).     | €15–25                  |
| **Extruder**           | BMG clone (e.g., Trianglelab on AliExpress).      | €20–30                  |
| **Controller Board**   | BigTreeTech SKR Mini or MKS Gen L.                | €20–35                  |
| **Heated Bed**         | Standard 200x200mm aluminum + silicone heater.    | €20–30                  |
| **Power Supply**       | Generic 24V PSU (MeanWell clone).                 | €15–20                  |
| **Motion System**      | Bearings, GT2 belts, pulleys, and smooth rods.    | €40–60                  |
| **Display**            | Basic LCD (e.g., 12864 RepRap Display).           | €10–15                  |
| **Miscellaneous**      | T-slot nuts, screws, wiring, etc.                 | €20–30                  |

**Total Estimated Cost**: ~€190–€250

---

## **Key Recommendations**

1. **Frame (Aluminum Profiles)**:
   - Source cut-to-size aluminum profiles from local suppliers or EU stores like **Dold Mechatronik**.
   - Avoid premium brands like Misumi unless necessary.

2. **Hotend and Extruder**:
   - Purchase clones of E3D or Bondtech components from trusted sellers on **AliExpress** or **eBay**.
   - Popular brands: **Trianglelab** and **Mellow** for reliable clones.

3. **Controller Board**:
   - Recommended models:
     - **MKS Gen L v2.1** (~€20–€25): Affordable 8-bit board.
     - **BigTreeTech SKR Mini E3** (~€25–€30): 32-bit board with silent stepper drivers.
   - Use firmware like **Marlin** or **Klipper**.

4. **Heated Bed**:
   - Use a simple aluminum plate with a 24V silicone heater.
   - Purchase from **Keenovo** (AliExpress) or local EU shops.

5. **Power Supply**:
   - A **24V, 350W MeanWell clone** is sufficient for most builds.
   - Buy from **AliExpress** or local electronics stores.

6. **Motion System**:
   - Use **GT2 belts**, pulleys, and smooth rods for affordability.
   - For higher precision, consider **linear rods** or **rails**.

7. **Display and Miscellaneous**:
   - Use a basic **RepRap LCD display** instead of touchscreens to save costs.
   - Bulk purchase screws, T-slot nuts, and wiring from local hardware stores or **Reprapworld**.

---

## **Additional Notes**
- **Hybrid Controller Setup**:
   - Combine a **€20 controller board** with your **server** for advanced features like Klipper and remote monitoring.
   - Ensure the server handles slicing and advanced motion planning while the board manages real-time tasks.

- **ESP32 as an Option**:
   - ESP32 can work as a secondary controller for features like Wi-Fi monitoring but may struggle as the primary MCU for real-time 3D printing tasks.

---

## **Next Steps**
1. Finalize printer design (e.g., Core XY, Cartesian).
2. Start sourcing components from trusted suppliers (e.g., AliExpress, Dold Mechatronik, 3DJake).
3. Assemble and configure your 3D printer.

---

Let me know if you'd like further details or assistance with setup! 😊
