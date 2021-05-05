# AOtrainingCBR

The file "Train Retrieval and Adaptation Together 1.1.ipynb" is a jupyter note book that contains everything needed to carry out the experiments in the paper, Harmonizing Case Retrieval and Adaptation with Alternating Optimization: First Lessons (Under Review, ICCBR 2021)

EXCEPT that the data sets are not included. The URLs are provided for each data set to download it.

## How to replicate an experiment

In the following instruction, `XXX` refers to a section of name XXX

Run `Import`
  
Choose a dataset from `Data` and run the corresponding section, for example, `Data (Airfoil)`

Tune parameters in `Preparation and global parameters`. If you are not sure what parameters to use, you can refer to the previous recorded settings, for example `Results (Airfoil )`->`In order, Alpha 1`

Run from `Preparation and global parameters` to `Test the models`, this includes data preprocessing (standardizing), defining models, training models, and testing

## How to run experiment on other data sets

To do so, add a section like `Data(XXX)` to load data. Everything else remains the same as "How to replicate an experiment"
