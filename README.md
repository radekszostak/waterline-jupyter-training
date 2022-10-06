# Geospatial processing in Python and Jupyter
## Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radekszostak/waterline-jupyter-training/HEAD)\
Run training environment using Binder

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
`jupyter lab`

## Contents of conda environment 
* Jupyter Lab
* Geemap
* Leafmap
* GDAL
* Rioxarray
* Geopandas
