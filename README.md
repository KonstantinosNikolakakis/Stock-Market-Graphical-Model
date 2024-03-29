# Stock-Market
Structure estimation for stock market prices. Real and semi-synthetic data.


Last revision: Dec 2019 (Matlab R2019b) Author: Konstantinos Nikolakakis

The purpose of this code is to support the published paper: "Learning Tree Structures from Noisy Data", AIStats, 2019,
by Konstantinos E. Nikolakakis, Dionysios S. Kalogerias, Anand D. Sarwate

Any part of this code used in your work should cite the above publication.
This code is provided "as is" to support the ideals of reproducible research. Any issues with this code should be reported by email to k.nikolakakis@rutgers.edu. 

The code is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License available at https://creativecommons.org/licenses/by-nc-sa/4.0/

Description:

 1) Stock_Market.m: The tree structured graphical model approximation of stocks is evaluated. 
 The estimation is based on real data (finance.yahoo.com). 
 The estimated structure is presented in Tree_structure_estimate.pdf. 

 2) Stock_Market_Noisy.m: Synthetic noise is added to the trend of the closing prices. 
 For a sufficient number of samples, structure estimation is feasible from noisy data as well. 
 The 3D plot of the average number of incorrect edges of the estimated structure is provided in Average_number_of_mismatched_edges.pdf
