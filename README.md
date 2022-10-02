# TPM802A: Model-based Assessments for Water Systems - Assignment 2: River Basin Analysis 

Maanav Jhatakia | 5551307

The following repository is for Assignment 2 of the TPM802A Model-based Assessments for Water Systems course at TU Delft. 
These files concern decision-making using a model on the Nile River basin in north-eastern Africa (specifically between Egypt, Sudan, and Ethiopia). 
All policies and necessary data emerge from the water_systems folder. The main files are the following: 

1. River_basin_tradeoffs.ipynb: This is the file that looks at trade-off analysis between different policy options. This was also 
where initial policy choice and compromising policies were chosen for further analysis. 

2. River_basin_sensitivity_vulnerability_robustness.ipynb: global sensitivity analysis, vulnerability analysis, and robustness analysis was conducted 
in this file. Results of png files of plots/graphs that were exported were all transferred manually to the "figs" folder for purposes of cleanliness. 

3. policies_chosen_for exploration.csv: a temporary csv file used in River_basin_sensitivity_vulnerability_robustness.ipynb that isolated 
which policies from the initial set of 8 will be used for the simulation and further analysis. 

Please ensure that "Baseline_wheeler.csv" is added to water_systems/stochastic_data_generation_inputs before any files are run. 
All necessary Python packages needed for this assignment are present in the ipynb files. 
