# SURFER
SURFER: a simple climate model linking CO2 emissions and Solar Radiation Management to sea level rise and ocean acidification.

For a full explanation of the model please check: https://egusphere.copernicus.org/preprints/2022/egusphere-2022-135/

We present the SURFER code and examples to reproduce all figures in the paper using a **jupyter notebook**: https://jupyter.org/.


## Requisites to running the jupyter notebook

The jupyter notebook containing the code and examples has been written in The Julia Programming Language and uses version 1.7.2. To install Julia follow instructions in https://julialang.org/

Additional Julia packages are used and may need to be installed: `DifferentialEquations`, `Plots`, `DelimitedFiles`, `Interpolations`, `Roots`, `LaTeXStrings`. Packages in Julia can be installed with the following comands:

`using Pkg`

`Pkg.add("Package Name")`

## Data from other sources
The repository contains data from other sources. The data is used to force the model (emission scenarios data) or to compare SURFER's output with other models (ZECMIP data).
### SSP emission scenarios
The data contained in folder `scenarios/SSP/` is based on the SSP database hosted by the IIASA Energy Program at https://tntcat.iiasa.ac.at/SspDb.
### RCP emission scenarios
The data contained in folder `scenarios/RCP/` is based on the RCP databased hosted by IIASA Energy Program at https://tntcat.iiasa.ac.at/RcpDb
### ZECMIP results
The data contained in folder `ZECMIP_data/` is freely available and has been downloaded from http://terra.seos.uvic.ca/ZECMIP/index.html
### Data not in the repository
In the paper, SURFER's output is contrasted to results from other references. That data can be found by following the references or by private communication with the authors of those references.
