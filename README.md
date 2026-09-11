
# Two-Stage OTA Design (TSMC 180nm CMOS: LTspice)
**Author:** Jit Barui (ID: 230108022)

## 📌 Problem Statement & Required Specifications
Design a low-power two-stage operational transconductance amplifier (OTA) using **TSMC 180nm technology**. The project is implemented and verified across two environments: **LTspice** (for initial schematic validation and closed-loop testing) .

**Required Specifications:**
* The OTA must operate in a **non-inverting amplifier** configuration with a **closed-loop gain of 2** (LTspice).
* The **open-loop DC gain** of the OTA must be **at least 40 dB** (with higher targets for the Cadence layout).
* The amplifier must be **stable**, with a **phase margin of approximately 60° to 75°**.
* The design should respond properly to a **0.2 V step input**.



## 📉 LTspice Key Design Highlights
* ✅ **Open-loop gain:** ~2360 (≈ 67.4 dB)
* ✅ **Closed-loop gain:** ≈ 2 (non-inverting)
* ✅ **Phase margin:** ~60°
* ✅ **Bandwidth:** Verified through AC analysis
* ✅ **Transient Response:** Stable step response to 0.2 V input


## 🔧 Technology & Tools

* **LTspice** for schematic-level simulation and transient testing.
* **TSMC 180nm CMOS** design node.
* **Analog CMOS Design** principles (manual sizing, pole-splitting Miller compensation).

---

## 📚 References
* EE206: Analog Electronic Circuits, course materials and assignments

