# FAST-Algorithm

This repository implements the FAST algorithm [(Aonghus Shortt and Mark O'Malley, 2014)](https://github.com/nnhjy/FAST-Algorithm/blob/main/documentation/2014-UCED-heuristic-algorithm-FAST.pdf) with Julia programming language. 

FAST employs rolling schedule, a heuristic approach, to solve unit commitment and economic dispatch (UCED) decision problems of generation units affiliated to one demand node. A equivalent mixed integer (linear) problem (MIP) is documented [here](https://github.com/nnhjy/FAST-Algorithm/blob/main/documentation/FAST-Algorithm.pdf). 

[MIP.ipynb](https://github.com/nnhjy/FAST-Algorithm/blob/main/MIP.ipynb) provides a JuMP model formulation of the MIP, where the tiny test system is established under the [*Spine generic data model (data strucure)*](https://doi.org/10.1016/j.softx.2021.100967) managed by [`SpineInterface.jl`](https://github.com/Spine-project/SpineInterface.jl) and [`Spine toolbox`](https://github.com/Spine-project/Spine-Toolbox). 