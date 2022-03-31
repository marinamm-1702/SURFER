# SURFER
SURFER: a simple climate model with ice sheet tipping points

## Requisites to running the jupyter notebook

The jupyter notebook containing the code and examples has been written in The Julia Programming Language and uses version 1.5.2. To install Julia follow instructions in https://julialang.org/

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

