SIPs is a parallel sparse eigensolver for real and symmetric generalized eigenvalue problems. Motivated by quantum chemistry and material science applications, where a large portion of eigensolutions are required, SIPs was initially developed in 2007.<sup>1</sup> Built on top of [PETSc](https://www.mcs.anl.gov/petsc/) and [SLEPc](http://slepc.upv.es/) libraries, SIPs solves the eigenvalue problem with distributed spectrum slicing method. Thanks to improvements in the robustness and efficiency of the underlying mathematical libraries, a later implementation of SIPs demonstrated scalability of the eigensolver beyond 200,000 cores for matrices with more than 500,000 rows.<sup>2,3</sup> SIPs is integrated into, [SIESTA](https://departments.icmab.es/leem/siesta/), an initio molecular dynamics package and it is also part of [ELSI](https://wordpress.elsi-interchange.org/).<sup>5</sup> A more recent implementation of SIPs is now available in [SLEPc](http://slepc.upv.es/) package. 

## Publications
1. Zhang, H.; Smith, B.; Sternberg, M.; Zapol, P. 

SIPs: Shift-and-Invert Parallel Spectral Transformations. ACM Trans. Math. Softw. 2007, 33, 9–es. [DOI=10.1145/1236463.1236464](doi.org/10.1145/1236463.1236464)
2. Campos, C.; Román, J. E. 

Strategies for Spectrum Slicing Based on Restarted Lanczos Methods. Numer. Algorithms 2012, 60, 279–295.
[DOI=10.1007/s11075-012-9564-z](doi.org/10.1007/s11075-012-9564-z)
3. Keçeli, M.; Zhang, H.; Zapol, P.; Dixon, D. A.; Wagner, A. F. 

Shift-and-Invert Parallel Spectral Transformation Eigensolver: Massively Parallel Performance for Density-Functional Based Tight-Binding. J. Comput. Chem. 2016, 37, 448–459.
[DOI=10.1002/jcc.24254](doi.org/10.1002/jcc.24254)
4. Keçeli M.; Corsetti F.; Campos C.; Roman J.; Vâzquez-Mayagoitia A;  Zhang, H.; Zapol, P.; & Wagner A, F. 

SIESTA-SIPs: Massively parallel spectrum-slicing eigensolver for an ab initio molecular dynamics package. (under review, 2018)
