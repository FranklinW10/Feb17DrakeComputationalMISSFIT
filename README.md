# MISSFIT — Magneto-Ionization Spacecraft Shield for Interplanetary Travel

## Overview
A central issue concerning manned interplanetary travel is the intense radiation 
exposure from solar wind and galactic cosmic rays (GCRs). MISSFIT is an 
interdisciplinary student-led collaboration whose goal is to produce a conceptual 
design of a magnetic shielding system that would protect the crew from this 
dangerous radiation.

## Computational Subgroup
The purpose of the computational subgroup is to model the interaction of 
relativistic charged particles with the ionization gas chambers and 
dipole-induced magnetic field of the spacecraft. Higher energy particles are 
deflected by the magnetic field, while lower energy particles spiral into the 
poles and are trapped in the ionization chambers, reducing their velocities 
and energy significantly.

## Input Files
3 input files are created and read by the simulation, a magnetic feild file, energy loss file, and a particle/radiation file
- **Magnetic Field Generation**: Successive over-relaxation method used to 
  approximate the magnetic field by solving the Laplace equation under 
  specified boundary conditions
- **Radiation Data**: Large radiation datasets obtained from SOHO and ACE 
  data repositories fed into a Monte Carlo model and relativistic tracking code
- **Energy Loss**: Ion-gas interactions simulated using charged particle 
  energy loss data from SRIM

## Results
Our results demonstrate the effectiveness of our methods in mitigating 
spacecraft radiation damage. Our end goal is to minimize magnetic field 
strength, conserving energy and optimizing overall mass, while ensuring 
the safety of the spacecraft and crew.

## Technologies
- C
- Fortran
- SRIM
- SOHO/ACE data repositories

## Contributors
A collaborative research project at Drake University.
