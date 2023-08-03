# ParametricOpenFOAMCaseExecution
Python class to demonstrate programmatic parametric OpenFOAM CFD case execution. At the moment the class only runs the pitzDaily (axisymmetric 2D flow) tutorial, for which the user can customize both geometry and inlet flow properties. 

By manipulating template files, the class first creates the geometry and boundary conditions. It then runs blockMesh, simpleFoam, foamToVTK, and post-processes the results, velocity magnitude and static pressure, to both 3D (gltf) and 2D (png) figures.
