These are the STL file for our festo finger gripper. 
----

The designs of the festo fingers themselves are available
solid_edge format, and have been converted to solid_works, but we tried printing them and our printer material
is not flexible enough. If you want to print them yourself for testing you can export the solid_edge files to STL.


To print the festo finger gripper, there are 4 STL files, you need to print 2 copies of some.
  - 2x "Platte.STL"
  - 2x "Arm.STL"
  - 2x "Arm1.STL"
  - 1x "Arm2.STL"

Depending on the quality of your 3D printer, some holes may need to be drilled by hand to friction fit the metal pins
which hold the gripper together. 
Also, we usually sand some of the parts were they rub against each other to avoid sticking.
We also usually open and close the gripper for a while in a script to break it in. You'll want to watch it at the 
beginning as it can get stuck. More sanding or a bit of lubricant might help speed up breaking it in. 

The festo_open_simple, sw-hand-closed-3 and sw-hand-open STL files are complete assemblies which can converted to
.dae and used for as simplified collision meshes in a URDF. 
