# Genetic Algorithm in R
This is a project where we create a genetic algorithm from scratch in R to select the best features to use in a GLM.

### Technologies
* R

## Project Description
The purpose of this project was to create a genetic algorithm for variable selection in a GLM.
This directory contains the selections algorithm itself inside R/select.R which takes in a dataset, the name of the response variable,
and various other inputs, and outputs the variables in that dataset that best fits a GLM.

This algorithm also takes in many additional inputs that would change how the genetic algorithm functions. 
The user could specify different selection methods, mutation rates, generation size, min and max number of generations, various stopping criteria, number of crossover points, etc. Changes to these parameters often leads to different results.

More details about the project, including information on the data used, tests, and logic are included in the project_report file in this folder.
