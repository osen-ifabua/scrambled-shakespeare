## Investigating Evolutionary Optimisation
An experiment based on a model which evolves a randomly generated string into a target string consisting of a line from a Shakespeare sonnet.

## The Big Question
How does the sequence length affect the performance of this model?

## Methodology
The model measures the closeness of a string to the target, i.e. the fitness, using Hamming distance from the target. Hence, the fittest string has the lowest Hamming distance.
The fittest string is selected from N random L-length strings produces N mutated offspring strings. Each character in a string has a probability p of being randomly altered.
This process is iterated for a maximum of G generations or until convergence, in this model, when the Hamming distance is below or equal to 2.

## Summary
This experiment showed that increasing the sequence length increased the final Hamming distance after a maximum number of 1000 generations.
It also showed that the relative error between the target and random string increased as the sequence length increased.
This indicated that increasing the sequence length made optimisation more difficult for this model.

## NOTE
The full write-up (methology, analysis, limitations, etc.) and the code for this project are located in the notebook: Investigating_Evolutionary_Optimisation.ipynb

## How to run
Open the notebook in Google Colab.

#### Written for 'Modelling for Big Data' at University of Leeds, (2026).
