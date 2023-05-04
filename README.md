# CFD-openFOAM-projects
My CFD projects simulated using OpenFOAM solvers.  
The three projects so far are all multiphase flow problems (water + air) solved using the interFoam solvers in OpenFOAM.  

To run each case, first go into its directory and then run
```
blockMesh
```
This will generate the geometry mesh of the problem. Then run 
```
setFields
```
to set the initial fields of the problems. You can then run 
```
interFoam 
```
to run the simulation. In order to post-process the data you will need to use paraView.  

I encourage you to try changing the files in constant and system to vary the boundary conditions, initial conditions, the fluid properties and etc. 
