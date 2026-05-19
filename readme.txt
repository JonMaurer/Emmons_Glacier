README for Emmons project

1. Scripts

Primaries
- emmons_dual_mono.ipynb is primary spin up script with sliding
- emmons_dual_noSlide.ipynb is the 'control' for sliding exps

Experiments:
- emmons_dual_debris_exp.ipynb tests the addition of debris to the SMB field as a step change
- emmons_dual_modern_exp.ipynb provides a step change to modern SMB values
- emmons_dual_SMBelev_exp.ipynb updates a in each timestep
- emmons_dual_modernDebris.ipynb combines exp 1 and 2 

Currently all exp are started from a nonupdating smb, subject to change

Extras:
- all .py files are from refactor, out of date as of May 2026
- emmons_projFile.qgz is QGIS file for initial processing of observational fields

2. Checkpoint files, logs, meshes
- emmons-output-vi.log is norms during model run
- emmons.msh is most recent mesh 
- emmons-initial-y1.h5 is checkpoint for makefile style run
- emmons-SteadyLoResN.h5 is checkpoint for steady state with sliding and no SMB-Elev feedback
- emmons-SteadyLoResNoSlide.h5 is checkpoint w no sliding
- emmons-SteadySMBElev.h5 is checkpoint w sliding and SMB-Elev feedback
