# ABFEconv
protocols for adaptive sampling of absolute binding free energy calcs

Instructions to run adaptive sampling protocol

1 setup jobs to run all windows for 5 ns initially. The input files AM-7209.tar provide an example ready to run on mechagodzilla. 

2 once all jobs have completed, run adaptive.py in the top-level folder (containing bound and free subfolders) to generate a new set of submission scripts. The script must be tweaked to write slurm submission scripts that will work on the local resource used. Save in a file the output of the script for potential future analyses. 

3 The scripts convergence-plots.py and prettyplot.py may be used to produce a text or graphical summary of the convergence as a function of the cumulative sampling time. 
