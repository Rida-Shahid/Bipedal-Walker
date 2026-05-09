# Bipedal Walker Agent using SAC

## Overview
This project trains a reinforcement learning agent to solve the BipedalWalker environment using the Soft Actor-Critic (SAC) algorithm.

The implementation is built using:
- Gymnasium
- Stable-Baselines3

## Environment
- Environment: `BipedalWalker-v3`
- Version: Normal environment (non-hardcore)

## Algorithm
- Soft Actor-Critic (SAC)

## Hyperparameters
The hyperparameters were selected based on values reported in the following paper:

[Comparative Analysis of Reinforcement Learning
Algorithms for Bipedal Robot Locomotion](https://escholarship.org/content/qt49q760h0/qt49q760h0_noSplash_f92cb43ac9c83fb68c6ec654f760ea27.pdf)

Key parameters include:
- Learning rate = 2.52e-3
- Discount factor (γ) = 0.96667
- Polyak update coefficient (τ) = 1.68e-1

The reproduced training results showed reward and convergence behavior comparable to the paper.

## Training Results
The trained agent successfully learned stable walking behavior in the environment.

Final trained agent demonstration:

![Agent Demo](final_agent.gif)

## Libraries Used
- Gymnasium
- Stable-Baselines3
- PyTorch
- NumPy
- Matplotlib

## Run the Project
1. Download the notebook.
2. Install required libraries.
3. Execute each notebook cell sequentially.

## Files
- `bipedal_walker_sac.ipynb` — Training and evaluation notebook
- `final_agent.gif` — Final trained agent demonstration

## Notes
This project was developed as part of a Deep Reinforcement Learning coursework/project.
