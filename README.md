# ProteomePhyto
A proteome allocation model for phytoplankton thermal responses

## The model
Our coarse-grained model is built on a constrained optimization problem that aims to maximize the steady-state growth rate of a generic phytoplankton cell considering temperature, irradiance levels, and external dissolved inorganic nitrogen and carbon concentrations.

The model is written in Julia and contains three files:

par.jl defines the parameter values
eqn.jl defines the model equations
save.jl runs the model over environmental conditions and saves model output
plot.jl plots model output and saves it as a pdf file
Julia packages required to run the code above: JuMP, Ipopt, CSV, DataFrames, Plots
