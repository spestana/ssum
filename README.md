# ssum

[Snow Sensor Usability Maps (Google Earth Engine)](https://code.earthengine.google.com/?scriptPath=users%2Fspestana%2Fssum%3Amain)

## Setting up the python environment

Set up the python environment using conda and the provided environment.yml file:

`conda env create -f environment.yml`

Alternatively, set up the environment manually with conda:

`conda create --name ssumenv`

`conda activate ssumenv`

`conda install xarray rioxarray pandas numpy matplotlib`

`conda install -c anaconda ipykernel`

`python -m ipykernel install --user --name=ssum`

`conda env export > environment.yml`
