# SIR-Model
A fairly basic stochastic SIR model

This model uses a SIR disease model framework and the mechanics of a simple disease propagation game to model the process of a disease through a population. Using the given parameters the code generates a population and then assess the progress of a disease itterativly through it and the result is graphed.

As of 4/12/2020 the available parameters to adjust are:
  1) Initial population demographics (number susceptible, infected, immune, total population size)
  2) Amount of interaction between people
  3) Rate of recovery from infection
  4) Probability of transmission of infection
  5) Probability of death from infection
  
  Eventually I'd like to add:
    1) Susceptibility gradient so immunity isn't all or nothing
    2) Infection severity gradient and associated changes to recovery/death probabilities
    3) Spatial component where interactions are restricted to neighboring people in the population
