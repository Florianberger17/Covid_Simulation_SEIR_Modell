# Covid simulation according to the SEIR model
## by F. Berger, D. Umlandt, A. Bloh

Within the project, the infection incidence at the beginning of the corona pandemic in Germany from March 2020 onwards is beeing investigated using two approaches: (i) a deterministic approach for which the above DGL system is solved numerically and (ii) a stochastic approach in which the infection incidence is simulated with a discrete Markov chain. 

## SEIR model
The SEIR model for mathematically modeling the spread of infectious diseases divides the individuals in a population into four groups. S(Suspectible) describes the number of individuals who are susceptible to infection. Individuals in group E (Exposed) are already infected but not yet infectious themselves. The number of infectious individuals is designated as I (Infectious) and the number of recovered individuals as R (Recovered).

## Simulation using the deterministic aproach
The most common approach to simulation with the SEIR model is to solve the PDE system. This can be performed efficiently with the DGL solver Scipy Library library. 

## Simulation using the stochastic approach
One disadvantage of the deterministic approach is that it can only be used to describe an average course of the pandemic. A stochastic approach, on the other hand, can be used to simulate various possible courses and analyze the range of fluctuation between these courses.

## Key Insights
- An unchecked spread of the Covid-19 pandemic would have led to high infection rates and potentially overwhelmed the healthcare system
- The enforcement of quarantine measures for infected persons and contact persons is an effective means for federal and state governments to demand the spread of infection
- Based on the results of the study, a "failure" of the pandemic with the parameters chosen for calibration, which are based on the real situation in Germany in March 2020, therefore appears very unlikely. 



