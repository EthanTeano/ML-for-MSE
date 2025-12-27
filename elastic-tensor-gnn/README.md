# Elastic Tensor Prediction with Equivariant GNNs

This project is a learning-focused, independent reimplementation of a
MatTen-style SO(3)-equivariant graph neural network for predicting the
full rank-4 elastic stiffness tensor of crystalline materials from
atomic structure.

The purpose of this work was to gain hands-on understanding of
symmetry-aware graph neural networks, tensor-valued regression, and
the practical challenges involved in implementing equivariant models
for materials science applications.

## Background
Elastic tensor prediction from first principles (DFT) is accurate but
computationally expensive. Prior work, such as the MatTen framework,
demonstrates that equivariant neural networks can learn tensor-valued
materials properties while respecting rotational symmetry.

## What Was Implemented
- Construction of atomic graphs from crystal structures
- SO(3)-equivariant message passing
- Tensor-aware readout preserving rotational covariance
- End-to-end training pipeline for elastic tensor prediction

## Data
- Elastic tensor labels derived from Density Functional Theory (DFT)
- Dataset constructed to mirror those used in the MatTen paper,
  primarily sourced from Materials Project calculations

## Scope and Limitations
- Implemented as a learning exercise rather than a formal reproduction study
- Focused on understanding model structure and symmetry constraints
- Performance metrics were not the primary objective

## Status
Completed as a learning exercise; potential extensions left for future work
