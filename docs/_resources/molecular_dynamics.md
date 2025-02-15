---
title: Molecular Dynamics
layout: page
permalink: /ml-learning/
---

## A great overview of Molecular Dynamics.
[Best Practices for Foundations in Molecular Simulations](https://livecomsjournal.org/index.php/livecoms/article/view/v1i1e5957)


### OpenMM tutorials
[openmm-tutorial-msbs](https://github.com/molmod/openmm-tutorial-msbs)  
[OpenMM tutorials](https://openmm.github.io/openmm-cookbook/dev/tutorials.html)

### If you want to use OpenMM in Colab copy this cell and run

## First Cell
!pip install -q condacolab
import condacolab
condacolab.install()

## Second Cell. Get rid of nglview from cells down
%%capture
!conda install -c conda-forge openmm mdtraj 