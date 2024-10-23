# LMMCoDrive: Cooperative Driving with Large Multimodal Model

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/henryhcliu/LMMCoDrive/blob/main/LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0-brightgreen)](https://github.com/henryhcliu/LMMCoDrive/releases/tag/v1.0)
[![arXiv](https://img.shields.io/badge/arXiv-2409.11981-lightgrey)](https://arxiv.org/abs/2409.11981)

This repository contains the code implementation for the paper titled **LMMCoDrive: Cooperative Driving with Large Multimodal Model** by Haichao Liu, Ruoyu Yao, Zhenmin Huang, Shaojie Shen, and Jun Ma.

## Abstract

To address the challenges of decentralized cooperative scheduling and motion planning in Autonomous Mobility-on-Demand (AMoD) systems, this paper introduces LMMCoDrive, a novel cooperative driving framework that utilizes a Large Multimodal Model (LMM) to enhance traffic efficiency in dynamic urban environments.
![image](https://github.com/user-attachments/assets/89097418-896e-47f0-915a-d1890d3d83e9)

## Code Implementation

The code in this repository accompanies the research paper and includes the following key components:

- **Scheduling and Motion Planning Integration**: The code integrates scheduling and motion planning processes for Cooperative Autonomous Vehicles (CAVs).
  
- **Decentralized Optimization Algorithm**: Utilizes the Alternating Direction Method of Multipliers (ADMM) within the LMM framework for graph evolution to drive the cooperative motion planning of CAVs.

- **Simulation and Experimental Results**: Demonstrates the effectiveness of LMMCoDrive in optimizing CAV scheduling and enhancing cooperative driving tasks in CARLA 0.9.14.

## Usage

To use the code in this repository, follow these steps:

1. Clone the repository: `git clone https://github.com/henryhcliu/LMMCoDrive.git`
2. Create a new Conda environment (`Python 3.8` is recommended) and activate it.
3. Install the necessary dependencies by `pip install -r requirements.txt`
4. Run the CARLA simulator in the Terminal using `./CarlaUE4.sh` in the corresponding CARLA folder to launch the server
5. Run the main script by `python main_lmmcodrive.py` to see the implementation in action.

## Citation

If you find this code or research paper helpful, please consider citing:
```
@article{liu2024lmmcodrive,
  title={LMMCoDrive: Cooperative Driving with Large Multimodal Model},
  author={Liu, Haichao and Yao, Ruoyu and Huang, Zhenmin and Shen, Shaojie and Ma, Jun},
  journal={arXiv preprint arXiv:2409.11981},
  year={2024}
}
```
For more details, refer to the paper available [here](https://arxiv.org/pdf/2409.11981).

For any questions or issues regarding the code, feel free to open an issue in this repository.
