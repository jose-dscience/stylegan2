# INSTRUCTIONS TO INSTALL PYTHON PACKAGES IN ULYSSES

1. Module must be loaded, in this case: `module load intelpython3/3.6.8`
2. IF environment does not exist, it must be installed:
   1. `conda create -n tf tensorflow`
3. Before activating, we can check if the module is installed: `conda env list`
   1. If we want to remove an environment, it can be done with: `conda remove --name tf`
4. The we can activate it: `source activate tf`

