# Optimal Planning of Standalone Net-Zero Energy Systems With Small Modular Reactors
*This work propose a standalone net-zero energy system planning scheme that coordinates SMRs with other distributed energy resources.*

Codes for "Optimal Planning of Standalone Net-Zero Energy Systems With Small Modular Reactors"
 *(https://doi.org/10.1109/TSG.2024.3365614)*

Authors: Mingyu Huang, Xueyuan Cui, Ning Zhang, Mengshuo Jia, Yi Wang

## Requirements

python version: 3.8.10

The must-have packages can be installed by running
```
pip install requirements.txt
```
## Experiments
### Data
*Data storage*

All the data for experiments are saved in ```../data```. 

### Reproduction

To reproduce the experiments in the paper, please refer to the detailed ```README.md``` in the following folders.

#### Centralized optimization
Results serve as the benchmark for VPP's decision-making.

#### Distributed optimization
Results show the concergence for the distributed scheme.

#### Distributed differentially private optimization
Results show the impact of the added noise in dual variable.
