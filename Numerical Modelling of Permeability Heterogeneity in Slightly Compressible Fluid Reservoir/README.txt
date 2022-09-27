Numerically solving 1-D and 2-D diffusivity equation (1-ϕ 2D Reservoir Mini-Simulator) with varying permeability (heterogeneous reservoir) with methods like implicit and explicit solution by Finite Volume Method (FVM) and discretization and verifying the solution using CMG software for any number of block sizes.

1. 1-D Heterogeneous Model solved implicitly and explicitly:
   Input file is created for reservoir properties and no. and size of grid blocks.
   Input Boundary conditions as Dirichlet for first block and Neumann (no flow) for last block.
   Estimating Dykstra-Parsons Heterogeneity coefficient.
   Equivalent permeability and Diffusivity (eta) values are estimated for each block and interblock and checking stability criteria.
   Estimating pressure values for each block at any time using Explicit and Implicit formulations.
   Generating output file with eta and pressure values.
   Plot for pressure responses.
2. 2-D Homogeneous and Heterogeneous Model solved explicitly:
   Input file is created for reservoir properties and no. and size of grid blocks.
   Input surface production rate at center block with no flow boundary.
   Estimating Dykstra-Parsons Heterogeneity coefficient.
   Equivalent permeability and Diffusivity (eta) values are estimated for each block and interblock along x- and y-directions and checking stability criteria.
   Estimating pressure values for each block at any time using Explicit formulation.
   Plotting 3D surface of pressure responses.
   Generating Dynamic Heatmap of the pressure simulation.
   Pressure diagnostic plot of Homogeneous case.