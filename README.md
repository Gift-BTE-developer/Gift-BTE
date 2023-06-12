# Gift-BTE

## What is Gift-BTE 
Gift-BTE is a powerful tool designed to investigate submicron heat conduction. At the submicron scale, the characteristic length of heat conduction becomes comparable to the phonon mean free path, rendering the macroscopic Fourier's law inapplicable. Instead, at this scale, the phonon Boltzmann transport equation accurately describes heat conduction. Gift-BTE employs numerical methods to solve this equation and simulates submicron heat conduction. It takes phonon properties from first-principles simulations as input and provides a built-in database for some materials. Additionally, Gift-BTE offers an interface with two external unstructured mesh generators and provides several examples. The tool is easy to use, as it only requires an environment with g++, MPI, and Cmake.

## Features
### General
- Deterministic solver of phonon Boltzmann transport equation
- Applicable to any crystalline materials and structures
- Applicable to steady-state and transient problem
- Interface to ShengBTE, ALAMODE, GMSH, COMSOL, and Paraview packages
- Mainly written in C++, parallelized in MPI

### Application
- Computing thermal conductivity of nanostructures such as nano-porous media, superlattice, nanowires, nano-composite
- Predicting temperature rise in transistors
- Simulating laser heating process
- Other submicron heat conduction problems

## Workflow
![method-figure1](https://github.com/Gift-BTE-developer/Gift-BTE/assets/133620758/86174800-9b5c-4b00-9fab-a4643f14727f)

## Links
- Documentation: https://sjtu.feishu.cn/docx/GzB2dXQfaozenFxEtP4cQEJOnKb
- Git repository: https://github.com/Gift-BTE-developer/Gift-BTE.git
