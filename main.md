# PyRx Algorithm

1) Download PyRx 0.8 (Free Version is sufficient): https://pyrx.sourceforge.io/downloads
2) Load the receptors into PyRx in the AutoDock macromolecules format. 
3) Load the ligands into PyRx. 
5) Perform energy minimization on the ligands (200 steps) through the Open Babel uff (Universal Force Field) energy parameters. 
6) Convert ligands into the AutoDock format. 
7) Select the AutoDock ligand and AutoDock macromolecule in Vina Wizard
8) Expand the PyRx search space: pull on the grid box so that it contains the whole binding site. 
9) Conduct a docking analysis through the Vina Wizard within the PyRx workspace
10) Binding affinities (kcal/mol) and the upper and lower bounds of the root-mean-square deviation (RMSD) are calculated. 
