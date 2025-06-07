# Bidirectionally Stacking Loudspeaker Enclosure for Wave Field Synthesis

An open-source, modular loudspeaker enclosure system for Wave Field Synthesis (WFS), developed at the Studio for Research in Sound and Technology (SRST) at Rhode Island School of Design (RISD).

This design supports both classroom and performance applications, and allows users to fabricate enclosures either manually or with a CNC, enabling fabrication across a range of workshop environments.

---

## Overview

This repository contains full open-source designs, hardware files, and documentation for constructing WFS loudspeaker arrays.

The system supports:
- Modular stacking in horizontal and vertical configurations
- 1-tier, 3-tier, and alternate versions
- Easily fabricated parts using standard fabrication tools or CNC
- Adaptability for student projects, research, and live performances

*Note: Alternate versions are provided for experimentation and may not have undergone full acoustic testing.*

---

## Repository Structure

- `/1_tier/` — Files for the single-tier loudspeaker enclosure:
  - `/PDF/` — Full-scale templates for manual cutting (table saw, track saw, drill press, etc.)
  - `/DXF/` — CNC-ready files for digital fabrication
  - `/STL/` — 3D-printable speaker component files (front/back pieces)
  - `/IMAGE/` — Reference build images

- `/3_tier/` — Files for the 3-tier stacked enclosure:
  - Same subfolders: `PDF/`, `DXF/`, `STL/`, `IMAGE/`

- `/alt_version/` — Alternative experimental designs:
  - Same subfolders: `PDF/`, `DXF/`, `STL/`, `IMAGE/`

- `/parts/` — Full Bill of Materials (BOM) for speaker components and cabinet hardware.

---

## Fabrication Methods

**Manual Fabrication**

- Use files in the `PDF` folders.
- Full-scale printouts can be applied directly to the plywood surface.
- Recommended tools: table saw, track saw, drill press, handheld router.

**CNC Fabrication**

- Use files in the `DXF` folders.
- Compatible with standard CAM software and CNC routers/laser cutters.

**3D Printing**

- Use `STL` files to fabricate speaker mounting hardware and front/back enclosures.
- Compatible with standard FDM printers (0.4mm nozzle recommended).

---

## Materials

- **Plywood**: Baltic Birch B/BB grade, 12mm thickness  
  *Note: Baltic Birch is typically supplied in 60" x 60" (1524mm x 1524mm) sheets. Verify sheet dimensions when ordering to ensure cutting layouts are compatible.*

- **Speakers**: 2" Tang Band drivers (T2-2136SG)  
  *Note: The T2-2136SG was custom manufactured to 8 Ohms. It shares the same dimensions as the 4 Ohm T2-2136SF model.*
- **Amplification**: Multi-channel Dante amplifiers (e.g. QSC 16-channel)
- **3D Printing**: STL files provided for speaker unit fabrication
  *Parts were printed using PLA filament on standard FDM printers (0.4mm nozzle recommended).*
- **Hardware Summary**: threaded rods, inserts, banana plugs, fasteners, speaker wiring


> The full hardware Bill of Materials (BOM), including part numbers, quantities, and sourcing information, is provided in the `/parts/` folder as separate cabinet and speaker BOM files. Pricing is not included, as component costs fluctuate over time and based on availability.

---

## Licence

This project is licensed under the CERN Open Hardware Licence Version 2 - Permissive (CERN-OHL-P v2).

You are free to:

- Use
- Modify
- Manufacture
- Distribute

…for any purpose (commercial or non-commercial), provided attribution is maintained and liability is disclaimed.

Full licence text:  
https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2

---

## Contributing

We welcome contributions from researchers, students, and educators.

- Please see `CONTRIBUTING.md` for submission guidelines.
- All contributions will be licensed under CERN-OHL-P v2.

---

## Contact

For questions, feedback, or collaboration enquiries, please contact:

**sound@risd.edu**


More information:

- Studio for Research in Sound and Technology (SRST): [SRST](https://sound.risd.edu)
- Rhode Island School of Design: [RISD](https://www.risd.edu)

---

## Authors

- Alex A. Chechile, PhD
- Stephen Cooke
- Will Johnson
- Shawn Greenlee, PhD

---

## Acknowledgements

We would like to thank our Research and Technical Assistants for their help with fabrication and assembly:

- Ada Wu
- Huichun Yang
- Nick Sadler

This work was inspired by the EMPAC system developed at Rensselaer Polytechnic Institute.

Original WFS mathematical models: Berkhout, de Vries, Vogel — *The Journal of the Acoustical Society of America*, 1993.

---
