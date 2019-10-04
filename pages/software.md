---
layout: page
title: Software
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
[here](https://bitbucket.org/zhfan_dertba/namd_basic/).



### [Genetic Algorithm (GA) to find structure](https://bitbucket.org/zhfan_dertba/ga_algorithm/)

Genetic algorithm is an engine to search global minimum structure based on the 
total energy, formation energy and other quantities. Particularly, this program 
can handle multiple-molecule case (such as water) and find their most-stable arrangement 
(e.g. on a metal surface). It utilizes DFT/force-field optimization program 
and iterate generations with the evolution style. For now, this program can use [QE](https://www.quantum-espresso.org/), [VASP](), 
PWmat, and [LAMMPS]() optimization. It can search multiple-atom and -molecule cases, either 
on a surface or forming a cluster. See details 
[here](https://bitbucket.org/zhfan_dertba/ga_algorithm/).


### [Bond switching to build amorphous structure](https://bitbucket.org/zhfan_dertba/bond-switching/)

Bond switching is a package to generate amorphous AX2 or A/AX2 interface type structures (such as Si, SiO2,
or Si/SiO2 interface). The program uses Monte-Carlo and empirical force field to build the amorphous 
network and optimize the structure. See more details [here](https://bitbucket.org/zhfan_dertba/bond-switching/)

