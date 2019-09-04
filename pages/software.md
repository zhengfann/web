---
layout: page
title: Research
description: Fan Zheng's research
---

### [Non-adiabatic molecular dynamics (NAMD)](https://bitbucket.org/zhfan_dertba/namd_basic/)

NAMD is a post-process-type simulation, it uses classical path approximation 
to simulate carrier's motion, including hot carrier's cooling by electron-phonon 
coupling. Before running this program, an *ab initio* molecular dynamics is 
performed by computing adiabatic states' overlapping between two MD steps. 
NAMD will use the overlapping values to re-construct Hamiltonian and simulate 
carrier dynamics. For now, only PWmat MD is implemented. Soon, we will have 
[QE](https://www.quantum-espresso.org/) support. See details 
[here](https://bitbucket.org/zhfan_dertba/namd_basic/)



### [Genetic Algorithm to find global minimum structure (GA)](https://bitbucket.org/zhfan_dertba/ga_algorithm/)
