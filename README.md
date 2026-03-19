# Semiconductor Device Fabrication & TCAD Simulation

## Overview
This repository serves as a comprehensive overview of the semiconductor engineering process.

---

## Part 1: TCAD Process Modeling & Simulation (Silvaco Deckbuild)

### 1. Resistor Design & Electrical Analysis
**Custom Serpentine Resistor Design:** Layout and simulation of a custom serpentine resistor to optimize sheet resistance within a constrained physical footprint.
<div align="center">
  <img width="484" alt="Serpentine Resistor Design" src="https://github.com/user-attachments/assets/1b40f66d-c07e-4148-be42-bf0af12d9535" />
  <img width="927" alt="Plots from serpentine resistor design" src="https://github.com/user-attachments/assets/83bd8b37-e7e3-416d-8a6d-51a6b61f8d82" />
</div>

### 2. Doping & Thermal Processing
**Drive-In Ion Implantation & Junction Depth:** Simulating dopant diffusion and analyzing the critical relationship between drive-in temperature and resulting junction depth. 
<div align="center">
  <img width="805" alt="Drive-in Ion Implantation Design" src="https://github.com/user-attachments/assets/a7cebc94-d0cc-4ca1-bc82-9f397a6a1b86" />
  <img width="1037" alt="Junction depth vs. temperature" src="https://github.com/user-attachments/assets/05c0b589-260c-435f-b0ba-399be534d624" />
</div>

### 3. Etching & Oxidation Profiles
**Etch Anisotropy & Oxide Growth:** Comparative analysis of etch profiles utilizing dry etch, barrel etching, and Monte Carlo physical simulations to evaluate undercut. Additionally, tracking the effect of various process parameters on final oxide thickness.
<div align="center">
  <img width="1214" alt="Various etching designs" src="https://github.com/user-attachments/assets/cc33c4de-09fe-4345-b0be-a3ec44c1424a" />
  <img width="315" alt="Effect of various parameters on oxide thickness" src="https://github.com/user-attachments/assets/407968bb-7d9f-4bd6-acc4-e390b0133553" />
</div>

---

## Part 2: Physical Fabrication & Metrology (CNM2 Lab)
*In this section, physical wafers were processed and analyzed, validating theoretical models through hands-on photolithography, etching, and electrical testing.*

### 1. Photolithography & Wafer Processing
**Defect Analysis & Wafer Topography:** Examining a physical wafer processed in the CNM2 Lab. The image on the left demonstrates a photolithography failure due to overexposure (13 seconds instead of the baseline 6 seconds), resulting in the catastrophic etching out of critical interconnects. 
<div align="center">
  <img width="1061" alt="Overexposed Wafer" src="https://github.com/user-attachments/assets/a1d7d11a-c8b8-4a36-a504-94c2120faf26" />
  <img width="483" alt="CNM2 Wafer" src="https://github.com/user-attachments/assets/d898ab72-87df-4bac-88bb-785aaf2e6d57" />
</div>

### 2. Metrology & Physical Measurement
**Surface Profilometry:** Utilizing a step profilometer to graze the transistor surface, verifying physical etch depths and thin-film topography against simulated expectations. 
<div align="center">
  <img width="1243" alt="Profilometer measurements" src="https://github.com/user-attachments/assets/0772f693-0673-4e22-89cd-5eef688d19ab" />
</div>

### 3. Electrical Characterization
**Device Testing:** Direct physical measurements of the fabricated transistors to extract critical electrical parameters, including I-V curves and specific contact resistance.
<div align="center">
  <img width="456" alt="Various transistors measured" src="https://github.com/user-attachments/assets/8e9d34dd-16a1-4558-be9f-105de46a9143" />
  <img width="364" alt="Electrical characterization" src="https://github.com/user-attachments/assets/3345f840-3a2b-4b98-91d1-bebbb4736e22" />
  <img width="395" alt="Contact Resistance" src="https://github.com/user-attachments/assets/8d1858fb-a394-4b58-a44a-c2382f4315fe" />
</div>
