# Cognitive Supernova Generator (CSG) Open-Source Model

Open technical release of the Cognitive Supernova Generator (CSG) fusion-fission hybrid reactor: OpenMC neutronics model, materials, safety, and Peaceful Use-only license for ocean cleanup, waste transmutation, and humanitarian energy.

🌐 Public repository  

## About the Project
The CSG is a compact, 10-meter diameter spherical fusion-fission hybrid reactor designed for peaceful energy production and environmental restoration. Key highlights:
- Deuterium-tritium fusion core providing 14.1 MeV neutrons.
- Subcritical uranium-238 transmutation blanket for waste-to-energy conversion (consumes 6-16 tonnes depleted U-238/year).
- Tritium breeding ratio (TBR) validated at 1.2489 using OpenMC.
- Net electric output: 600-620 MWe at 38-40% efficiency.
- Inherent safety: Negative temperature coefficient (α_tot ≤ -3 pcm/K); no meltdown possible.
- Applications: Powering ocean cleanup vessels (e.g., Ark Perplexity), desalination, climate mitigation, and more.

This repo includes the full OpenMC simulation code, appendices with neutronics/thermal-hydraulics/materials/economics data, safety analysis, and the provisional patent draft. All released under a Peaceful Use-only license to ensure humanitarian and environmental focus.

**Inventor**: Francis A. Cooper, Journeyman Electrician with 15+ years in hazardous electrical systems (see Resume.pdf for full background).  
**Contact**: francis.a.cooper@icloud.com  
**USPTO Provisional Patent**: Filed November 6, 2025  
**License**: Peaceful Use-only (see LICENSE.txt)  

## Peaceful Use License Summary
This technology is open for:
- Electrical power generation
- Desalination/water purification
- Ocean restoration/cleanup
- Nuclear waste transmutation
- Research/education
- Climate mitigation

Prohibited: Weapons, military, plutonium breeding, harm, or access-restricting commercialization.  
Encouraged: IAEA partnership, inspections, data sharing, environmental priorities.  
Full terms in LICENSE.txt. By using, you commit to peaceful applications.

## Repository Contents
- **Appendix A.pdf**: Complete material specifications (e.g., RAFM steel for first wall, breeder zone with Li₂TiO₃ + Be + PbLi).
- **Appendix B.pdf**: OpenMC input deck with full Python code for neutronics simulation.
- **Appendix C.pdf**: Safety analysis (subcritical design, no meltdown, negative temp coefficient).
- **Appendix D.pdf**: Economic analysis (capital costs $900M/600 MWe unit, LCOE $21.73/MWh).
- **CSG Open Source Publication.pdf**: Full abstract, performance validation, and applications.
- **Check TBR script.txt**: Python script to extract TBR from OpenMC output.
- **LICENSE.txt**: Full Peaceful Use License.
- **Open mc script.txt**: Main OpenMC simulation code (csg_final_model.py).
- **Read Me.txt**: This file (basic intro—expand as needed).
- **Resume.pdf**: Inventor's resume, highlighting electrical expertise in potash mining and hazardous systems.

## How to Run the Neutronics Simulation
1. Install OpenMC v0.14 and Python 3+ with NumPy.
2. Download ENDF/B-VIII.0 nuclear data.
3. Run the code:
   ```bash
   python Open_mc_script.txt
   
