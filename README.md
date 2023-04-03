# Two-Stage-Robust-Optimization
Two stage robust optimization using a column-and-constraint generation (C&amp;CG) method.
This is an example code for the classical C&CG algorithm for two stage robust optimization, which is programmed by original Python Gurobi solver.

please refer to 

"Zeng B, Zhao L. Solving two-stage robust optimization problems using a column-and-constraint generation method[J]. Operations Research Letters, 2013, 41(5): 457-461."

for more details

Constrains of the Sub Problem have been transformed into Matrix formulations, but the constrains of the Main Problem haven't, so the code may look a little redundancy. I am now trying to transform all the constrains into Matrix formulations
