## Description
This was a college project where I trained and compared double Q learning and standard Q learning reinforcement models using Frogger for the Atari as the environment.
## Installation and Running Code
doubleProject.ipynb contains my training code, results, and short form analysis.
A conda environment with the necessary packages to run the notebook can be created with the environment.yaml file in this repository:
```bash
conda env create -f environment.yaml
conda activate rl-env
```
You might want to remove pytorch-cuda if you don't have an NVIDIA GPU!
The yaml will also automatically agree to the license for Atari ROMs if used!