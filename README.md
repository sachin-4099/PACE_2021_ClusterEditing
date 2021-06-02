# CLIP: Cluster Editing PACE 2021 (Exact Track)

This repository contains an exact solution to the cluster editing problem.

The program is submitted to the [PACE Challenge 2021](https://pacechallenge.org/2021/).

The cluster editing problem consists of removing or inserting as few edges to an undirected graph to obtain a graph where every connected component is a clique.

## Compilation & Usage

To run:

```
pip install pulp
python3 clip.py
```

## Description
We convert the cluster editing problem into an integer linear program (ILP) using [1]. We use an open source ILP solver CBC (https://github.com/coin-or/Cbc) to solve the ILP formed in the previous step.  



1. L. H. N. Lorena, M. G. Quiles, A. C. P. L. F. Carvalho, and L. A. N. Lorena: Preprocessing Technique for Cluster Editing via Integer Linear Programming, Intelligent Computing Theories and Application, pp.287-297, 2018.
