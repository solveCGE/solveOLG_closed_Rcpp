# solveOLG closed economy in R/C++
Solves a simple AK-OLG-model for a closed economy in R/C++

## About
Shows how to solve a simple deterministic overlapping-generations model (OLG) of Auerbauch-Kotlikoff type, solving for the transition path between two steady-states. Requires the Rcpp-package <https://github.com/solveCGE/pkgsolveOLG>.

A model description can be found here: <https://github.com/solveCGE/solveOLG_doc>.

## How to run
Parameters can be set in `calib.R`. Policy shocks are defined in `run.R` (or just uncomment some of the predefined exemplary shocks). The model is then solved by just running `run.R`. 

## Author
Philip Schuster
