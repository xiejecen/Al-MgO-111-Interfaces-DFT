# Al(111)-MgO(111)-Interfaces-DFT
DFT input files and data for interfacial energy, charge transfer, and fracture behavior of Al/MgO(111) interfaces
# Al(111)/MgO(111) Interfaces: First-Principles Calculations

This repository provides density functional theory (DFT) input files and data supporting the study of Al/MgO(111) interfaces with different surface terminations. The data are associated with the manuscript:

**"First-Principles Study of the Polar MgO(111)/Al(111) Interface: Adhesion, Stability, and Electronic Structure"**  
submitted to *Computational Materials Science*.

The calculations focus on the thermodynamic stability, electronic structure, charge transfer behavior, and interfacial fracture mechanisms of Al/MgO(111) interfaces.

---

## Repository Structure

The data in this repository are organized into three main parts following the computational workflow of the study: surface calculations, interface modeling, and tensile deformation simulations.


---

## Surface Calculations

The `Surface/` directory contains slab models and calculation data for the polar MgO(111) surface, which serve as structural and thermodynamic references for interface construction.

Two surface terminations were explicitly considered:

- **111OT**: O-terminated MgO(111) surface  
- **111MT**: Mg-terminated MgO(111) surface  

These surface calculations were used to account for the polarity of the MgO(111) surface, constrain the chemical potentials of Mg and O under Mg-rich and O-rich conditions, and ensure thermodynamic consistency in the interfacial energy analysis.

---

## Interface Calculations

The `Interface/` directory contains data for six Al/MgO(111) interface configurations constructed from the corresponding surface terminations:

- O-terminated interfaces: OT-Hollow, OT-MT, OT-OT  
- Mg-terminated interfaces: Mg-Hollow, Mg-MT, Mg-OT  

Subdirectories include:

- `Structure/`: Optimized atomic structures of all interface models.
- `DOS/`: Density of states data used to analyze the electronic structure and bonding characteristics at the interface.
- `Charge_difference/`: Charge density difference data visualizing interfacial charge redistribution upon interface formation.
- `Bader/`: Bader charge analysis results quantifying the direction and magnitude of charge transfer across the interface.

These data support the analysis of termination-dependent bonding nature (ionic/covalent versus metallic) and interfacial adhesion behavior.

---

## Tensile Deformation and Fracture Analysis

The `Tensile/` directory contains uniaxial tensile deformation calculations applied normal to the interface to investigate interfacial fracture behavior.

Representative interface models, including **MgT-Hollow** and **OT-OT**, were selected for tensile loading. The evolution of charge density distribution, atomic bonding, and electronic structure under increasing strain was analyzed to elucidate the atomistic mechanisms governing interfacial fracture and failure.

---

## Computational Details

All calculations were performed using the Vienna *ab initio* Simulation Package (VASP) within the framework of density functional theory (DFT).

- Exchange–correlation functional: GGA-PBE  
- Plane-wave basis set  
- Periodic slab models  

Due to licensing restrictions, VASP `POTCAR` files are not included in this repository. The pseudopotentials used for Al, Mg, and O are documented in the manuscript.

---

## Data Reproducibility

The data provided in this repository are sufficient to reproduce the main results reported in the manuscript, including:

- Surface stability and termination effects
- Interfacial energies and adhesion behavior
- Charge transfer and bonding characteristics
- Strain-dependent electronic evolution and fracture mechanisms

---

## Citation

If you use the data or structures from this repository, please cite the corresponding article:

> [Authors], *Computational Materials Science*, [Year].  
> DOI: to be added after publication.

---

## Contact

For questions regarding the data or calculations, please contact:

**JiachenXie**   
**Email:** xie-jia-chen@outlook.com
