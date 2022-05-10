# Seinfeld-Bottle-Problem-Optimization
This repository contains a solution to an optimization problem inspired by a bottle-recycling scheme hatched by the characters of the show Seinfeld. It was designed and implemented in Julia/JuMP with peers as the final project for the class ECE 524: Introduction to Optimization at the University of Wisconsin-Madison.

In Season 7, Episodes 21 & 22 of Seinfeld, the characters Kramer and Newman hatch a scheme to profit from recycling bottles in Michigan for 10 cents per bottle. They live in New York City, so the cost of gas and renting a truck previously meant it was not worth the drive to recycle the bottles. However, in these two episodes, they are able to use a truck for free and decide this is the opportunity to make a profit recycling hundreds of bottles.

In our project, we investigate this “bottle deposit” problem and evaluate whether we could make a profit recycling bottles following this scheme. We consider not only Michigan, but also seven other states where we could recycle the bottles. We vary factors like the number of cars/trucks available, the price of gas, the maximum cost we are willing to pay, and the potential cost of legal punishment (since this scheme is technically illegal).

We first model this problem mathematically, describing assumptions, variables, constraints, and an objective function. We then implement the problem in Julia/JuMP, discuss the results, and explore how the outcome is altered by making adjustments to our assumptions and constraints. Interestingly enough, the solution to our initial model turns out to be sending all the bottles to Michigan, which is the same solution posed given in Seinfeld. 

The project, including the mathematical model, code implementation, and discussion, is entirely contained in the Final_Project_Report.ipynb file. 
