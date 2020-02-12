# SLAPPaperMeshFiles

This directory contains the meshes (.bdf-files) and an interface description file for:
F. Naets, T. Devos, A. Humer, J. Gerstmayr: A non-invasive system-level model order reduction scheme for
flexible multibody simulation, International Journal of Numerical Methods in Engineering (2020).

![Four bar mechanism](FourBarModel.png)

Besides the trivial 'ground' body, The system consists of three component model described by a Nastran compatible mesh file: Bar1, Bar2, and UpperBar. 

## Connectivity overview
First we give an overview of which 'frames' should be defined and then indicate which frames should be joined. 

### Frame overview
Ground body frames:
G1_L at 1e-3*[0;2.50000023841858;0]
G1_R at 1e-3*[50;2.50000023841858;0]
G2_L at 1e-3*[-7.45058059692383e-7;137.5;0]
G2_R at 1e-3*[50;137.5;0]

### Joint overview
All joints considered are revolute joints:



