# RRDecon

To install and use the package  you can run in R:
-library(devtools)
-install_github('RRDecon','hernanmp')
-library(RRDecon)

This an R package based on the methods from the paper "A deconvolution path for mixtures".  The main functions in the package R:
- L2_deconvolution_path
- L1_deconvolution_path
These allow to compute the solution path with different regularization penalties L2 and L1 respectively.  

Other useful functions are:
- L2_deconvolution
- L1_deconvolution

The source folder also contains a file called "Demo.R"  that has an example on how to call the functions. You can also  see the documentation for each individual function.

