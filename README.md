# GABA, L-arginine and L-lysine on Ca-montmorillonite
Molecular dynamics simulations of γ-aminobutyric acid (GABA), L-arginine and L-lysine adsorbing on Ca-montmorillonite (STx-1b), alone and in the two binary mixtures.
## Please cite as
> Stewart, S. V.; Braeuer, R.; Erastova, V. Non-proteinogenic γ-aminobutyric acid reorganises L-arginine and L-lysine adsorption on Ca-montmorillonite through selective displacement and Ca²⁺ bridging. *ChemRxiv* **2025**, version 2. <https://doi.org/10.26434/chemrxiv-2025-nrsm5/v2>
## Files
Each `.gro` file is the GROMACS structure of that simulation. Each `.xtc` file keeps every 10th frame of the original simulation output and is stored with Git LFS.
| Run | System | Structure | Trajectory |
| --- | --- | --- | --- |
| Arginine | L-arginine on Ca-montmorillonite | [arg_all.gro](arg_all.gro) | arg_all.xtc |
| Lysine | L-lysine on Ca-montmorillonite | [lys_all.gro](lys_all.gro) | lys_all.xtc |
| GABA | GABA on Ca-montmorillonite | [gab_all.gro](gab_all.gro) | gab_all.xtc |
| GABA + arginine | GABA with L-arginine | [gab_arg_all.gro](gab_arg_all.gro) | gab_arg_all.xtc |
| GABA + lysine | GABA with L-lysine | [gab_lys_all.gro](gab_lys_all.gro) | gab_lys_all.xtc |
## Download
The structures come down with a normal clone. The trajectories need Git LFS, once per machine. The five deposited trajectories keep every 10th saved frame.
    git lfs install
    git clone https://github.com/Erastova-group/GABA_Arg_Lys.git
