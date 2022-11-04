[![](http://waterlineproject.eu/images/logo.png)](http://waterlineproject.eu/)
# About
This repository contains the files needed for the training conducted as part of the Waterline project on October 6, 2022. For more practical information on processing geospatial data in Python, see the excellent course at https://www.earthdatascience.org/courses/use-data-open-source-python/.
# Ways to access the Jupyter environment for geospatial analysis
## Binder
You can run temporary training environment using Binder\
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radekszostak/waterline-jupyter-training/HEAD)
## Planetary computer
Microsoft Planetary Computer (https://planetarycomputer.microsoft.com/) provides Jupyter environment for geospatial processing. Environmental scientists can apply for free access to this platform.
## Conda based configuration
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
`jupyter-lab "--NotebookApp.token=''", "--NotebookApp.password=''"`
7. Open Jupyter in web browser http://localhost:8888.

## Docker based configuration
You can run geospatial processing environment using docker:
1. Install docker (https://docs.docker.com/get-docker/) on machine with any operating system.
2. Run docker image\
`docker run -p 8888:8888 -w /home/workdir rszostak/gis-jupyter`
3. Open Jupyter in web browser: http://localhost:8888
4. In Jupyter open console and clone training repository\
`git clone https://github.com/radekszostak/waterline-jupyter-training`
