# SVD-ROM: SVD-based Reduced-Order Modeling for large-scale data

SVD-ROM is an open-source Python package to perform scalable Reduced Order Modeling (ROM) of large-scale dynamical systems using the Singular Value Decomposition(SVD). It leverages Dask for out-of-core parallel computing, enabling the processing of huge arrays on standard hardware such as laptops. The current focus is on the Dynamic Mode Decomposition (DMD), although future work will focus on other algorithms such as the Spectral Proper Orthogonal Decomposition (SPOD). Applications include climate and weather modeling and the analysis of fluid flows, among others.

An overview of SVD-ROM can be found here: https://doi.org/10.5281/zenodo.18468075
