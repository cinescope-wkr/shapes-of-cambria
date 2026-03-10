# Shapes of Cambria: The Cambrian Explosion in Silico

Official repository for *Shapes of Cambria*, a research project on co-optimizing vision, embodiment, and control as a computational and aesthetic medium.

The project combines differentiable optics, embodied agents, reinforcement learning, and human-in-the-loop selection to study how optical systems can evolve beyond task optimization toward expressive image formation and perceptual artifacts.

## Status

This repository currently contains the official project materials and the scaffold for the accompanying code release. The research codebase is being prepared around an integration of the Cambrian reinforcement-learning framework for MuJoCo-based vision-and-control experiments.

## Planned Integration

The code release is intended to build on **Cambrian: Co-Optimizing Vision and Control in MuJoCo**, a forked research framework derived from [Artificial Cambrian Intelligence (ACI)](https://github.com/cambrian-org/ACI).

The integrated codebase is expected to provide:

- MuJoCo environments for embodied vision-and-control experiments
- Hydra-based experiment composition and override workflows
- PPO-based training and evaluation pipelines
- Optics-aware eye models and morphology parameters
- Evolutionary or search-based optimization over visual front-end parameters

## Repository Structure

- `model/`: integrated research codebase and reproducibility materials
- `configs/`: experiment configuration files
- `scripts/`: launch and utility scripts
- `docs/`: paper, figures, and project media assets

## Planned Code Layout

- `model/src/`: core library code
- `model/train.py`: training entry point
- `model/infer.py`: inference or rendering entry point
- `configs/`: experiment configuration files
- `scripts/`: helper utilities for setup, preprocessing, and evaluation

## Attribution

The planned Cambrian integration is based on the ACI project and its downstream fork structure. This repository is maintained by Jinwoo Lee.

## Asset Note

Large checkpoints, datasets, and long renders should be distributed outside git when possible.
