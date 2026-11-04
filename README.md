# Tommaso Lanzini

I am a MSc student in Aerospace Engineering, specializing in Space Systems Engineering at TU Delft. My research focuses on fault-tolerant embedded design, radiation transport physics, and the enablement of resilient orbital computing through GPGPU accelerators and neuromorphic artificial intelligence. My methodology integrates Monte Carlo simulations, hardware-in-the-loop validation, and systems engineering to ensure reliability in extreme environments.

## Public Projects

### 1. NVBitFI_for_ODC
*Architecture-level fault injection tool for GPU application resilience evaluation - ONGOING*.
Developed in Python as part of my MSc thesis research, this project is designed to classify radiation-induced faults on GPUs in orbit. It utilizes a hybrid architecture that integrates software-based fault injection campaigns with hardware RAS telemetry, allowing for subsystem-level vulnerability mapping and the identification of diagnostic blind spots.

### 2. Act_Magnetic_Shielding
*Active magnetic shielding analysis for spacecraft - ONGOING*.
A research project developed in Python and C++ for the TU Delft Honours Programme. It features data analysis pipelines and Geant4 Monte Carlo simulations to model the Jovian radiation environment, evaluating the efficacy of custom magnetic field topologies (such as dipoles and Field Reversed Arrays) in deflecting high-energy particles to protect silicon avionics from Total Ionizing Dose (TID).

### 3. SEE
*Testing and design for Single Event Effects mitigation on COTS mass memory - Group project*.
Developed in C, this project focuses on the design and testing of a 64 GB Flash memory subsystem for a LEO CubeSat. It incorporates logic implementations for memory scrubbing and Error Detection and Correction (EDAC, utilizing BCH and CRC) to mitigate Single Event Upsets (SEU), with its performance empirically validated via hardware-in-the-loop fault injection across millions of words.

### 4. SNNforDOCKING
*Spiking Neural Network (SNN) for spacecraft pose estimation*.
A Python implementation (using PyTorch and snnTorch) of a convolutional SNN for 6DoF spacecraft pose estimation, utilizing sparse data from a DVS event camera. The repository includes an Artificial Neural Network (ANN) to SNN transfer learning pipeline and a Monte Carlo simulator for SEU injection, verifying the superior fault tolerance of SNNs over standard ANNs in aerospace applications.

### 5. SpecialTopicsOfAstrodynamics
*Hybrid chemical/solar-sail Earth-Mars trajectories (MIMOSA project)*.
A Python codebase developed for orbital dynamics modeling and Jacobian eigenvalue analysis within the Circular Restricted Three-Body Problem (CR3BP) for the Sun-Earth and Sun-Mars systems. It optimizes interplanetary transfers by minimizing $\Delta V$ through the propagation of invariant manifolds and the adjustment of solar sail cone angles.

### 6. Smart_battery
*Control system and fault mitigation for smart batteries - Group project*.
A C++ framework utilizing Arduino R4 for the real-time monitoring of voltage, current, and temperature. It integrates hardware safety mechanisms using MOSFETs, software routines for fault tolerance, and a State-of-Charge (SoC) estimation augmented by machine learning algorithms.
