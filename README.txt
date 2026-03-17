## Application:

In the zip file "application", the file "real data analysis-code.txt" includes a function "sim_data_fun()" used to generate a simulated data set with two diseases.

The main program is the function "MGTEM2_2". Before using this function, one needs to install the R package "MGTEfun2".

The output results include the regression parameter estimates, standard error estimates, p-values, and likelihood ratio test statistic (-2*log(likelihood ratio)) as well as the associated p-value.  



#########################################
## Simulations:

Before conducting the simulation, one needs to install the R package "MGTEfun2".

To save the computation time in the simulations, we run the 500 replicates under each simulation setup in 5 high-performance computers.

Each of the files "11_1.txt", ...., "11_5.txt" include the code for 100 replicates. In each file, we use parallel computing with 50 cores to further accelerate the computation.

After we have all the results, one needs to put the 5 output files in the working directory and run the code in the file "summary11.txt" to get the summary results. 

The obtained results are similar to these in Table 1 of the main paper with the setting of alpha_k = beta_k=1 and group size 5. The results may be slightly different due to the use of bootstrapping and parallel computing.




