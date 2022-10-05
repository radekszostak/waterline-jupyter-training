# Waterline Python and Jupyter training
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radekszostak/waterline-jupyter-training/HEAD?labpath=notebook.ipynb)

## Linux configuration
Environment should be configured on Linux system
1. Install anaconda on your Linux system (or Linux subsystem for Windows). You can download an installer from https://www.anaconda.com/.
2. Download training repository from https://github.com/radekszostak/waterline-jupyter-training/archive/refs/heads/main.zip and unzip.
3. Open command prompt and change working directory to unzipped folder in order to:
* Create conda environment using environment.yml file\
`conda env create --name gis-env --file=environments.yml`
* Activate conda environment\
`conda activate gis-env`
* Run Jupyter Lab\
`jupyter lab`

## Contents of conda environment 
* Jupyter Lab
* Geemap
* Leafmap
* GDAL
* Rioxarray
* Geopandas
