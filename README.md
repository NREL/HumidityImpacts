# Humidity Impacts

## Git Large File Storage (LFS)
This repository contains a number of EnergyPlus input data files (.idf). To better manage these files, Git Large File Storage (LFS) is utilized.

Git LFS installation instructions are [here](https://git-lfs.github.com/). Files that are tracked by Git LFS are identified in the `.gitattributes` file located in the root of the repository. No explicit commands are needed to retrieve Git LFS content as long as Git LFS is installed.

To clone the repository more quickly (and skip LFS downloads), perform (on Linux or macOS):
```
GIT_LFS_SKIP_SMUDGE=1 git clone https://github.com/NREL/HumidityImpacts.git
```
using HTTPS, or using SSH:
```
GIT_LFS_SKIP_SMUDGE=1 git clone git@github.com:NREL/HumidityImpacts.git
```
On Windows (using HTTPS):
```
set GIT_LFS_SKIP_SMUDGE=1
git clone https://github.com/NREL/HumidityImpacts.git
```
Or using SSH:
```
set GIT_LFS_SKIP_SMUDGE=1
git clone git@github.com:NREL/HumidityImpacts.git
```
