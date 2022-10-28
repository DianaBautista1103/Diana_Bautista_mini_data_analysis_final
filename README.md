# Diana_Bautista_mini_data_analysis_final
**Both milestone 1 and 2 are contained here.**

##Milestone 1 summary.
From the datateachr package, we explored several databases and ended up picking one to continue doing most of the tasks. 
###Task 1: Choose dataset
-1.1: In my case, I selected 4 data bases (cancer_sample, flow_sample, steam_games, vancouver_trees). 
-1.2: We visualized these four data bases to choose the one we were interested in more. 
-1.3 Narrow choice of databases to 2
-1.4:Come up with one esearch question according to the database selected. 

###Task 2: Exploring the dataset
-2.1: the following activies were selected to carry out using the cancer_sample database:
        1) Explore the relationship between 2 variables in a plot.
        2) Use a boxplot to look at the frequency of different observations within a single variable. You can do this for more than one variable if you wish!
        3) Create a new variable based on other variables in your data (only if it makes sense)
        4) Use a density plot to explore any of your variables (that are suitable for this type of plot).

###Task 3: Write research questions

###Task 4: Process and summarize your data
-4.1: The following questions and activities were done:
    1)Do malign tumors have a higher standard error (in terms of area) than benign tumors?
          Summarizing: (1) Compute the *range*, *mean*, and *two other summary statistics* of **one numerical variable**                         across the groups of **one categorical variable** from your data.
          Graphing: (5) Create a graph out of summarized variables that has at least two geom layers.
    3) Are symmetry and area related to the diagnosis of a patient?
          Summarizing: (3) Create a categorical variable with 3 or more groups from an existing numerical variable. You           can use this new variable in the other tasks!
          Graphing: (7) Make a graph where it makes sense to customize the alpha transparency.
    1)Is symmetry correlated to an increased nuclei area in malign tumors?
          Summarizing: (2) Compute the number of observations for at least one of your categorical variables. Do not use           the function `table()`!
          Graphing: (8) Create 3 histograms out of summarized variables, with each histogram having different sized               bins. Pick the "best" one and explain why it is the best.
    1)Is concavity correlated to the diagnosis of the patient?
          Summarizing: (4) Based on two categorical variables, calculate two summary statistics of your choosing.
          Graphing: (6) Create a graph of your choosing, make one of the axes logarithmic, and format the axes labels so           that they are "pretty" or easier to read.
Documents:
        Diana_Bautista_mini_data_analysis_1_final_reupload.Rmd
        Diana_Bautista_mini_data_analysis_1_final_reupload.md
        Diana_Bautista_mini_data_analysis_1_final_reupload_files
          
          
##Milestone 2 summary.
In this milestone we continued to explore, tidy and manipulate the cancer_sample dataset through ggplot, ggpubr, forcats, broom, and here. 

###Task 1: Tidying the data
-1.1-1.2: My data was tidy since the beginning, so I had to untidy it and return it to its original state. 
-1.3: Choose two research questions

###Task 2: Special Data Types
-2.1  The selected tasks were:   
    -Produce a new plot that reorders a factor in your original plot, using the forcats package (3 points). Then, in a        sentence or two, briefly explain why you chose this ordering (1 point here for demonstrating understanding of the       reordering, and 1 point for demonstrating some justification for the reordering, which could be subtle or               speculative.)
-2.2: Produce a new plot that groups some factor levels together into an “other” category (or something similar), using the forcats package (3 points). Then, in a sentence or two, briefly explain why you chose this grouping (1 point here for demonstrating understanding of the grouping, and 1 point for demonstrating some justification for the grouping, which could be subtle or speculative.)

###Task 3: Modelling
- 3.1 Choose research question and variable:
    Research Question: Does the perimeter of the nuclei correlate with the area in malign tumors?
    Variable of interest: perimeter_mean
-3.2: Find a model that fits the data behaviour 
-3.3: predictions on Y with the created model

###Task 4: Reading and Writing data
Use the here and save/readRDS functions to properly produce the desired files as outputs. 

Documents: 
           Diana_Bautista_mini_data_analysis_2_final.Rmd
           Diana_Bautista_mini_data_analysis_2_final.md
           Diana_Bautista_mini_data_analysis_2_final_files
           Output




Useful sources:
https://resources.github.com/github-and-rstudio/
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
https://r4ds.had.co.nz/r-markdown-workflow.html
https://happygitwithr.com/https-pat.html?q=token#get-a-pat
