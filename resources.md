# Datasets, Benchmarks, and Simulation Resources

This page collects datasets, benchmarks, simulators, and evaluation resources used to interpret the evidence reviewed in the manuscript.

The resources below are not themselves treated as primary ITS-LMA study families unless a qualifying foundation-model-centred system is evaluated in the corresponding study.

---

## Frozen-Corpus Evaluation Snapshot

Across the 42 primary study families, the verified principal evaluation environments include:

| Evaluation environment | Primary study families |
|---|---:|
| Offline / no interactive simulator | 14 |
| CARLA | 9 |
| Custom or other simulation | 8 |
| SUMO | 6 |
| Real-world / onboard | 2 |
| CityFlow | 1 |
| highway-env | 1 |
| MATSim | 1 |

These counts describe the principal evaluation environment assigned to each study family. They do not imply that studies using the same simulator, dataset, or environment are directly comparable.

---

## Multimodal Driving Datasets

### nuScenes

A multimodal autonomous-driving dataset used across perception and driving research.

- H. Caesar et al., **“nuScenes: A Multimodal Dataset for Autonomous Driving,”** CVPR 2020.
- [Paper](https://doi.org/10.1109/CVPR42600.2020.01164)

### Waymo Open Dataset

A large-scale autonomous-driving perception dataset.

- P. Sun et al., **“Scalability in Perception for Autonomous Driving: Waymo Open Dataset,”** CVPR 2020.
- [Paper](https://doi.org/10.1109/CVPR42600.2020.00252)

---

## Naturalistic Trajectory Data

### highD

A drone-based naturalistic highway trajectory dataset widely used for automated-driving and traffic-behaviour research.

- R. Krajewski et al., **“The highD Dataset: A Drone Dataset of Naturalistic Vehicle Trajectories on German Highways for Validation of Highly Automated Driving Systems,”** ITSC 2018.
- [Paper](https://doi.org/10.1109/ITSC.2018.8569552)

---

## Traffic Simulation

### CityFlow

A multi-agent traffic environment commonly used for large-scale traffic-signal-control research.

- H. Zhang et al., **“CityFlow: A Multi-Agent Reinforcement Learning Environment for Large Scale City Traffic Scenario,”** WWW 2019.
- [Paper](https://doi.org/10.1145/3308558.3314139)

### SUMO

A microscopic transportation simulator used extensively in traffic-control, planning, scenario-generation, and agentic simulation studies.

- P. A. Lopez et al., **“Microscopic Traffic Simulation Using SUMO,”** ITSC 2018.
- [Paper](https://doi.org/10.1109/ITSC.2018.8569938)

---

## Reasoning Benchmark

### DriveCombo

A benchmark for compositional traffic-rule reasoning in autonomous driving.

- E. Ma et al., **“DriveCombo: Benchmarking Compositional Traffic Rule Reasoning in Autonomous Driving,”** CVPR 2026.
- [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Ma_DriveCombo_Benchmarking_Compositional_Traffic_Rule_Reasoning_in_Autonomous_Driving_CVPR_2026_paper.html)

---

## Reproducibility Note

Use of the same named dataset, simulator, or benchmark does not make two studies directly comparable.

Important differences may include:

- dataset splits;
- geography and network structure;
- sensing configuration;
- scenario coverage;
- model and tool versions;
- prompts and system instructions;
- simulator configuration;
- evaluation metrics; and
- operational assumptions.

The frozen evidence map therefore records evaluation setting separately from methodological concern and claim-specific evidence.

---

## Post-Cutoff Resources

Resources identified after **3 August 2026** are recorded through the living update process and documented in [`post-cutoff-updates.md`](post-cutoff-updates.md) and [`UPDATE_LOG.md`](UPDATE_LOG.md).

---

[← Back to main repository](README.md)
