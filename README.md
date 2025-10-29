# Huertas_2025_Oct4
Source Code for the paper 'Oct4 clusters promote DNA accessibility by enhancing chromatin plasticity'

We are delighted to share our model for chromatin phase separation and analysis scripts with the community. Please use it freely and cite our paper: preprint https://www.biorxiv.org/content/10.1101/2025.10.20.683403v1

For questions, contact Jan Huertas: jh2366[at]cam.ac.uk

## Installation Guide
For compiling the chromatin multiscale model, please follow the instructions in https://github.com/CollepardoLab/CollepardoLab_Chromatin_Model

## Usage
The files needed to run a typical simulation from the paper are in the demo folder.
Please download the whole folder, and run using at least 16 cores, for example:
```
mpirun -np 16 ./lmp -in run.in
```

## Visualization
We recommend using OVITO (https://www.ovito.org/) or VMD (https://www.ks.uiuc.edu/Research/vmd) for visualising the trajectory.
