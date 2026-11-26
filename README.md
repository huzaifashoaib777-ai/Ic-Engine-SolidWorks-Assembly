# Single-Cylinder 4-Stroke IC Engine (SolidWorks)

[Screenshot%202026-11-21%20155903.jpg]

A complete 3D CAD assembly of a **single-cylinder four-stroke Internal Combustion (IC) Engine** modeled and assembled in **SolidWorks**. The project covers the full reciprocating slider-crank mechanism (piston, wrist pin, connecting rod, crankshaft) synchronized with a geared camshaft and overhead rocker-arm valvetrain.

## Project Architecture

- **Reciprocating Assembly (`12. Piston Sub Assemb.SLDASM`):** Piston with compression ring grooves, wrist pin, connecting rod, and rod lock/cap.
- **Valvetrain Assembly (`11. Vlave Sub Assemb.SLDASM`):** Intake/exhaust valves, inner and outer valve retainers, rocker arms, and push/rocker rods.
- **Timing & Final Assembly (`Final Assemb.SLDASM`):** Crankshaft driving the camshaft through small and big timing gears to actuate the valvetrain in sync with the piston stroke.
- **Motion Simulation:** Download or view the engine cycle animation in [`Final Assemb.avi`](Final%20Assemb.avi).

## Bill of Materials (BOM)

| Category | File Name | Description |
| :--- | :--- | :--- |
| **Final Assembly** | `Final Assemb.SLDASM` | Complete IC engine top-level assembly |
| **Sub-Assembly** | `11. Vlave Sub Assemb.SLDASM` | Overhead valve & retainer sub-assembly |
| **Sub-Assembly** | `12. Piston Sub Assemb.SLDASM` | Piston, pin, connecting rod & cap sub-assembly |
| **Power Train** | `Piston.SLDPRT` | Piston with ring grooves & wrist pin bore |
| **Power Train** | `Piston Pin.SLDPRT` | Wrist pin linking piston and connecting rod |
| **Power Train** | `Rod.SLDPRT` | Connecting rod |
| **Power Train** | `Rod Lock.SLDPRT` | Connecting rod bearing cap / lock |
| **Power Train** | `CrankShaft (1).SLDPRT` | Single-throw crankshaft with counterweights |
| **Timing & Cam** | `4. Gear Small.SLDPRT` | Crankshaft timing drive gear |
| **Timing & Cam** | `4. Gear Big.SLDPRT` | Camshaft driven timing gear |
| **Timing & Cam** | `6. Gear Rod.SLDPRT` | Timing gear support shaft / rod |
| **Timing & Cam** | `9. CAM Shaft.SLDPRT` | Camshaft with intake & exhaust cam lobes |
| **Valvetrain** | `5. Rod Rocker Arm.SLDPRT` | Rocker arm pivot shaft |
| **Valvetrain** | `7. Valve.SLDPRT` | Poppet valve |
| **Valvetrain** | `8. Valve Retiner.SLDPRT` | Inner valve retainer |
| **Valvetrain** | `8. Valve Retiner Outer.SLDPRT` | Outer valve retainer |
| **Valvetrain** | `10. Rocker Arm.SLDPRT` | Overhead rocker arm |

## How to Open & Inspect

1. Clone or download all files into a **single local folder** (keep all `.SLDPRT` and sub-assembly `.SLDASM` files in the same directory so SolidWorks resolves all references automatically).
2. Open `Final Assemb.SLDASM` in **SolidWorks**.
3. Rotate `CrankShaft (1)` manually or run **Motion Study** to observe the synchronized piston stroke, timing gear drive, camshaft rotation, and valve actuation.

## Certification

Completed as part of **Design and Assemble an IC Engine Using SolidWorks** (EDUCBA via Coursera, Nov 26, 2026):
- **Verify Credential:** [https://coursera.org/verify/D2CX519PZ6M5](https://coursera.org/verify/D2CX519PZ6M5)
- **Certificate PDF:** [`Coursera D2CX519PZ6M5.pdf`](Coursera%20D2CX519PZ6M5.pdf)

## License

Shared for educational and CAD portfolio purposes under the MIT License.
