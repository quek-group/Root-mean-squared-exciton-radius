# Root-mean-squared-exciton-radius
Simple program to calculate rms radius of exciton from  an a3dr file generated by plotxct.x in the BGW suite

Please consider citing: K Ulman & SY Quek, Nano Lett. 2021, 21, 8888−8894 
-----------------------------------------------------------------------------------------------------------------

This code is written with a ZnPc/MoS2 organic-2D heterostructure system in mind:
 1. The position vector of the hole is on the ZnPc molecule (C atom)
 2. The electronic wavefunction is generated with this hole position using plotxct.x in the BGW suite.
 3. a3dr file is used for the code 
 4. One can use a z-bound on the electronic wavefunction to consider only the part of the wavefunction that lies 
    on the MoS2 layer (these lines are commented out)
