# Nimbus
Nimbus: An Open-Source aerostat using an internal solar concentrator and ceramic receiver to generate thermal lift. Clean flight, no fuel.


# NIMBUS — Solar Thermal Aerostat
### An open-source flying platform powered by concentrated solar energy

![Nimbus Concept](images/01.png)

---

## What is NIMBUS?

NIMBUS is a solar-powered aerostat that generates lift by heating its internal air volume using concentrated sunlight — no fossil fuels, no helium. A transparent spherical envelope acts as a solar reactor: inside, a mobile parabolic concentrator tracks the sun and focuses radiation onto a high-temperature ceramic honeycomb receiver, which heats the internal air and generates Archimedean buoyancy.

---

## How It Works

### 1. The Transparent Envelope
A spherical shell made of high-strength transparent polymer (ETFE) contains the heated air volume and allows solar radiation to enter with minimal refraction.

### 2. The Internal Concentrator
A lightweight Mylar parabolic reflector inside the sphere focuses incoming solar radiation onto a single focal point. It is mounted on a two-axis mechanism that tracks the sun independently of the balloon's orientation.

### 3. The Ceramic Receiver
A Silicon Carbide (SiC) honeycomb receiver sits at the focal point. Internal air circulates through its channels, heating rapidly by contact with the incandescent ceramic walls.

### 4. The Exoskeleton
A rigid external framework of carbon fiber maintains the sphere's shape and houses C-shaped tracks. A tension-cable system running inside these tracks allows the pilot or an automated system to orient the concentrator on two axes with no backlash.

### 5. The Solar Theater (Ground Infrastructure)
A semi-circular array of heliostats on a south-facing slope beams additional solar energy into the sphere during takeoff — acting as a thermal catapult that reduces the required envelope diameter and time to lift-off.

---

## Empirical Validation

A first experiment was conducted using a foil-lined parabolic shell (16cm diameter) with a standard thermometer at the focal point. Starting from an ambient temperature of 22.5°C, the focal point reached **41°C within seconds**, confirming rapid energy concentration at the focal point.

![Experiment](images/Exp1.jpg)

---

## Scale Model

A physical scale model was built using metal tubes, cables, and a 16cm transparent sphere to demonstrate the exoskeleton kinematics and two-axis cable-driven tracking mechanism.

![Scale Model](images/Model.jpg)

---

## Target Specifications (Design Goal)

| Parameter | Value |
|---|---|
| Envelope diameter | 13 m |
| Envelope material | ETFE 100 g/m² |
| Estimated structure weight | ~107 kg |
| Target payload | 150 kg (2 persons) |
| Required ΔT for flight | ~85–100°C |
| First flight type | Tethered |

---

## Project Status

| Phase | Status |
|---|---|
| Concept definition | ✅ Complete |
| Physical scale model | ✅ Complete |
| Focal point thermal test | ✅ Complete |
| Closed-volume ΔT measurement | 🔄 Next step |
| GitHub repository | ✅ Active |
| Hackaday publication | 🔄 In progress |
| Crowdfunding campaign | ⏳ Planned |

---

## How You Can Help

NIMBUS is fully open-source and at an early validation stage. Collaboration is welcome in these areas:

- **Optical/thermal simulation** — CFD or ray-tracing models to predict achievable ΔT at scale
- **Materials expertise** — feedback on envelope polymers, reflective films, and ceramic receiver design
- **Mechanical engineering** — refinement of the two-axis cable-driven tracking system

If you're interested in being notified when the crowdfunding campaign launches, open an Issue or leave a comment on the Hackaday project page.

---

## Repository Contents

```
/images          — All project photos and diagrams
/calculations    — Weight, lift and thermal estimates (spreadsheet)
/docs            — Full project description (5 chapters)
/model           — Bill of materials for the scale model
```

---

## License

This project is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.
You are free to share and adapt the material for any purpose, provided appropriate credit is given.

---

## Author

**Michele Lorenzi** — Independent inventor and researcher.
Project started in Trentino, Italy.
Contact: michele.lorenzi@hotmail.it

---

*"The crisis requires sharing, not secrecy."*
