# social-brain
This software performs the numerical solutions and produces the parameter-sweep figures for the paper “Inference of ecological and social drivers of human brain-size evolution”, by Mauricio González-Forero and Andy Gardner.

DifferentialGameSolver.zip contains MATLAB computer code to obtain approximated numerical solutions to the evolutionary differential game (Supplementary Information Eqs. 15) with GPOPS. The GPOPS code is to be run in MATLAB and was prepared for GPOPS 2.3 in MATLAB R2015b in Linux Debian 8.9. For the contents in this zip file, the top file is brainNashDeep.m.

When executing the contents of DifferentialGameSolver.zip: the file guessDeep.mat provides an initial guess; the file solutionDeep.mat provides the solution for the final iteration of the OCP; the file solutionNashDeep.mat provides the solution for all the iterations of the OCP; and the file solutionNashDeep.txt is the output in the MATLAB command prompt when executing brainNashDeep.m.

SolutionExtraction.zip contains MATLAB and R computer code to extract solutions obtained with the code in DifferentialGameSolver.zip.

PParameterSweep.zip contains cvs files with the results of SolutionExtraction.zip. These cvs files contain the following data. In column 1, age [years]; column 2, observed brain mass in an average H. sapiens female [kg]; ; column 3, observed body mass in an average H. sapiens female [kg]; column 4, predicted brain mass [kg]; column 5, predicted body mass [kg]; and column 6, predicted skill level [TB].

The parameters P1, P2, P3 are respectively denoted by etas, etaC, and etac in DifferentialGameSolver.zip, SolutionExtraction.zip, and PParameterSweep.zip.
