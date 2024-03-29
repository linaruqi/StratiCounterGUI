# StratiCounterGUI
a GUI version of StratiCounter(mai winstrup,2016)
If you encounter any problems or have valuable comments and suggestions, please contact via mailbox：linaruqi@hotmail.com

note. the userguide inside has been translated into  Chinese, please find the English version in the original package from StratiCounter-master.

The original version as shown below this line--------------------
> **StratiCounter:** A layer counting algorithm
=========================================
> This algorithm is developed for annual layer counting in paleoclimate archives. The algorithm is based on the principles of statistical inference of hidden states in semi-Markov processes. States, and their associated confidence intervals, are inferred by the Forward-Backward algorithm. The EM (Expectation-Maximization) algorithm is used to find the optimal set of layer parameters for each data batch. Confidence intervals do not account for the uncertainty in estimation of layer parameters. If (absolute) tiepoints are given, the algorithm is run between these, while assuming constant annual layer signals between each pair. If no tiepoints, the algorithm is run batch-wise down the core, with a slight overlap between consecutive batches. See Winstrup (2011) and Winstrup et al. (2012) for further documentation. 

Developed by Mai Winstrup. 
Contact: mai@gfy.ku.dk

When using this script please cite:
Winstrup et al., *An automated approach for annual layer counting in ice cores, Clim. Past.* ***8***, 1881-1895,  2012. 
Also please provide release date of the algorithm: 7/7-2015

The StratiCounter software package
------------------------------
StratiCounter is written in Matlab, and thus running the script requires a Matlab license. 

Released versions of the program can be downloaded from: 
https://github.com/maiwinstrup/StratiCounter/releases

