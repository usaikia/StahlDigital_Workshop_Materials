# Workshop Materials: StahlDigital Meets Industries

In this repository you will find the Jupyter Notebooks from our latest workshop `StahlDigital Meets Industries` organized by our project `StahlDigital`. The Notebooks explains how to run simulation workflow from atomistic to continuum scale. The Notebooks are inside the folder `00_pyiron_damask_tutorial/`

Here is a short description to the Notebooks:
- Notebook 1 (`01_introduction_to_pyiron.ipynb`): General introduction to pyiron.
- Notebook 2 (`02_damask_tensile_test_simulation.ipynb`): Shows how to setup and run damask tensile test simulation with pyiron. Also (second part of the notebook), how run lammps simulation, get elastic constants, and used them to run damask simulation.
- Notebook 3 (`03_damask_multiplerolling.ipynb`): Shows how to setup and run damask rolling simulation with pyiron. In this notebook, we will get the damask input parameters from DSMS and use them to run the pyiron job.
- Notebook 4 (`04_lammps_damask_workflow.ipynb`): Show how to run lammps jobs for Fe-Al alloys with different Al concentration to calculate elastic constants, use these elastic constants to run damask tensile test simulation for these alloys.

To run these notebooks directly in your webbrowser click on the `MyBinder` link below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/usaikia/StahlDigital_Workshop_Materials.git/HEAD?labpath=00_pyiron_damask_tutorial)
