# Radial-Field-of-Views MATLAB package
Radial sampling patterns in frequency space to support anisotropic field of views (FOVs) in the dual domain


This archive includes Matlab functions to design acquisition schemes
for radial fourier/frequency space sampling that will support the desired field-of-view (FOV), where the primary application is for MRI acquisition trajectories in k-space.
Included are design functions for 2D and 3D radial frequency space sampling, as well as 
PROPELLER MRI trajectories.  As a recent addition, C-file implementations for designing
elliptical FOV trajectories are included.

Within Matlab, use "help Radial-Field-of-Views" for information on the design
functions included in this package.  Documentation on each specific
function is also included.

This package accompanies the journal article and conference abstract:
Peder E.Z. Larson and Paul T. Gurney and Dwight G. Nishimura.
"Anisotropic Field-of-Views in Radial Imaging."
IEEE Transactions on Medical Imaging. 27(1): 47-57 (2008).

Peder E. Z. Larson, M. Lustig, and Dwight G. Nishimura. “Anisotropic field-of-view shapes for improved PROPELLER imaging.” Magn Reson Imaging, 27(4):470–479, May2009. PMC2882965.


Another recent addition is a 2D golden angle ordering (with anisotropic FOV) and a 3D golden angle ordering (only isotropic FOV).  There is currently a need for a
- 3D anisotropic FOV golden angle strategies

Originally Designed by Peder Larson and Paul Gurney, also contributions from Wenwen Jiang
(c) 2007-2014, Board of Trustees, Leland Stanford Junior University and The Regents of the University of California. 

