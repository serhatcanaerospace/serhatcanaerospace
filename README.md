# Hi, I'm Serhat Can Dalmış 👋

**Aerospace Engineer** — Computational Fluid Dynamics (CFD) & Finite Element Analysis (FEA)

![Email](https://img.shields.io/badge/Email-serhatcandalmis%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white) ![LinkedIn](https://img.shields.io/badge/LinkedIn-Serhat%20Can%20Dalm%C4%B1%C5%9F-0A66C2?style=flat&logo=linkedin&logoColor=white) ![Location](https://img.shields.io/badge/Location-Turkey-lightgrey?style=flat)

Aerospace engineering graduate (2026) working on CFD and FEA: ASME V&V20 mesh-independence
and verification (GCI), turbulence modeling, reacting-flow/combustion, conjugate heat transfer
(CHT), and fluid-structure interaction (FSI). Active in TEKNOFEST and IREC rocketry teams on
propulsion and aerodynamics. Two conference papers accepted at HAVÖS 2026; currently running a
TÜBİTAK 2209-A research project on LS-DYNA impact modeling.

---

## 💼 Experience

**Associate Engineer (Long-term Intern)**, Design & Simulation Technologies (DSTECH) — Eskişehir · *Feb 2026–present*
Mesh-independence and ASME V&V20 verification (GCI = 2.7%) on a model cruise-missile geometry
using OpenFOAM/SALOME; local Mach>1 / shock structure analysis; kerosene–oxygen reacting-flow
combustion analysis (`reactingFoam`); Python-automated parametric CFD sweeps for data-center
cooling with ASHRAE A1 compliance assessment; Bash automation for SALOME→OpenFOAM mesh
pipelines; acceptance test procedures (ATP) for pressurized tanks and ignition systems.

**Intern**, TÜBİTAK National Observatory (TUG) — Electrical-Electronic Maintenance Unit, Antalya · *Jan–Feb 2026*
Technical support for telescope systems and observatory infrastructure maintenance; Arduino-based
interface development with environmental sensor integration.

**Intern**, TÜBİTAK SAGE — Advanced Rocket Propulsion Systems, Ankara · *Jul–Sep 2024*
Built a lateral-thrust performance tool from scratch (Excel/VBA); modeled the effect of nozzle
surface roughness on boundary-layer thickness and specific impulse (Isp); validated against 2D
axisymmetric CFD in ANSYS Fluent.

## 🎓 Education

**B.Sc. Aerospace Engineering** — Necmettin Erbakan University, Konya · 2021–2026 · GPA 3.19/4
Coursework: Propulsion Systems, Thermodynamics, Heat Transfer, Fluid Mechanics, Aerodynamics,
Compressible Aerodynamics, CFD, Mechanics of Materials, Statics, Materials Science, Embedded
Systems, Satellite Communication Systems.

## 🛠️ Technical Skills

| Area | Tools |
|---|---|
| **CFD** | OpenFOAM (`reactingFoam`, `simpleFoam`, `interFoam`), ANSYS Fluent, SALOME, GCI/ASME V&V20, RANS (k-ω SST), conjugate heat transfer, reacting flow |
| **FEA** | ANSYS Mechanical, LS-DYNA (dynamic impact), static/modal/fatigue analysis, factor-of-safety |
| **Propulsion & Thermo** | NASA CEA, RPA, Flownex SE (1D–0D), nozzle performance, combustion chamber design |
| **System Modeling** | Simscape, Simulink, OpenRocket, digital twin |
| **Programming** | Python (NumPy, Pandas, Matplotlib), MATLAB, C/C++, Bash, LaTeX |
| **CAD/CAE** | SolidWorks, ANSYS SpaceClaim, ANSYS Discovery |
| **Test & DAQ** | LabVIEW, DAQ/sensor integration, Arduino, RSSI/telemetry |

## 🚀 Open-source CFD portfolio

All built with OpenFOAM, validated where literature/benchmark data exists.

| Repository | Study |
|---|---|
| [cht-multiregion-openfoam](https://github.com/serhatcanaerospace/cht-multiregion-openfoam) | Multi-region conjugate heat transfer + literature replication (fin effectiveness) |
| [fin-heatsink-cfd-screening](https://github.com/serhatcanaerospace/fin-heatsink-cfd-screening) | 7-topology finned heat-sink screening study |
| [savonius-rotor-openfoam-ami](https://github.com/serhatcanaerospace/savonius-rotor-openfoam-ami) | Savonius VAWT rotor, AMI/sliding-mesh (Cm/Cp) |
| [savonius-mrf-angle-screening](https://github.com/serhatcanaerospace/savonius-mrf-angle-screening) | Same rotor, MRF/frozen-rotor multi-angle sweep |
| [naca0012-openfoam-validation](https://github.com/serhatcanaerospace/naca0012-openfoam-validation) | NACA0012 validation against NASA TMR |
| [ahmed-body-openfoam-aero](https://github.com/serhatcanaerospace/ahmed-body-openfoam-aero) | Ahmed body external aerodynamics |
| [battery-cold-plate-cht-openfoam](https://github.com/serhatcanaerospace/battery-cold-plate-cht-openfoam) | EV battery cold-plate conjugate heat transfer |
| [pcm-melting-openfoam](https://github.com/serhatcanaerospace/pcm-melting-openfoam) | Phase-change-material melting benchmark |
| [solar-chimney-openfoam](https://github.com/serhatcanaerospace/solar-chimney-openfoam) | Solar chimney natural convection |
| [cyclone-separator-openfoam](https://github.com/serhatcanaerospace/cyclone-separator-openfoam) | Cyclone separator swirling flow |

## 🛰️ Other projects

- [Rocket Simulation Project (via RocketPy)](https://github.com/serhatcanaerospace/Rocket-Simulation-Project-via-RocketPy) — Cesaroni motor flight simulation + a standalone liquid/solid rocket engine design tool.
- [Satellite Orbit Simulation](https://github.com/serhatcanaerospace/satellite-orbit-simulation) — MATLAB TLE processing, 3D orbit visualization, perturbation and collision-risk analysis.

**Not yet public:**
- Liquid rocket engine + test stand (JP-8/GOX): conceptual design, ANSYS Fluent combustion/CHT
  analysis, NASA CEA cross-validation, ANSYS Mechanical structural verification (FoS @ 1.5×),
  Simscape/Flownex SE digital-twin modeling — senior thesis, 2026.
- Nozzle surface-roughness effect on specific impulse — analytical + CFD study, TÜBİTAK SAGE, 2024–2025.
- LoRaWAN-based satellite telemetry prototype (~2 km range) — 2025.
- 3D-printed TPU honeycomb geometries under high-speed impact, LS-DYNA + experimental validation — TÜBİTAK 2209-A, ongoing.

## 📄 Publications

- *Model Cruise Missile Transonic CFD Analysis: Aerodynamic Characterization and Mesh
  Independence Verification* — HAVÖS 2026, Necmettin Erbakan University.
- *Parametric CFD Analysis of Thermal Performance and Energy Efficiency in Data Centers* —
  HAVÖS 2026, Necmettin Erbakan University (25-scenario Python-automated sweep, ASHRAE A1
  compliance, RCI_lo = 22.4%).

## 🏆 Competitions

- **TEKNOFEST B3 Liquid Rocket Engine**, Propulsion Team — *MagneThrust* (2024–25): injector
  concept design, CFD-assisted atomization/mixing analysis.
- **TEKNOFEST B3 Liquid Rocket Engine**, Propulsion Team — *PALTİ2DE* (ongoing): subsystem
  detail design, CFD/FEA, component acceptance testing — **1st place, Turkey**.
- **TEKNOFEST High-Altitude Rocket**, Aerodynamics Team — *KAPSÜL BOZDOĞAN* (ongoing): CFD-FSI
  analysis, flight simulation, aerodynamic stability.
- **IREC**, Aerodynamics Team — *KAPSÜL BOZDOĞAN* (ongoing): airframe CFD, flight-profile
  optimization, successful launch and recovery.
- **TEKNOFEST Satellite-on-the-Move Terminal**, Team Lead — *Kapsül Atlas* (ongoing):
  laser-based target tracking, two-axis stabilization, Stewart-platform kinematics.

---

📬 **Contact:** [serhatcandalmis@gmail.com](mailto:serhatcandalmis@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aerospace-eng-serhatdalmis/)

![Serhat's GitHub Stats](https://github-readme-stats.vercel.app/api?username=serhatcanaerospace&show_icons=true&theme=radical)
