# 4dTracking
Work completed in 4-dimensional tracking studies for ATLAS during the BU Physics Geneva Study Abroad Program.

The notebook ClassifactionNN provides a simple classification neural network created with ROOT TMVA and PyTorch to distinguish between hard-scatter and pile-up tracks. The goal of this neural network was to illustrate that the addition of timing information increases performance.

The notebook SigandBackTrees can be used to construct two ROOT trees containing the signal and background data to be used for NN training. In this example, the input variables are transverse momentum, pseudorapidity, and time. Three different uncertainties in the timing information are used: 30, 60, and 90 ps.  
