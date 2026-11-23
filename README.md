# GABA, L-arginine and L-lysine on Ca-montmorillonite

Molecular dynamics simulations of γ-aminobutyric acid (GABA), L-arginine and L-lysine adsorbing on Ca-montmorillonite (STx-1b), alone and in the two binary mixtures.

## Please cite as
> S. V. Stewart, R. Braeuer and V. Erastova, Non-proteinogenic γ-aminobutyric acid reorganises L-arginine and L-lysine adsorption on Ca-montmorillonite through selective displacement and Ca²⁺ bridging. *ChemRxiv* **2025** (version 2). <https://doi.org/10.26434/chemrxiv-2025-nrsm5/>

## Files
Each `.gro` file is the GROMACS structure of that simulation. Each `.xtc` file keeps every 10th frame of the original simulation output.

| Run | System | Structure | Trajectory |
| --- | --- | --- | --- |
| Arginine | L-arginine on Ca-montmorillonite | [arg_all.gro](arg_all.gro) | arg_all.xtc |
| Lysine | L-lysine on Ca-montmorillonite | [lys_all.gro](lys_all.gro) | lys_all.xtc |
| GABA | GABA on Ca-montmorillonite | [gab_all.gro](gab_all.gro) | gab_all.xtc |
| GABA + arginine | GABA with L-arginine | [gab_arg_all.gro](gab_arg_all.gro) | gab_arg_all.xtc |
| GABA + lysine | GABA with L-lysine | [gab_lys_all.gro](gab_lys_all.gro) | gab_lys_all.xtc |


## Ca-montmorillonite structure

The clay model is made by [ClayCode](https://github.com/Erastova-group/ClayCode), matching the experimentally determined structure of STx-1b from [The Clay Mineral Society](https://clays.org/source-clays-data/#phychem).

The structure of the clay used in this work is: 

(Ca<sub>0.286</sub>Na<sub>0.057</sub>K<sub>0.057</sub>)[Al<sub>3.343</sub>Fe<sub>0.229</sub>Mg<sub>0.429</sub>][Si<sub>7.743</sub>Al<sub>0.257</sub>]O<sub>20</sub>(OH)<sub>4</sub>

## Visualisation in VMD

Load a .gro structure and its .xtc trajectory, then unwrap the whole system. 
A periodic clay sheet may look strange with VMD's static bonds, so the sheet is best drawn with dynamic bonds (increase cutoff) and VDW spheres. 


## Download

The structures will download with a normal clone. 
The trajectories are larger (150 MB) and will likely need Git LFS.
```
git lfs install
git clone https://github.com/Erastova-group/GABA_Arg_Lys.git
```
