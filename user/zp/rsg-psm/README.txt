#================================================================
This demo is used to demostrate the pseudo-spectral method based on 
rotated staggered grid configuration. This work is published in Geophysical
Prospecting (doi:10.1111/1365-2478.12543).  

When you run this demo you need the following source codes:

Mtwolayer2dti.c and Mtwolayer3dti.c to produce model parameters;

Mtti2delastic_cpml.c and Mhti3delastic.c to propagate the wavefield in 2D/3D;

if you want to further decouple the elastic wavefields, you need the 
Mtti2delrdec_stiffiness.c program.

