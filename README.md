[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radekszostak/waterline-jupyter-training/HEAD?labpath=notebook.ipynb)

## Machine configuration
1. Install anaconda on your computer (installer at https://www.anaconda.com/). During installation, confirm the inclusion of anaconda in the PATH environment variable:\
![](https://i.stack.imgur.com/x30M7.png)
2. Download training repository from https://github.com/radekszostak/waterline-jupyter-training/archive/refs/heads/main.zip and unzip.
3. Open command prompt and change working directory to unzipped folder in order to:
* Create conda environment using environment.yml file\
`conda env create --name gis-env --file=environments.yml`
* Activate conda environment\
`conda activate gis-env`
* Run Jupyter Lab\
`jupyter lab`

## Contents of conda environment 
* Jupyter Lab with GeoJSON extension
* Geemap
* Ipyleaflet
* GDAL
* Rioxarray
* Geopandas
