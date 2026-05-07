# Phase 2: NIMBUS-E — The Hybrid Thermal-Electric System

> **Note:** Images referenced below are planned. Prompts for generating them with AI image tools are included at the end of each section. Contributions are welcome.

---

## 1. Concept
Once the core thermal lift system of Phase 1 is validated, the natural next step is to add onboard electrical generation. This transforms NIMBUS from a passive solar aerostat into a partially steerable hybrid airship: **NIMBUS-E.**

### Spectrum Splitting at the Receiver
Sunlight concentrated onto the ceramic receiver contains three components:

| Component | Share | Role |
| :--- | :--- | :--- |
| **Near-infrared** | ~50% | Heats internal air → lift |
| **Visible light** | ~45% | Intercepted by PV layer → electricity |
| **Ultraviolet** | ~5% | Absorbed as additional heat |

A thin photovoltaic layer is added to the front face of the ceramic receiver. Visible light is converted to electricity before the remaining radiation heats the SiC honeycomb behind it. This is called **spectrum splitting** and is an active area of research in concentrated solar power (CSP) systems.

**Important design note:** Standard silicon PV cells fail above ~80°C and cannot survive near the ceramic receiver. NIMBUS-E will use either **GaAs (Gallium Arsenide)** cells — which tolerate high irradiance and elevated temperatures — or position the PV layer slightly offset from the ceramic core, in the cooler airstream, so that infrared passes through to the honeycomb while visible light is captured. 

Both approaches are being evaluated, as well as the possibility to use a **Dichroic Mirror** or a **Beam Splitter**.

*Estimated electrical output: modest but sufficient for tracking motors, sensors, communications, and partial propulsion.*

> **Image 7 — Receiver cross-section diagram** > *AI image prompt: "Technical cross-section diagram of a solar receiver: a Silicon Carbide honeycomb block behind a thin photovoltaic layer, labelled arrows showing near-infrared passing through to the ceramic, visible light absorbed by the PV layer, white background, clean engineering style."*

---

## 2. Thermal Battery — Flying After Sunset
Because the receiver operates at high temperature, it naturally acts as a **thermal mass**. Phase 2 will explore integrating **Phase Change Materials (PCM)** — substances that store and release large amounts of heat during melting and solidification — inside or around the ceramic receiver.

This would allow NIMBUS-E to remain buoyant for **1–2 hours after the sun goes down**, using stored heat rather than active solar input. This is a significant safety and operational advantage over conventional aerostats, which lose lift immediately when solar input drops.

> **Image 8 — PCM thermal storage diagram** > *AI image prompt: "Schematic diagram of a thermal battery integrated into a ceramic receiver block, showing Phase Change Material layer surrounding a SiC honeycomb, arrows indicating heat storage and release cycle, clean technical illustration, white background."*

---

## 3. Onboard Electrical Systems Enabled
The electricity generated opens four new capabilities:

* **Autonomous Sun Tracking:** The two-axis cable mechanism of Phase 1 is motorised, replacing manual control with a sensor-driven automatic tracking system. This improves optical precision and reduces pilot workload.
* **Altitude Control:** The electricity produced can be used for a **Ballonet**: an internal bag inflated with outside air to increase weight and control descent.
* **Steering and Station-Keeping:** Small electric thrusters or vectored fans on the gondola provide limited directional control — enough to compensate for wind drift and hold a position. Meaningful station-keeping transforms NIMBUS-E into a steerable platform.
* **Onboard Instrumentation:** Sensors, cameras, and communication systems powered indefinitely during daylight hours.

> **Image 9 — Tracking motor integration diagram** > *AI image prompt: "Diagram of a two-axis cable-driven solar tracking mechanism inside a transparent sphere, with small electric motors at the cable anchor points, labelled, clean engineering drawing style, white background."*

> **Image 10 — Propulsion pod concept** > *AI image prompt: "Concept illustration of a small gondola beneath a large transparent spherical balloon, with two small vectored electric thrusters mounted on the sides, clean technical concept art style, blue sky background."*

---

## 4. Impact on Envelope Size
Recovering an estimated 8–10% of total solar input as electricity reduces the thermal load required for lift. This allows a modest reduction in envelope diameter — approximately **5–10% compared to Phase 1** — while maintaining the same payload capacity. Supporting calculations will be published in the `/calculations` folder.

---

## 5. Commercial Applications
Station-keeping capability fundamentally changes the commercial proposition of NIMBUS. A steerable, fuel-free solar airship opens markets in:
* Aerial photography and surveying
* Environmental monitoring
* Telecommunications relay
* Tourism and recreational flight

---

## Status
⏳ **Planned** — pending successful validation of Phase 1 thermal lift system.

Contributions and simulations related to spectrum splitting, high-temperature PV cells, PV-thermal hybrid receivers, Phase Change Materials, and electric propulsion at aerostat scale are welcome. Open an Issue or contact the author directly.

> *"The crisis requires sharing, not secrecy."*
