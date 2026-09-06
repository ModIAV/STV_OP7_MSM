# STV_OP7_MSM

This code implements a multiscale model of influenza A virus (IAV, also referred to as standard virus (STV)) and OP7 coinfection developed at the MPI Magdeburg. This model is an extension/combination of a multiscale model of IAV and defective interfering particle (DIP) co-infection [1], and an intracellular model of STV and OP7 coinfection [2]. The current model version will be documented in [3]. 

## References
1. Rüdiger D, Pelz L, Hein MD, Kupke SY, Reichl U. Multiscale model of defective interfering particle replication for influenza A virus infection in animal cell culture. PLoS Comput Biol. 2021 Sep 7;17(9):e1009357. doi: 10.1371/journal.pcbi.1009357.
2. Rüdiger D, Piasecka J, Küchler J, Pontes C, Laske T, Kupke SY, Reichl U. Mathematical model calibrated to in vitro data predicts mechanisms of antiviral action of the influenza defective interfering particle "OP7". iScience. 2024 Mar 5;27(4):109421. doi: 10.1016/j.isci.2024.109421.
3. TBD

## Requirements
- MATLAB (MathWorks, Inc.)

- IQM Toolbox for MATLAB by Schmidt and Jirstrand (Bioinformatics, 2006), available at https://iqmtools.intiquan.com/main.html

- C/C++ compiler: Creates MEX-files for a faster simulation with the IQM Toolbox (e.g. MinGW 6.3 C/C++ for Windows or GCC for Linux)

## Optional programs (for faster simulation)
- CVODE solver from SUNDIALS: Simulates MEX-files. Cohen and Hindmarsh (Computers in Physics, 1996), available at https://computing.llnl.gov/projects/sundials/sundials-software

## Running the code
The function `STV_OP7_CoinfectionModel_Main.m` is used for model simulation. 

## Contributors
The code base was written by Stefan Heldt. Code and model extension was performed by Daniel Rüdiger. Initial works on the intracellular OP7 and IAV coinfection model were performed by Tanja Laske and Carolina Pontes.

## Citation
If you use this code, we ask you to cite the appropriate papers in your publication.
