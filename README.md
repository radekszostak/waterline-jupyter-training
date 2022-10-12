# About
This repository contains the files needed for the training conducted by the Waterline project on October 6, 2022.
# Ways to access the Jupyter environment for geospatial analysis
## Binder
You can run temporary training environment using Binder\
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radekszostak/waterline-jupyter-training/HEAD)
## Planetary computer
Microsoft Planetary Computer (https://planetarycomputer.microsoft.com/) provides Jupyter environment for geospatial processing. Environmental scientists can apply for free access to this platform.
## Machine configuration
You can also configure your own machine. To do this follow steps below:
1. Install anaconda on your Linux system (or Linux subsystem for Windows). You can download an installer from https://www.anaconda.com/.
2. Clone training repository from github\
`git clone https://github.com/radekszostak/waterline-jupyter-training`
3. Change working directory\
`cd waterline-jupyter-training`
4. Create conda environment using environment.yml file\
`conda env create --name gis-env --file=environment.yml`
5. Activate conda environment\
`conda activate gis-env`
6. Run Jupyter Lab\
`jupyter-lab`
7. Open in web browser an URL displayed in console after running jupyter-lab
