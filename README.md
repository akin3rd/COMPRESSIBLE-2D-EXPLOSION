# COMPRESSIBLE-2D-EXPLOSION

This repository contains the 2D code for a cylindrical explosion modelled using the Euler Equations in FORTRAN.
The HLLC and Rusanov fluxes were used to address the Riemann Problem at the interface between cells; serving as inputs for a Riemann solver.
Both Flux methods were paired with the Barth and Jespersen Limiter and a MUSCL scheme was used for overall numerical approximation.

All rights to the original authors of the code.
