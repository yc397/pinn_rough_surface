# Implementations of PINN to reconstruct rough surfaces

The repository contains the codes of physics-informed neural network (PINN) for reconstructing 1D rough srufaces.

There are two folders corresponding to two types of waves (TE and TM); in each folder.
For each type of wave, two cases are considered:

case A: reconstruction with full scattered data

case B: reconstruction with phaseless total field data

A standard code includes two parts:

(i) The data generation with creating rough surface, method of moments and interpolation

(ii) PINN for the inverse problem

To run the code, one has to generate data first (i) and then run PINN code.

These codes requires the PyTorch 2.0.0.
