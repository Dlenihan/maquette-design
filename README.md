# De Novo Haem-Binding Maquette Design

This repository contains the design, modelling, and optimisation of an **antiparallel single-chain four-helix bundle (sc4HB)** maquette capable of weak **bis-His haem b** coordination. The project demonstrates how minimal amino acid alphabets can encode stable tertiary structures and how binary patterning of hydrophobic and charged residues directs predictable folding.

## Project Overview
The maquette was designed using a five-residue alphabet (L, K, E, G, H) and connected by flexible Gly₄ linkers. Structure prediction was performed using **AlphaFold2** and **Rosetta**, both producing convergent four-helix-bundle topologies (mean pLDDT ≈ 79; pTM ≈ 0.70). The haem-binding site was introduced by appending His–Gly–Gly motifs to helices 2 and 4, yielding a flexible, low-affinity bis-His geometry with an Nε₂–Nε₂ spacing of 14.6 Å.

## Repository Contents
report/       — project report and figures
models/       — AlphaFold2 and Rosetta model files
sequences/    — amino acid and codon-optimised DNA sequences
scripts/      — codon optimisation and PyMOL visualisation scripts

## Citation
Design principles adapted from foundational *de novo* 4HB work (Regan & DeGrado, 1988; Gibney et al., 1998; Moser et al., 2016; Woolfson et al., 2015).  
All modelling and analysis performed by **Diarmuid Lenihan (2025)** as part of a synthetic biology design project, University of Liverpool.
