# pyprojects

### Pseudocode ###

import all libraries

load and organize dataset
  - read csv into panda dataframe

Create a list of different combinations without duplicates:
  for all df columns (select/slice the required columns for analysis)
  - create all possible combinations of columns without duplicates
  - put resulting list of combined columns into a list of lists
  - Iterate through list
  - Set attributess and save
  
Iterate index up to length of list of lists in a loop:
  set colormaps
  set up
  - perform scatter matrix plots
  - run cycler - config, params
  - run subplots as a plot, variables assignment
  - set axes to lines
  - Assign a string from output of formatted strings
  - set title
  - save
  
### Analysis ###

The figures provide a good overall views of the distribution of the data, both the Scatter Matrix and Cycler plotting methods do provide some shapes and configurations that show some patterns. Here are some interesting observations of the different combinations of comparsions of the two methods. Scatter Matrix and Cycler plot:  
    
  - Appears unidirectional, all facing the same way (BMI_BP_S1_S5_S6 Scatter Matrix plot)
  - Showing S1 and S2 are linearly proportionate and quite normally distributed, shown in figure. (BMI_S1_S2_S5_S6 Scatter Matrix plot)
  - S4 appears with about six discrete bars as opposed to scattered out like others
  - Comparing S1 vs S2 from the Scatter Matrix plot and show pattern also in the Cycler one. (BMI_S1_S2_S5_S6 Cycler plot)
  - S3 and S6 appear to complement each other's shape (BMI_BP_S3_S5_S6 Cycler plot)
  
