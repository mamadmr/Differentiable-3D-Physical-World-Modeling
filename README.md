# Differentiable 3D Physical World Modeling

## Problem
Optimize the 3D shape of a floor surface to guide a ball from random starting positions to a target location, using differentiable physics simulation in PyTorch.

## Approach
- **Learnable Parameters**: Height map representing the floor surface
- **Physics Engine**: Differentiable layers computing ball trajectory based on velocity and position
- **Training**: Random ball initializations with multi-objective loss:
  - Distance to goal
  - Surface smoothness
  - Surface height minimization